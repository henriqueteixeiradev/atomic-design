<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div class="services">
    <Service
      title="Front-End"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Asperiores magni a maxime odio dolorem reprehenderit accusantium quo voluptatum nam, ad, qui eveniet amet, veritatis enim tempora nesciunt cum velit rerum!"
    />
    <Service
      title="Back-End"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Asperiores magni a maxime odio dolorem reprehenderit accusantium quo voluptatum nam, ad, qui eveniet amet, veritatis enim tempora nesciunt cum velit rerum!"
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Asperiores magni a maxime odio dolorem reprehenderit accusantium quo voluptatum nam, ad, qui eveniet amet, veritatis enim tempora nesciunt cum velit rerum!"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { Service } from '@/components/molecules/';

export default defineComponent({
  components: { Service },
});
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
