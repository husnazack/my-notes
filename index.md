# Interactive Counter Demo

Click the button to increase the counter.

<div id="counter" style="font-size: 32px; margin-bottom: 10px;">
0
</div>

<button onclick="add()" style="padding: 10px 20px; font-size: 16px;">
+ Add
</button>

<script>
function add() {
  let el = document.getElementById("counter");
  el.innerText = parseInt(el.innerText) + 1;
}
</script>
