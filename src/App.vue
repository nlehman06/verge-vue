<template>
    <div id="app" class="h-full">
		<navComponent/>
        <top/>
    </div>
</template>

<script>
import Top from "./components/Top.vue";
import NavComponent from "./components/NavComponent";

export default {
  name: "app",
  components: {
    NavComponent,
    Top
  }
};
</script>
