<template>
  <div class="social-networks">
    <SocialLint name="Github" to="https://github.com" icon="github.svg" />
    <SocialLint name="Twitter" to="https://twitter.com" icon="twitter.svg" />
    <SocialLint name="Facebook" to="https://facebook.com" icon="facebook.svg" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { SocialLint } from '@/components/atoms';

export default defineComponent({
  components: { SocialLint },
});
</script>

<style lang="scss" scoped>
.social-networks {
  display: grid;
  grid-gap: 1rem;
}
</style>
