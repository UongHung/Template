
<template>
  <div class="relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0">
    <link
      href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css"
      rel="stylesheet"
    />

    <div class="max-w-3xl mx-auto sm:px-6 lg:px-8">
      <div class="bg-purple-400 overflow-hidden shadow sm:rounded-lg p-4">
        <div class="flex justify-end p-2">12:07, Wednesday, 3rd December, 2022</div>


        <div class="text-center p-3 text-2xl font-semibold">
          <h3><div class="block"><el-avatar :size="50" :src="circleUrl"></el-avatar></div> Uong Van Hung</h3>
        </div>
        <div class=" p-3 text-2xl">
          <p>
           You have new comment about...
          </p>
        </div>

        <div class="p-3 flex justify-center">
          <el-button type="primary" round>Go to post</el-button>
        </div>


      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Nuxtcomment",
};
import Vue from "vue";
import ElementUI from "element-ui";
import "element-ui/lib/theme-chalk/index.css";
import App from "./comment.vue";

Vue.use(ElementUI);

new Vue({
  el: "#app",
  render: (h) => h(App),
});
</script>
