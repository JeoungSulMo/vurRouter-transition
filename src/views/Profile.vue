<template>
  <div class="mainContainer">
    <router-link to="/">리마인드레터링</router-link>
    <hr />
    <div id="nav">
      <router-link to="/purchase">구매하기</router-link>|
      <router-link to="/review">고객후기</router-link>|
      <router-link to="/profile">프로필</router-link>|
      <router-link to="/basket">장바구니</router-link>
    </div>
    <hr />
    <h1>프로필</h1>
    <br>
    <router-link to="/profile/editProfile">프로필 수정하기</router-link>
  </div>
</template>
<script>
export default {
  components: {}
};
</script>

<style>
</style>