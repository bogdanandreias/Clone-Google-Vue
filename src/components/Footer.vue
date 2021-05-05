<template>
  <div class="google-footer">
    <div class="first-footer">Romania</div>
    <div class="second-footer row">
      <div class="first-row">
        <a href>About</a>
        <a href>Advertising</a>
        <a href>Business</a>
        <a href> How Search works</a>
      </div>
      <div class="second-row">
        <a href>Privacy</a>
        <a href>Terms</a>
        <a href>Settings</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: "Footer",
};
</script>

<style scoped>
.google-footer {
  position: fixed;
  left: 0;
  bottom: 0;
  height: 95.4px;
  width: 100%;
  background-color: #f2f2f2;
  color: rgb(111, 111, 111);
  text-align: start;
}

.google-footer a {
  float: left;
  margin-right: 15px;
  color: #787f82;
  text-decoration: none;
  font-size: 14px;
  padding-left: 15px;
}

.first-footer {
  font-size: 15px;
  height: 48px;
  padding-left: 30px;
  font-family: arial, sans-serif;
  padding-top: 12px;
  border-bottom: 1px solid #dadce0;
  color: #787f82;
}

.second-footer {
  height: 46px;
  padding-left: 25px;
  font-family: arial, sans-serif;
  align-items: center;
}

.first-row {
  padding-left: 10px;
}

.second-row {
  margin-left: auto;
  padding-right: 35px;
}
</style>