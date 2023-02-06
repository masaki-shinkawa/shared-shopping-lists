<template>
  <div>
    <div
      id="g_id_onload"
      data-client_id="989412605567-djerugsq4f00ed90plegrt2i3lklf92d.apps.googleusercontent.com"
      data-context="signin"
      data-login_uri="http://localhost:3000"
      data-auto_select="true"
      data-itp_support="true"
    >
      aaaaa
    </div>
  </div>
</template>

<script setup lang="ts">
useHead({
  script: [
    { src: "https://accounts.google.com/gsi/client", async: true, defer: true },
  ],
});
</script>
