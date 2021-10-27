<template>
  <node-view-wrapper class="dom" as="td">
    <node-view-content class="content-dom" />
  </node-view-wrapper>
</template>

<script>
import { NodeViewWrapper, NodeViewContent } from "@tiptap/vue-3";
import { nodeViewProps } from "@tiptap/vue-3";

export default {
  components: {
    NodeViewWrapper,
    NodeViewContent,
  },
  props: {
    ...nodeViewProps,
  },
};
</script>

<style>
</style>