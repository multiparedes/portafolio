<script setup lang="ts">
import { DropdownMenuSeparator, type DropdownMenuSeparatorProps } from 'radix-vue'

const props = defineProps<DropdownMenuSeparatorProps>()
</script>

<template>
  <DropdownMenuSeparator v-bind="props" class="-mx-1 my-1 h-px bg-slate-100 dark:bg-slate-800" />
</template>
