<script setup lang="ts">
const props = defineProps({
  total: {
    type: Number,
    required: true,
  },
});
</script>

<template>
  <div class="flex justify-between items-center py-3">
    <div class="text-slate-800 font-bold text-lg md:text-2xl md:px-2">
      សរុប <span class="font-bold">{{ arabicToKhmer(props.total) }}</span
      >ឯកសារ
    </div>
  </div>
</template>
