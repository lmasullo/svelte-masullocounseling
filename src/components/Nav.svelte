<script>
  // Function to show and hide hamburger menu links
  function fnMenu() {
    var x = document.getElementById("myLinks");
    if (x.style.display === "block") {
      x.style.display = "none";
    } else {
      x.style.display = "block";
    }
  }
</script>

<style>
</style>

<header>
  <div>
    <img src="/images/logo_small.png" alt="Masullo Counseling Logo" />
    <span>Masullo Counseling</span>
  </div>

  <nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#forms">Client Forms</a>
    <a href="#insurance">Insurance</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Hamburger menu icon -->
  <img
    id="hamburger"
    src="images/hamburger_black.png"
    alt="Menu"
    on:click={fnMenu} />
</header>
