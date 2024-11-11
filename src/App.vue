<template>
  <div>
    <fieldset>
      <legend>App.vue</legend>
      <table>
        <tr>
          <td>NODE_ENV</td>
          <td>{{ NODE_ENV }}</td>
        </tr>
        <tr>
          <td>VUE_APP_MY_ENV</td>
          <td>{{ VUE_APP_MY_ENV }}</td>
        </tr>
        <tr>
          <td>VUE_APP_MY_TITLE</td>
          <td>{{ VUE_APP_MY_TITLE }}</td>
        </tr>
        <tr>
          <td>VUE_APP_MODE</td>
          <td>{{ VUE_APP_MODE }}</td>
        </tr>
      </table>
    </fieldset>
    <fieldset>
      <legend>模式和环境变量的关系</legend>
      <div>
        <p><a href="https://cli.vuejs.org/zh/guide/mode-and-env.html#示例：staging-模式" target="_blank">https://cli.vuejs.org/zh/guide/mode-and-env.html#示例：staging-模式</a></p>
      </div>
    </fieldset>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      NODE_ENV: process.env.NODE_ENV,
      VUE_APP_MY_ENV: process.env.VUE_APP_MY_ENV,
      VUE_APP_MY_TITLE: process.env.VUE_APP_MY_TITLE,
      VUE_APP_MODE: process.env.VUE_APP_MODE,
    };
  },
};
</script>
