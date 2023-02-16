<script>
  
</script>

<main>
<h1>Adding two numbers</h1>
<input type="text" name="num1" id="num1" placeholder="Enter first number">
<p>+</p>
<input type="text" name="num2" id="num2" placeholder="Enter second number">
<p>=</p>
<input type="text" name="result" id="result" placeholder="Result">
<br>
<br>
<button on:click={() => {
  const num1 = document.getElementById('num1').value;
  const num2 = document.getElementById('num2').value;
  const result = document.getElementById('result');
  result.value = Number(num1) + Number(num2);
}}>Add</button>
</main>

<style>
 

</style>
