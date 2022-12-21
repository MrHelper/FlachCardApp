<template>
  <div class="w-100 h-100 d-flex align-center justify-space-between">
    <!-- 👉 Footer: left content -->
    <span class="d-flex align-center">
      &copy;
      {{ new Date().getFullYear() }}
      Made With
      <VIcon
        icon="mdi-heart-outline"
        color="error"
        size="1.25rem"
        class="mx-1"
      />
      By <a
        href="https://fb.com/mr.helperz"
        target="_blank"
        rel="noopener noreferrer"
        class="text-primary ms-1"
      >Mr. Helper</a>
    </span>
  </div>
</template>
