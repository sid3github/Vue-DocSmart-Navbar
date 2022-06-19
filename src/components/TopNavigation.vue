<template>
  <div class="top-navigation">
    <div class="logo">
      <img src="@/assets/docsmart_logo.png" alt="" />
    </div>
    <div class="nav-tabs">
      <div class="tab-1">
        <p>Dashboard</p>
      </div>
      <div class="tab-2">
        <p>Feed</p>
        <span>&#8964;</span>
      </div>
      <div class="tab-3">
        <p>Store</p>
      </div>
    </div>
    <div class="nav-icons">
      <div class="icons">
        <img class="icon-img-1" src="@/assets/social-media.svg" alt="" />
      </div>
      <div class="icons">
        <img class="icon-img-2" src="@/assets/alert.svg" alt="" />
      </div>
      <div class="icons">
        <img class="icon-img-3" src="@/assets/support.svg" alt="" />
      </div>
      <div class="icons">
        <img class="icon-img-4" src="@/assets/bubble-chat.svg" alt="" />
      </div>
      <div class="icons">
        <img class="icon-img-5" src="@/assets/notification-bell.svg" alt="" />
      </div>
    </div>
    <div class="profile">
      <div class="profile-img">
        <img
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT7Nd5QJdhzApS-CVTJD26Sgf1G1qxMo2WL7w&usqp=CAU"
        />
      </div>
      <div class="profile-text">
        <p>D K Bose</p>
        <h6>Doctor</h6>
      </div>
      <div class="caret">
        <p>&#8964;</p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "TopNavigation",
};
</script>
<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.top-navigation {
  display: grid;
  grid-template-columns: 15% 30% 1fr 15%;
  padding: 0.5rem 1rem;
  box-shadow: 0 8px 6px -6px #00000021;
}

li {
  list-style: none;
}

a {
  text-decoration: none;
}

.nav-tabs {
  display: flex;
  justify-content: flex-start;
  align-items: center;
}

.tab-1,
.tab-2,
.tab-3 {
  margin-right: 5rem;
}

.tab-2 {
  display: flex;
  align-items: center;
}

.tab-2 span {
  position: relative;
  top: -5px;
  left: 10px;
  font-size: x-large;
}

.nav-icons {
  display: flex;
  justify-content: flex-end;
  align-items: center;
}

.icons {
  margin-right: 2.5rem;
}

.icons img {
  width: 30px;
  height: 30px;
  object-fit: cover;
}

.profile {
  display: flex;
  justify-content: start;
  align-items: center;
}

.profile-img img {
  width: 60px;
  height: 60px;
  object-fit: cover;
  border-radius: 50%;
}

.profile-text {
  margin-left: 1rem;
}

.caret {
  margin-left: 6rem;
}

.caret p {
  font-size: xx-large;
}

@media screen and (max-width: 1480px) {
  .logo img {
    width: 125px;
    position: relative;
    top: 16px;
  }

  .nav-tabs {
    justify-content: center;
  }

  .tab-1,
  .tab-2,
  .tab-3 {
    margin-right: 2rem;
  }

  .caret {
    margin-left: unset;
  }
}
</style>