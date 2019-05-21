<template>
  <g>
    <circle :fill="st2" cx="-213.2" cy="322.7" r="54.2"/> <!-- ear -->
    <circle :fill="st2" cx="-696.5" cy="322.7" r="54.2"/> <!-- ear -->
    <path :fill="st3" d="M-454.8,635.2L-454.8,635.2c-133.3,0-241.7-108.3-241.7-241.7V176.8h391.7c54.2,0,95.8,41.7,95.8,95.8v129.2 C-213.2,526.8-321.5,635.2-454.8,635.2z"/> <!-- face -->
  </g>
</template>

<script>
import AvatarComponent from '@/components/avatar-components/AvatarComponent';
export default {
  extends: AvatarComponent,
}
</script>