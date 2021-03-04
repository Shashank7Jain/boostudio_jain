<template>
  <div class="main__div">
    <div class="logo__bar">
        <div>
<img src="BOOStudio_Logo.png" height="30px" alt="logo" />
        </div>
      <div>
        <button>BOOHUB &#8594;</button>&nbsp;&nbsp;&nbsp;
        <span>menu</span>
      </div>

    </div>
    <hr />
    <div>
      <p>Home/ Contact/ <b> Business Enquiries</b></p>
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
  height: 80px;
  padding: 10px 30px;
  border: 0px solid black;
  background: #f2f2f2;
}
.logo__bar {
  display: flex;
  justify-content: space-between;
}
.main__div__section {
  display: flex;
}
button {
  background-color: #cf551c;
  color: #ffffff;
  border: none;
  height: 2em;
  font-weight: 500;
  border-radius: 2.5px;
  margin-left: 5px !important;
}
p {
  font-size: 0.69rem;
  text-align: center;
}
hr {
  border-top: 0.01px solid #9e9e9e;
  
}
</style>
