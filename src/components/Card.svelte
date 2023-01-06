<script>
    export let text;
    export let icon;
    export let header;
    export let arrow;
    export let second;

</script>

<article class="card">
    <div class="container">
    <div class="header">
      <h4>{header}</h4>
      <img src={icon} alt = "palette" style="width:43.98px;height:43.98px;">
    </div>
    <div class="text">
      <p>{text}</p>
    </div>
  </div>
  <div class="bottom">
    <p>{second}</p>
    <img src={arrow} alt = "arrow" style="left: 3.96%; right: 3.96%; top: 29.29%; bottom: 29.29%;">
  </div>
</article>


<style>
  .card {
    /* Add shadows to create the "card" effect */
    box-sizing: border-box;
    box-shadow: 0px 0px 6px 2px rgba(48, 52, 56, 0.25);
    width: 32%;
    height: 90%;
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
</style>

