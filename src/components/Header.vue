<template>
  <div class="google-header">
    <div>
      <img
        class="img"
        src="../assets/me.jpeg"
        title="Google-Account: bogdanandreias1923@gmail.com"
      />
    </div>
    <div class="header-icons">
      <i class="material-icons">apps</i>
      <a href="#">Images</a>
      <a href="#">Gmail</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
.google-header {
  width: 100%;
  max-height: 200px;
  float: right;
  font-family: sans-serif;
}

.google-header img {
  max-width: 100%;
  border-radius: 50%;
}

.img {
  border-radius: 50%;
  width: 32px;
  float: right;
  margin-right: 15px;
  margin-top: 20px;
  cursor: pointer;
  margin-top: 24px;
}

.header-icons {
  float: right;
  width: 200px;
  margin-top: 28px;
  margin-right: 10px;
}

.header-icons .material-icons {
  font-size: 25px;
  float: right;
  margin-right: 20px;
  cursor: pointer;
}

.header-icons .material-icons:hover {
  background-color: rgb(172, 172, 172);
  border-radius: 50%;
}

.header-icons a {
  float: right;
  margin-right: 15px;
  color: rgb(53, 52, 52);
  text-decoration: none;
  font-size: 14px;
}

.header-icons a:hover {
  color: gray;
}
</style>>