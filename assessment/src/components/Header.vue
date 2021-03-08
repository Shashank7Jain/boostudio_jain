<template>
  <div class="main__div">
    <div class="logo__bar">
      <div>
        <img src="BOOStudio_Logo.png" height="55px" width="207" alt="logo" />
      </div>
      <div>
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
    height: auto;
    padding: 2% 5%;
    border: 0px solid black;
    background: #fffbfa;
  }
}
.main__div {
  height: auto;
  padding: 32px 111px 22.1px 123px;
  border: 0px solid black;
  background: #fffbfa;
}
.logo__bar {
  display: flex;
  justify-content: space-between;
}
button {
  background-color: #cf551c;
  color: #ffffff;
  border: none;
  padding: 14%;
  font-size: 16px;
  font-weight: 600;
  border-radius: 2.5px;
  margin-right: 5px !important;
}
p {
  font-size: 16px;
  color: #8c8c8c;
}
span {
  color: black;
}
</style>
