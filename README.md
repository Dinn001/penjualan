<h1 align="center">
  <span class="rainbow-text">DINNS STORE</span>
</h1>

<style>
@keyframes slideRainbow {
  0% { transform: translateX(0); }
  100% { transform: translateX(100%); }
}

.rainbow-text {
  display: inline-block;
  font-weight: bold;
  font-size: 2.5em;
  background-image: linear-gradient(90deg, red, orange, yellow, green, cyan, blue, violet, red);
  background-size: 400%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: slideText 6s linear infinite;
  white-space: nowrap;
}

@keyframes slideText {
  0% { background-position: 0% }
  100% { background-position: 400% }
}
</style>
