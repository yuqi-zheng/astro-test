<script>

</script>


<div class="centered">
 
  <section class="cards">
       
    <article class="card">
      <div class="container">
        <h4>Design.</h4>
        <p>No templates - we custom design your website from the ground up based on your needs.
        You give us as much detail as you want and we will do the rest</p>
      </div>
    </article><!-- /card-one -->

    <article class="card">
      <div class="container">
      <h4>Develop.</h4>
      <p>We hand-code each line to maximise performance. Lambda websites are built in Svelte for optimal
        pagespeed - which will bump up your ranking in Google searches.</p>
      </div>
      </article><!-- /card-two -->

    <article class="card">
      <div class="container">
      <h4>Maintain.</h4>
      <p>We take care of any changes you want to make, and perform routine maintenance to keep your website
        running optimally.</p>
      </div>
      </article>

</section>
</div>

<head>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Outfit">
<style>

.card {
  /* Add shadows to create the "card" effect */
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
    gap: 18px;
    
  
}

/* On mouse-over, add a deeper shadow */
.card:hover {
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.container{
  flex-direction: column;
  align-items: flex-start;
  padding: 0px;
  width: 472px;
  height: 198px;
  overflow: hidden;
  display: inline;
}

* {
  margin: 0px;
}



p {
  font-family: "Outfit";
  font-size: 24px;

} 

h4 {
  font-family: "Outfit";
  font-size: 48px;

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

</style>
</head>

