<script setup lang="ts">
const props = withDefaults(
  defineProps<{
    label?: string
    title: string
    body?: string
    accent?: 'blue' | 'gold' | 'red' | 'green' | 'ink'
  }>(),
  {
    label: '',
    body: '',
    accent: 'blue',
  }
)
</script>

<template>
  <div class="evidence-card" :class="`accent-${props.accent}`">
    <div v-if="props.label" class="evidence-label">{{ props.label }}</div>
    <div class="evidence-title">{{ props.title }}</div>
    <div v-if="props.body" class="evidence-body">{{ props.body }}</div>
  </div>
</template>

<style scoped>
.evidence-card {
  border-radius: 22px;
  padding: 0.82rem 0.9rem 0.88rem;
  background: rgba(255, 251, 244, 0.88);
  border: 1px solid rgba(31, 41, 55, 0.12);
  box-shadow: 0 10px 24px rgba(15, 23, 42, 0.08);
  display: flex;
  flex-direction: column;
  gap: 0.32rem;
  min-height: 152px;
}

.evidence-label {
  font-size: 0.64rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  font-weight: 700;
  opacity: 0.9;
}

.evidence-title {
  font-family: "Source Serif 4", Georgia, serif;
  font-size: 1.02rem;
  line-height: 1.12;
  font-weight: 700;
  color: #152238;
}

.evidence-body {
  font-size: 0.82rem;
  line-height: 1.35;
  color: #334155;
}

.accent-blue {
  border-top: 6px solid #2d5a88;
}

.accent-gold {
  border-top: 6px solid #b9851f;
}

.accent-red {
  border-top: 6px solid #9f3d33;
}

.accent-green {
  border-top: 6px solid #54785b;
}

.accent-ink {
  border-top: 6px solid #1f2937;
}
</style>
