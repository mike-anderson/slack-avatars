<template>
  <g>
    <circle :fill="st1" cx="-575.7" cy="351.8" r="29.2"/> <!-- eye -->
    <circle :fill="st1" cx="-334" cy="351.8" r="29.2"/> <!-- eye --> 
    <path :fill="st1" d="M-559,285.2h-37.5c-8.3,0-16.7-4.2-16.7-16.7l0,0c0-8.3,4.2-16.7,16.7-16.7h33.3c8.3,0,16.7,4.2,16.7,16.7l0,0 C-542.3,276.8-550.7,285.2-559,285.2z"/> <!-- eyebrow -->
    <path :fill="st1" d="M-313.2,285.2h-33.3c-8.3,0-16.7-4.2-16.7-16.7l0,0c0-8.3,4.2-16.7,16.7-16.7h33.3c8.3,0,16.7,4.2,16.7,16.7 l0,0C-300.7,276.8-304.8,285.2-313.2,285.2z"/> <!-- eyebrow -->
  </g>
</template>

<script>
import AvatarComponent from '@/components/avatar-components/AvatarComponent';
export default {
  extends: AvatarComponent,
}
</script>