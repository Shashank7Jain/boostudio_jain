<template>
  <div class="main__div">
    <div class="how">
      <h3><b>How can we Help you?</b></h3>
      <p>
        Choose a category below so we can get back to you as soon as possible.
      </p>
    </div>
    <div class="cards">
      <div class="business">
        <img src="bar-chart.png" height="50" width="50" alt="" srcset="" />
        <h4>Business Enquiries</h4>
        <p>Contact Us</p>
      </div>
      <div class="career">
        <img src="resume.png" height="50" width="50" alt="" srcset="" />
        <h4>Career Openings</h4>
        <p>Careers</p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "How_Can_We",
};
</script>
<style scoped>
.how {
  margin-bottom: 3%;
}
.career {
  margin-left: 1.5%;
  background: #fdf8f5;
  padding: 2% 7%;
}
.business {
  background: #fdf8f5;
  border: 1px solid orange;
  padding: 2% 7%;
}
.main__div {
  flex-direction: column;
  height: 350px;
  align-items: center;
  justify-content: center;
  text-align: center;
}
.cards {
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}
</style>
