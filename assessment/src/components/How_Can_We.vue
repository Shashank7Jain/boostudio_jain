<template>
  <div class="main__div">
    <div class="how">
      <h3><b>How can we Help you?</b></h3>
      <p class="subheading">
        Choose a category below so we can get back to you as soon as possible.
      </p>
    </div>
    <div class="cards">
      <div class="business">
        <img src="bar-chart.png" height="50" width="50" alt="" srcset="" />
        <h4>Business Enquiries</h4>
        <p class="image_subheading"><b>Contact Us</b></p>
      </div>
      <div class="career">
        <img src="resume.png" height="50" width="50" alt="" srcset="" />
        <h4>Career Openings</h4>
        <p class="image_subheading"><b>Careers</b></p>
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
  height: 152px;
}
.image_subheading {
  color: #cf551c;
  font-size: 16px;
}
.subheading {
  font-size: 18px;
  font-weight: 700;
}
h4 {
  font-size: 24px;
}
h3 {
  font-size: 40px;
}
.career {
  margin-left: 1.5%;
  background: #fdf8f5;
  padding: 4% 7%;
}
.business {
  background: #fdf8f5;
  border: 1px solid #cf551c;
  padding: 4% 7%;
}
.main__div {
  margin-top: 128.2px;
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

@media only screen and (max-width: 960px) {
  h3 {
    font-size: 30px;
  }
  h4 {
    font-size: 18px;
  }
  .subheading {
    font-size: 12px;
    font-weight: 700;
  }
  .how {
    height: 100px;
  }
  .image_subheading {
    color: #cf551c;
    font-size: 10px;
  }
  .main__div {
    margin-top: 64.2px;
    flex-direction: column;
    height: 180px;
    align-items: center;
    justify-content: center;
    text-align: center;
  }
}
</style>
