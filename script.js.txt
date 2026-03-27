const toggle = document.getElementById("toggleDark");

toggle.addEventListener("click", () => {
document.body.classList.toggle("light");
});

document.getElementById("form").addEventListener("submit", e => {
e.preventDefault();
alert("Mensaje enviado 🚀");
});
