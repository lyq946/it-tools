<script setup lang="ts">
const md = `
# Dev Tools Hub

## About
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod, nisl quis
mollis blandit, nunc nisl aliquam nunc, vitae aliquam nisl nunc vitae nisl.

- Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- Sed euismod, nisl quis mollis blandit, nunc nisl aliquam nunc, vitae aliquam nisl nunc vitae nisl.

[dev-tools-hub](https://tools.cxyroad.com)
`;
</script>

<template>
  <c-markdown :markdown="md" />
</template>
