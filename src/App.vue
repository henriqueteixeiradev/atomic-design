<template>
  <HomeTemplate />
</template>
/

<script lang="ts">
import { defineComponent } from 'vue';
import { HomeTemplate } from '@/components/templates';

export default defineComponent({
  components: { HomeTemplate },
});
</script>

<style lang="scss" scoped>
.component {
  margin: 5rem;
}
</style>
