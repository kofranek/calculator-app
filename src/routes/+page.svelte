<main>
 <div class="calculator">
  <div class="results">
    <div class="digits">
      <div class="numbers">
        <button> C </button> 
        <button> 1 </button> 
        <button> 2 </button> 
        <button> 3 </button> 
        <button> 4 </button> 
        <button> 5 </button> 
        <button> 6 </button> 
        <button> 7 </button> 
        <button> 8 </button> 
        <button> 9 </button> 
        <button> 0 </button> 
        <button> . </button> 
      </div>
      <div class="operations">
        <button> / </button>
        <button> x </button>
        <button> + </button>
        <button> - </button>
        <button> = </button>
      </div>
    </div>
  </div>
 </div>
</main>
 
<style>
  main {
    width: 100vw;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .calculator {
    background-color: rgb(28, 28, 28);
    width: 240px;
    padding: 15px;
    border-radius: 7px;
  }
  .digits {
    display: flex;
  }
  .operations {
    display: flex;
    flex-direction: column;
  }
  .numbers {
    display: flex;
    flex-wrap: wrap;
    width: 200px;
  }
  .btn {
    width: 50px;
    height: 50px;
    border-radius: 100px;
    background-color: rgb(114, 113, 113);
    font-size: 20px;
    font-weight: bold;
    color: white;
    margin: 5px;
    border: none;
  }
  .btn-lg {
    width: 110px;
  }
  .btn-orange {
    background-color: orange;
  }
  .btn-silver {
    background-color: silver;
  }
  .btn-xlg {
    width: 170px;
  }
  .results {
    height: 60px;
    color: white;
    font-size: 50px;
    display: flex;
    flex-direction: row-reverse;
    margin-right: 10px;
  }
</style>

