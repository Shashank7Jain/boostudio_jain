<template>
  <div class="main__div">
    <div class="business_main">
      <div class="business__enquiries">
        <p class="sub__heading">Business enquiries</p>
        <h1>Visit one of our agency locations or contact us today</h1>
        <p class="business_desc">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit sed do eiusmod
          tempor incididunt ut labore
        </p>
        <p class="sub__heading">Address</p>
        <span>
          101-103 Illawarra Road, Marrickville,<br />
          NSW 2204, Sydney, Australia. <br />
        </span>
        <p class="sub__heading">Opening Hours</p>
        <span>Monday to Saturday:9:00 to 16.pm</span>
      </div>

      <img src="people.svg" alt="interview" class="people_img" srcset="" />
    </div>
    <div class="leave_main">
      <img src="business_first_dots.svg" class="first_dots" alt="dots" />
      <img src="arrow.svg" alt="arrow" class="arrow" />
      <img src="ellipse.svg" alt="ellipse" class="first_ellipse" />
      <img src="ellipse.svg" alt="ellipse" class="second_ellipse" />
      <img
        src="business_second_dots.svg"
        alt="second_dots"
        class="second_dots_one"
      />
      <img
        src="business_second_dots.svg"
        alt="second_dots"
        class="second_dots_two"
      />
      <img src="curls.svg" alt="curls" class="curls" />
      <div class="leave">
        <h1 class="leave_heading">Leave a message</h1>
        <p class="leave_sub_heading">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut blandit
          arcu in pretium.
        </p>
        <table>
          <tr>
            <td>
              <input
                type="text"
                name="first_name"
                id="first_name"
                placeholder="First name"
              />
            </td>
            <td>
              <input
                type="text"
                name="last_name"
                id="last_name"
                placeholder="First name"
              />
            </td>
          </tr>
          <tr>
            <td>
              <input type="text" name="Email" id="Email" placeholder="Email" />
            </td>
            <td>
              <input type="text" name="Phone" id="Phone" placeholder="Phone" />
            </td>
          </tr>
          <tr>
            <td>
              <input
                type="text"
                name="Company"
                id="Company"
                placeholder="Company"
              />
            </td>
            <td>
              <input
                type="text"
                name="Select Your position"
                id="Select Your position"
                placeholder="Select your position"
              />
            </td>
          </tr>
          <tr>
            <td>
              <input
                type="text"
                name="date"
                id="date"
                placeholder="02/01/2021"
              />
            </td>
            <td>
              <input
                type="text"
                name="Specify your budget"
                id="Specify your budget"
                placeholder="Specify your budget"
              />
            </td>
          </tr>
          <tr>
            <td colspan="2" width="100%">
              <textarea
                name="Tell us what your are looking"
                id="tell_us"
                placeholder="Tell us what your are looking"
              ></textarea>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <button class="upload">
                Upload File
                <span class="upload_sub_heading">(Max File Size 15MB)</span>
              </button>
            </td>
          </tr>
        </table>

        <br />
        <button type="submit" class="request">SEND REQUEST</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Business_Enquiries",
};
</script>
<style scoped>
@media only screen and (max-width: 960px) {
  .main__div {
    display: flex;
    margin: 10% 10%;
    flex-direction: column;
  }
  .request {
    font-size: 12px !important;
  }
  .arrow {
    position: absolute;
    top: 4px !important;
    right: 7px !important;
    z-index: 2;
  }
  input {
    font-size: 11px !important;
  }
  textarea {
    font-size: 11px !important;
  }
  .business__enquiries {
    padding: 0% !important;
    margin: 0% !important;
  }
  .main__div > * + * {
    margin-top: 10px;
  }
  .people_img {
    width: 370px;
  }
  .people_img {
    margin-left: 0% !important;
  }
}
.people_img {
  margin-left: 20%;
}

.business_desc {
  font-size: 20px;
}

textarea {
  width: 502px;
  height: 175px;
}

.leave_sub_heading {
  margin-bottom: 5%;
  padding-right: 20%;
}
.upload_sub_heading {
  font-size: 9px;
  color: #9e9e9e;
}
.leave_main {
  margin-top: 9%;
  position: relative;
}
span {
  font-size: 16px;
}
.arrow {
  position: absolute;
  top: 29px;
  right: 46px;
  z-index: 1;
}
.curls {
  position: absolute;
  bottom: -23px;
  right: -29px;
  z-index: 1;
}
.first_ellipse {
  position: absolute;
  top: 0px;
  right: -51px;
  z-index: -2;
}

.second_ellipse {
  position: absolute;
  bottom: -31px;
  left: -62px;
  z-index: -1;
}
.second_dots_one {
  position: absolute;
  bottom: 44px;
  left: -44px;
  z-index: -1;
}
.second_dots_two {
  position: absolute;
  bottom: 129px;
  left: -44px;
  z-index: -1;
}
.first_dots {
  position: absolute;
  top: -23px;
  right: -10px;
  z-index: -1;
}
.business__enquiries {
  padding-right: 22%;
  padding-bottom: 5%;
  padding-left: 15%;
  margin-left: 11%;
}
.sub__heading {
  color: #cf551c;
  font-weight: 700;
  font-size: 18px;
}
.main__div {
  display: flex;
  align-items: center;
  justify-content: center;
}
input {
  width: 81%;
  padding: 9%;
  border: 0px;
  font-size: 16px;
}
textarea {
  border: 0px;
  font-size: 16px;
  border: 0px;
  width: -webkit-fill-available;
}

td {
  width: 50%;
  padding: 5px 5px;
}
tr {
  width: 100%;
}
table {
  border-collapse: separate;
  border-spacing: 0 2px;
  width: 100%;
}
.upload {
  display: block;
  padding: 2% 3%;
  justify-content: center;
  text-align: center;
  width: 100%;
  background-color: #ffffff;
  border: 0px;
  font-size: 16px;
  color: #8c8c8c;
}
img {
  max-width: 100%;
  height: auto;
}
.request {
  display: block;
  font-size: 15px;
  padding: 3% 4%;
  justify-content: center;
  text-align: center;
  width: 40%;
  background-color: #cf551c;
  color: #ffffff;
  border: 0px;
  border-radius: 2px;
  margin-bottom: 22%;
}
.leave {
  padding-left: 6%;
  padding-right: 6%;
  padding-bottom: 5%;
  padding-top: 2%;
  width: auto;
  background-color: #f5f8fd;
}
</style>
