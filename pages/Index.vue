<template>
    <div class="pageHome">
        <theme class="theme"></theme>
    </div>
</template>

<script>
import theme from "../components/theme.vue";
export default {
  name: "index",
  components: {
    theme
  }
};
</script>

<style lang="stylus" scoped>
.pageHome {
    display: flex;
    flex-direction: column;
}

.theme {
    position: fixed;
    flex: 1;
    top: 0;
    left: 0;
    right: 0;
}
</style>
