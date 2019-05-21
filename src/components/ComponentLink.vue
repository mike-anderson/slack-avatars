<template>
    <component :is="component" :data="data" v-if="component" />
</template>
<script>
export default {
    name: 'a-component',
    props: ['data', 'type'],
    data() {
        return {
            component: null,
        }
    },
    computed: {
        loader() {
            if (!this.type) {
                return null
            }
            return () => import(`./avatar-components/${this.type}`)
        },
    },
    mounted() {
        this.loader()
            .then(() => {
                this.component = () => this.loader()
            })
            .catch(() => {
                this.component = () => import('./avatar-components/AvatarComponent')
            })
    },
}
</script>