<template>
  <div class="main__div">
    <div class="logo__bar">
      <div class="logo">
        <img src="BOOStudio_Logo.png" alt="logo" />
      </div>
      <div class="buttons">
        <img src="menu.svg" class="menu" alt="menu-icon" />
        <button>BOOHUB&#8594;</button>
      </div>
    </div>
    <hr />
    <div>
      <p>Home/ Contact / <span>Business Enquiries </span></p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
@media only screen and (max-width: 960px) {
  .main__div {
    padding: 1% 0% !important;
  }
  button {
    padding: 1%;
    font-size: 10px;
  }
}
.logo {
  width: 50%;
}
.menu {
  width: 50px;
}
.buttons {
  flex-direction: row-reverse;
  width: 50%;
  display: flex;
}
.main__div {
  padding: 32px 111px 22.1px 123px;
  border: 0px solid black;
  background: #fffbfa;
}
.logo__bar {
  display: flex;
  height: 55px;
}
button {
  background-color: #cf551c;
  color: #ffffff;
  border: none;
  padding: 2%;
  font-size: 16px;
  font-weight: 600;
  border-radius: 2.5px;
}
p {
  font-size: 16px;
  color: #8c8c8c;
  margin-left: 19%;
}
span {
  color: black;
}
</style>
