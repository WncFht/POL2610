<script setup lang="ts">
withDefaults(
  defineProps<{
    items: string[]
    prefix?: string
  }>(),
  {
    prefix: 'Refs',
  }
)
</script>

<template>
  <div class="source-strip">
    <span class="source-prefix">{{ prefix }}</span>
    <span v-for="item in items" :key="item" class="source-chip">{{ item }}</span>
  </div>
</template>

<style scoped>
.source-strip {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.35rem;
  margin-top: 0.45rem;
}

.source-prefix {
  font-size: 0.64rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #64748b;
  font-weight: 700;
}

.source-chip {
  display: inline-flex;
  align-items: center;
  border-radius: 999px;
  padding: 0.14rem 0.48rem;
  font-size: 0.66rem;
  font-weight: 700;
  color: #29415a;
  background: rgba(224, 234, 246, 0.95);
  border: 1px solid rgba(45, 90, 136, 0.18);
}
</style>
