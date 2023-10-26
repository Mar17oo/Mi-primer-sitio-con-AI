document.addEventListener("DOMContentLoaded", function() {
  fetch("enlaces.json")
    .then((response) => response.json())
    .then((data) => {
      const ul = document.querySelector("ul");

      data.enlaces.forEach((enlace) => {
        const li = document.createElement("li");
        const a = document.createElement("a");
        a.href = enlace.url;
        a.textContent = enlace.nombre;
        li.appendChild(a);
        ul.appendChild(li);
      });
    });
});
