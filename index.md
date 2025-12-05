# My Notes

<style>
.tab-container {
  display: flex;
  gap: 10px;
  margin-bottom: 20px;
}
.tab-button {
  padding: 10px 18px;
  border-radius: 6px;
  background: #f0f0f0;
  cursor: pointer;
  border: 1px solid #ccc;
}
.tab-button:hover {
  background: #e2e2e2;
}
.tab-content {
  display: none;
  padding: 15px;
  border: 1px solid #ddd;
  border-radius: 6px;
}
</style>

<a href="aboutcs770">About CS770</a>

<div class="tab-container">
  <div class="tab-button" onclick="openTab('ICT701')">ICT701</div>
  <div class="tab-button" onclick="openTab('ICT702')">ICT702</div>
  <div class="tab-button" onclick="openTab('ICT703')">ICT703</div>
  <div class="tab-button" onclick="openTab('ICT707')">ICT707</div>
  <div class="tab-button" onclick="openTab('ICT709')">ICT709</div>
</div>

<!-- ICT701 -->
<div id="ICT701" class="tab-content">
  <h2>ICT701</h2>
  <ul>
    <li><a href="ict701/chapter1.md">SL: Chapter 1</a></li>
    <li><a href="ict701/chapter2.md">SL: Chapter 2</a></li>
    <li><a href="ict701/chapter3.md">SL: Chapter 3</a></li>
  </ul>
</div>

<!-- ICT702 -->
<div id="ICT702" class="tab-content">
  <h2>ICT702</h2>
  <ul>
    <li><a href="ict702/chapter1.md">SL: Chapter 1</a></li>
    <li><a href="ict702/chapter2.md">SL: Chapter 2</a></li>
  </ul>
</div>

<!-- ICT703 -->
<div id="ICT703" class="tab-content">
  <h2>ICT703</h2>
  <ul>
    <li><a href="ict703/chapter1.md">SL: Chapter 1</a></li>
  </ul>
</div>

<!-- ICT707 -->
<div id="ICT707" class="tab-content">
  <h2>ICT707</h2>
  <ul>
    <li><a href="ict707/chapter1.md">SL: Chapter 1</a></li>
  </ul>
</div>

<!-- ICT709 -->
<div id="ICT709" class="tab-content">
  <h2>ICT709</h2>
  <ul>
    <li><a href="ict709/chapter1.md">SL: Chapter 1</a></li>
    <li><a href="ict709/chapter2.md">SL: Chapter 2</a></li>
  </ul>
</div>

<script>
function openTab(tabId) {
  const contents = document.querySelectorAll('.tab-content');
  contents.forEach(c => c.style.display = 'none');
  document.getElementById(tabId).style.display = 'block';
}
</script>

<p><i>Select a tab and choose a chapter.</i></p>
