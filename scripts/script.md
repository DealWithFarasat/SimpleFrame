       ```
             Scroll
window.addEventListener("scroll", function () {
    let navbar = document.querySelector("nav");
         if (window.scrollY > 50) {
       navbar.style.backgroundColor = "rgba(24, 24, 24, 0.9)"; // Slightly transparent when scrolling
         } else {
        navbar.style.backgroundColor = "rgb(24, 24, 24)"; // Solid at the top
       }
  });
  ```
                  