<script>
    import '../styles/global.css'
    
    export let text;
    export let icon;
    export let header;
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
    <img src='arrow.svg' alt = "arrow" style="left: 3.96%; right: 3.96%; top: 29.29%; bottom: 29.29%;">
  </div>
</article>


<style>
  .card {
    box-sizing: border-box;
    box-shadow: 0px 0px 6px 2px rgba(48, 52, 56, 0.25);
    height: 275px;
    width: 32%;
    background-color: #F7F5F3;
    border: 3px solid #9BA6AE;
    border-radius: 10px;
    padding: 18px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    font-family: 'Outfit', sans-serif;
  }

  .container {
    display: flex;
    gap: 18px;
    flex-direction: column;
    align-items: flex-start;
    overflow: hidden;
}

h4 {
  font-size: 32px;
  font-weight: 400;
} 

.text {
  font-size: 18px;
  font-weight: 300;
  color: #161718;
}

.header {
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.bottom {
  display: flex;
  justify-content: flex-end;
  align-items: center;
  font-weight: 500;
  font-size: 16px;
  gap: 18px;
  align-self: stretch;
}

</style>

