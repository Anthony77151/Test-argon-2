<template>
    <div id="app">
        <router-view name="header"></router-view>
        <main>
            <fade-transition origin="center" mode="out-in" :duration="250">
                <router-view/>
            </fade-transition>
        </main>
        <router-view name="footer"></router-view>
    </div>
</template>
<script>
import { FadeTransition } from "vue2-transitions";

export default {
  components: {
    FadeTransition
  }
};
</script>
<style>
@font-face {
  font-family: "Font global";
  src: url("./font/Alice-Regular.ttf");
}
@font-face {
  font-family: "Ma fonte";
  src: url("./font/AlexBrush-Regular.ttf");
}
</style>
