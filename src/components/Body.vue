<template>
    <div class="google-search">
        <div class="search-bar">
            <img src="../assets/Google-Logo.gif" alt="" class="google-img">
            <div class="search">
                <input type="text" class="search-input">
            </div>
            <div>
                <button class="button-design">Google Search</button>
                <button class="button-design">I'm feeling lucky</button>
            </div>
            <div>
                <p class="language-text-design">Google offered in:
                    <a href> Română </a>
                    <a href> Magyar </a>
                    <a href> Deutsch </a>
                </p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Body'
}
</script>

<style scoped>
    .google-search {
  text-align: center;
  padding-top: 7%;
}
.google-img {
  justify-content: center;
  width: 391px;
  height: 220px;
  border-radius: 20px;
}

.search-input {
  margin-top: 30px;
  width: 582px;
  height: 44px;
  border: none;
  box-shadow: 0px 0px 1px 1px;
  outline: none;
  padding-left: 10px;
  border: 1px solid #dfe1e5;
  box-shadow: none;
  border-radius: 24px;
  z-index: 3;
}

.search-input:hover {
  box-shadow: 0px 0px 6px 2px;
  color: rgb(226, 226, 226);
}

.button-design {
    font-size: 15px;
  margin-top: 30px;
  height: 36px;
  width: 130px;
  
  background-color: F8F9FA;
  border: transparent;
  color: #3c4043;
  border-radius: 3px;
  font-family: arial, sans-serif;
}

.button-design:hover {
  border-color: #adadad;
  box-shadow: 0px 0px 3px 1px;
}

.language-text-design {
  padding-top: 30px;
  font-size: 13px;
  font-family: arial, sans-serif;
}
</style>