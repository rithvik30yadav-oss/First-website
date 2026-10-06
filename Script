const toast = document.getElementById("toast");

function showDemoMessage() {
  toast.classList.add("show");
  window.setTimeout(() => toast.classList.remove("show"), 3500);
}

document.querySelectorAll("#reserveTop, #reserveHero, #reserveBottom")
  .forEach(button => button.addEventListener("click", showDemoMessage));
