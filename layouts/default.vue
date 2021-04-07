<template>
<div class="overall">
    <navbar class="nav-cmp"/>
    <Nuxt />
</div>
   
</template>

<script>
 import navbar from "@/components/navbar";
export default {
   components: {
          navbar
        },
}
</script>
