
<template>
  <div
    class=" relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0"
  >
    <link
      href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css"
      rel="stylesheet"
    />

    <div class="max-w-3xl mx-auto sm:px-6 lg:px-8">
      <div class="bg-purple-400 overflow-hidden shadow sm:rounded-lg p-4">
        <div class="flex justify-end p-2">Wednesday, 3rd December, 2008</div>

        <div
          class="text-4xl p-4 with-60 bg-purple-500 text-center"
        >
          Title Post
        </div>
        <div class="text-center p-3 text-2xl font-semibold">
          <h3>Hi Hung,</h3>
        </div>
        <div class="text-center p-3 text-2xl bg-fuchsia-400">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam
            semper diam at erat pulvinar, at pulvinar felis blandit. Vestibulum
            volutpat tellus diam, consequat gravida libero rhoncus ut. Maecenas
            imperdiet felis nisi, fringilla luctus felis hendrerit sit amet.
            Pellentesque interdum, nisl nec interdum maximus, augue diam
            porttitor lorem, et sollicitudin felis neque sit amet erat.
          </p>
        </div>

        <div class="p-3 flex justify-center">
          <el-button type="primary" round>Watch now</el-button>
        </div>
        <hr />
        <div class="text-center">
          <p>Regards,</p>
          <p class="p-2">NAME</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NuxtTutorial",
};
import Vue from "vue";
import ElementUI from "element-ui";
import "element-ui/lib/theme-chalk/index.css";
import App from "./Tutorial.vue";

Vue.use(ElementUI);

new Vue({
  el: "#app",
  render: (h) => h(App),
});
</script>
