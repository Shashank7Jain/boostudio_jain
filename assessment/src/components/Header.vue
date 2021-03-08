<template>
  <div class="main__div">
    <div class="logo__bar">
      <div>
        <img src="BOOStudio_Logo.png" height="55px" width="207" alt="logo" />
      </div>
      <div>
        <button>BOOHUB &#8594;</button>&nbsp;&nbsp;&nbsp;
        <img src="menu.svg" alt="" width="100" height="40" />
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
.main__div {
  height: 193px;
  padding: 32px 111px 22.1px 123px;
  border: 0px solid black;
  background: #f2f2f2;
}
.logo__bar {
  display: flex;
  justify-content: space-between;
}
button {
  background-color: #cf551c;
  color: #ffffff;
  border: none;
  height: 55px;
  width: 151px;
  font-size: 18px;
  font-weight: 600;
  border-radius: 2.5px;
  margin-left: 5px !important;
}
p {
  font-size: 20px;
}
hr {
  border-top: 1px solid #9e9e9e;
}
</style>
