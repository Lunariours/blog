<template>
  <!-- <router-link></router-link> -->
  <a href="" class="tag">
    <slot></slot>
  </a>
</template>

<script>
export default {
	name: 'e-tag'
};
</script>

<style lang="scss" scoped>
.tag {
  position: relative;
  margin-left: torem(6.4px);
  color: #aaa;
  font-size: torem(16px);
  font-weight: lighter;
  transition: color 0.4s ease-out;

  &:hover {
    color: var(--theme-color);
  }
}
</style>
