<script>
</script>

<section class="cards">
  <article class="card">
    <div class="container">
    <div class="header">
      <h4>Design.</h4>
      <img src="palette.svg" alt = "palette" style="width:43.98px;height:43.98px;">
    </div>
    <div class="text">
      <p class="p1">No templates - we custom design your website from the ground up based on your needs.
      You give us as much detail as you want and we will do the rest.</p>
    </div>
  </div>
  <div class="bottom">
    <p class="p2">Take a look at our gallery!</p>
    <img src="arrow.svg" alt = "arrow" style="left: 3.96%; right: 3.96%; top: 29.29%; bottom: 29.29%;">
  </div>
  </article><!-- /card-one -->

  <article class="card">
    <div class="container">
    <div class="header">
      <h4>Develop.</h4>
      <img src="keyboard.svg" alt = "keyboard" style="width:43.98px;height:43.98px;">
    </div>
    <div class="text">
    <p class="p1">We hand-code each line to maximise performance. Lambda websites are built in Svelte for optimal
      pagespeed - which will bump up your ranking in Google searches.</p>
    </div>
  </div>
  <div class="bottom">
    <p class="p2">Site speed and Google rankings</p>
    <img src="arrow.svg" alt = "arrow" style="left: 3.96%; right: 3.96%; top: 29.29%; bottom: 29.29%;">
  </div>
  </article>

  <article class="card">
    <div class="container">
    <div class="header">
      <h4>Maintain.</h4>
      <img src="home_repair_service.svg" alt = "home_repair" style="width:43.98px;height:43.98px;">
    </div>
    <div class="text">
    <p class="p1">We take care of any changes you want to make, and perform routine maintenance to keep your website
      running optimally.</p>
    </div>
  </div>
  <div class="bottom">
    <p class="p2">Small-business-friendly pricing</p>
    <img src="arrow.svg" alt = "arrow" style="left: 3.96%; right: 3.96%; top: 29.29%; bottom: 29.29%;">
  </div>
  </article>
</section>

<head>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Outfit">
<style>
  
* {
  margin: 0px;
}

.card {
  /* Add shadows to create the "card" effect */
  gap: 0px;
  box-sizing: border-box;
  box-shadow: 0px 0px 6px 2px rgba(48, 52, 56, 0.25);
  transition: 0.3s;
  width: 544px;
  height: 396px;
  background: #F7F5F3;
  border: 3px solid #9BA6AE;
  /* Low Shadow */
  border-radius: 10px;
  padding: 30px 36px 36px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
}

/* On mouse-over, add a deeper shadow */
.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.container {
  display: flex;
  gap: 18px;
  flex-direction: column;
  align-items: flex-start;
  padding: 0px;
  width: 472px;
  height: 198px;
  overflow: hidden;
}


.p1 {
  font-family: "Outfit";
  font-style: normal;
  font-size: 24px;
  font-weight: 400;
  line-height: 30px;
} 

.p2 {
  font-family: "Outfit";
  font-weight: 600;
  font-size: 24px;
  line-height: 30px;
}

h4 {
  font-family: "Outfit";
  font-size: 48px;
  font-weight: 500;
  line-height: 60px;
} 

.text {
  width: 472px;
  height: 120px;
}

.header {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 0px;
  gap: 10px;
  width: 472px;
  height: 60px;
  /* Inside auto layout */
  flex: none;
  order: 0;
  flex-grow: 0;
}

.cards {
  box-sizing: border-box;
/* Auto layout */
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: flex-start;
  padding: 36px;
  gap: 10px;
  width: 1776px;
  height: 468px;

  /* Primary/700 */

  background: #5043BA;
  /* Primary/600 */

  border: 2px solid #6756DE;
  /* High Shadow */

  box-shadow: 0px 0px 24px 4px rgba(48, 52, 56, 0.25);
  border-radius: 15px;

  /* Inside auto layout */
  flex: none;
  order: 1;
  flex-grow: 0;
}

.bottom {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  align-items: center;
  padding: 0px;
  gap: 18px;
  width: 472px;
  height: 47.8px;
}

</style>
</head>

