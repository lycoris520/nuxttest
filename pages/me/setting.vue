<template>
  <div>
        <ul>
        <li @click="$router.replace('/me')">hh替换</li>
        <router-link to="/me/center">e</router-link>
    </ul>
</div>
</template>
<script>
export default {
  components: {}
};
</script>

