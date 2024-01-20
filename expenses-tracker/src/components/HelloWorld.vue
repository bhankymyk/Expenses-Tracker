<template>

<div class="container-fluid">
  <div class="row">
    <div class="hello">
      <!-- <h1>{{ msg }}</h1> -->
      <h1>Manage Spending  <br>Money Effectively <br>and Efficiency</h1>
      <h3>Best way to save your money</h3>
      <h5>With our easy to use platform you can track your income and expenses, set budget and plan for your <br>
        funancial future. Say goodbye to financial stress and yes to financial freedom </h5>
        <button type="button" class="btn  btn-success mt-2">Click here to explore</button>
      </div>
    </div>
    <div class="row bg-light mt-5">
      <div class="col-md-3 midlogo"><h6>Supported by international finance manager</h6></div>
      <div class="col-md-3"><img src="../assets/Paypal-logo.png" class="img-fluid"  alt="pay"></div>
      <div class="col-md-3"><img src="../assets/VISA-logo.png"  class="img-fluid" alt="pay"></div>
      <div class="col-md-3"><img src="../assets/images (1).png"  class="img-fluid" alt=""></div>
    </div>

      <div class="row mt-5 midText">
        <div class="col">
          <h2>Together with AI assistant who manage <br> your finances optimally</h2>
          <h5>Expensely uses AI technology that can help you manage your finances </h5>
        </div>
      </div>

      <div class="row mt-5 bg-light">
        <div class="col-md-4 midBox">
          <div class="col-md-3"><img src="../assets/Paypal-logo.png" class="img-fluid"  alt="pay"></div>
          <h3>Multilevel security</h3>
          <h6>Protect your financial status with features like <br> multi-factor aunthetification and
          granular <br> employee permision </h6>
        </div>
        <div class="col-md-4 midBox  ">
          <div class="col-md-3"><img src="../assets/Paypal-logo.png" class="img-fluid"  alt="pay"></div>
          <h3>Trusted Experience</h3>
          <h6>Apply in minutes and recieved account<br> Approval within hours, This access all the <br> 
          cash management essentials in one digital <br>platform</h6>
        </div>
        <div class="col-md-4 midBox">
          <div class="col-md-3"><img src="../assets/Paypal-logo.png" class="img-fluid"  alt="pay"></div>
          <h3>Structured Outreach</h3>
          <h6>Expensely offers around clock support to<br> answer most pressing question and <br> propel your business forward </h6>
        </div>
      </div>


</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped>
h1 {
  font-size: 70px;
  line-height: 90px;
  padding: 10px;
}
h6 {
  white-space: nowrap;
}
.midlogo{
  margin-top: 80px;
}
.midText, h2 {
  text-align: center;
  color: black;
}
.midBox{
  box-shadow:rgba(5, 5, 5, 0.50) 5px 5px 8px;
  padding: 20px;
}
.midBox h6 {
  /* box-shadow:rgba(5, 5, 5, 0.50) 5px 5px 8px; */
  padding: 20px;

}
</style>
