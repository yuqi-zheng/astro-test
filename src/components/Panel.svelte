<script>
  import Card from './Card.svelte';
</script>

<div>
  <h2><u>Everything</u> you need with no big unfront cost</h2>
  <section class="cards">
    <Card header='Design.' text= 'No templates - we custom design your website from the ground up based on your needs.
    You give us as much detail as you want and we will do the rest.' icon = 'palette.svg' second = 'Take a look at our gallery!'/>
    <Card header='Develop.' text= 'We hand-code each line to maximise performance. Lambda websites are optimised for
    minimal loading times - which will bump up your ranking in Google searches.' icon = 'keyboard.svg' second = 'Site speed and Google rankings'/>
    <Card header='Maintain.' text= 'We take care of any changes you want to make, and perform routine maintenance to keep your website
    running optimally.' icon = "home_repair_service.svg" second = 'Small-business-friendly pricing'/>
  </section>
</div>

<style>
  
  h2 {
    font-family: 'Outfit', sans-serif;
    font-size: 32px;
    font-weight: 400;
    margin-bottom: 24px;
  }
.cards {
  box-sizing: border-box;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 24px;
  gap: 10px;
  width: 100%;
  background-color: #5043BA;
  border: 2px solid #6756DE;
  box-shadow: 0px 0px 24px 4px rgba(48, 52, 56, 0.25);
  border-radius: 10px;
}

</style>

