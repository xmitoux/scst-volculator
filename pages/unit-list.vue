<template>
  <div>ユニット一覧ページ</div>
</template>

<script lang="ts">
import { defineComponent } from '@vue/composition-api';
export default defineComponent({
  middleware: 'authenticated',
});
</script>
