# My Website

This is the header of my website.

<!-- Hamburger menu -->
<button onclick="myFunction()" class="dropbtn">Menu</button>
<div id="myDropdown" class="dropdown-content">
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</div>

<!-- Script to toggle the hamburger menu -->
<script>
function myFunction() {
  document.getElementById("myDropdown").classList.toggle("show");
}

// Close the dropdown if the user clicks outside of it
window.onclick = function(event) {
  if (!event.target.matches('.dropbtn')) {
    var dropdowns = document.getElementsByClassName("dropdown-content");
    var i;
    for (i = 0; i < dropdowns.length; i++) {
      var openDropdown = dropdowns[i];
      if (openDropdown.classList.contains('show')) {
        openDropdown.classList.remove('show');
      }
    }
  }
}
</script>

## Body

This is the body of my website. Here is where I will put the main content of my website.

## Footer

This is the footer of my website. Here is where I will put information about myself or my business, as well as any legal notices or disclaimers.
