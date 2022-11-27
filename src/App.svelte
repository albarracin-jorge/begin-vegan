<script>
  import Header from './lib/Header.svelte';
  import First from './lib/First.svelte';
  import Second from './lib/Second.svelte'
</script>

<main>
  <Header/>
  <First/>
  <Second/>

  <footer>
    <h2>BEGIN VEGAN</h2>
    <h3>MADE WHIT LOVE</h3>
  </footer>
</main>

<style>
  main{
    display: flex;
    flex-direction: column;
  }

  footer{
    height: 10vh;

    border-top: solid 5px #6bd9e8;
    text-align: center;
    color: black;
  }

  h2{
    margin-top: 3vh;
  }

</style>
