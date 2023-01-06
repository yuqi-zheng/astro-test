<script>
  import Card from './Card.svelte';
</script>

<section class="cards">
  <Card header='Design.' text= 'No templates - we custom design your website from the ground up based on your needs.
  You give us as much detail as you want and we will do the rest.' icon = 'palette.svg' second = 'Take a look at our gallery!' arrow = 'arrow.svg'/>
  <Card header='Develop.' text= 'We hand-code each line to maximise performance. Lambda websites are built in Svelte for optimal
  pagespeed - which will bump up your ranking in Google searches.' icon = 'keyboard.svg' second = 'Site speed and Google rankings' arrow = 'arrow.svg'/>
  <Card header='Maintain.' text= 'We take care of any changes you want to make, and perform routine maintenance to keep your website
  running optimally.' icon = "home_repair_service.svg" second = 'Small-business-friendly pricing' arrow = 'arrow.svg'/>
</section>

<head>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Outfit">
<style>
  
* {
  margin: 0px;
  padding: 0px;
}


.container {
  display: flex;
  gap: 18px;
  flex-direction: column;
  align-items: flex-start;
  padding: 0px;
  height: 198px;
  overflow: hidden;
}

h4 {
  font-family: "Outfit";
  font-size: 24px;
  font-weight: 500;
  line-height: 60px;
} 

.text {
  font-family: "Outfit";
  font-style: normal;
  font-size: 16px;
  font-weight: 400;
  line-height: 30px;
  color: #161718;
}

.header {
  width: 100%;
  height: 60px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 0px;
}

.cards {
  box-sizing: border-box;
/* Auto layout */
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 36px;
  gap: 10px;
  width: 100%;
  height: 468px;
  background: #5043BA;
  border: 2px solid #6756DE;
  box-shadow: 0px 0px 24px 4px rgba(48, 52, 56, 0.25);
  border-radius: 15px;
}

.bottom {
  font-family: "Outfit";
  display: flex;
  justify-content: flex-end;
  align-items: center;
  font-weight: 600;
  font-size: 16px;
  line-height: 30px;
  gap: 18px;
  align-self: stretch;
}

</style>
</head>

