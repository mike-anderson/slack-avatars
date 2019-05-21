<template>
  <g>
    <path :fill="st1" d="M-300.7,68.5H-434l0,0c0-75,58.3-133.3,133.3-133.3l0,0V68.5z"/> <!-- hair -->
    <path :fill="st1" d="M-704.8,89.3H-559l0,0c0,79.2-62.5,145.8-145.8,145.8l0,0V89.3z"/> <!-- hair -->
    <path :fill="st1" d="M-588.2,101.8h112.5l0,0c0,62.5-50,112.5-112.5,112.5l0,0V101.8L-588.2,101.8z"/> <!-- hair -->
  </g>
</template>

<script>
import AvatarComponent from '@/components/avatar-components/AvatarComponent';
export default {
  extends: AvatarComponent,
}
</script>