<template>
  <AntInput>
    <template #prefix>
      <slot name="prefix"></slot>
    </template>
    <template #addonAfter>
      <slot name="addonAfter"></slot>
    </template>
    <slot></slot>
  </AntInput>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import {Input} from 'ant-design-vue';

export default defineComponent({
  name: 'UIInput',
  components: {AntInput: Input},
})
</script>

<style lang="scss" scoped>
</style>
