+++
widget = "blank"
headless = false
weight = 4
+++
<html>
  <head>
    <style>
      /* Style the buttons that are used to open and close the accordion panel */
      .accordion {
        background-color: #eee;
        color: #444;
        cursor: pointer;
        padding: 18px;
        width: 100%;
        text-align: left;
        border: none;
        outline: none;
        transition: 0.4s;
      }

      /* Add a background color to the button if it is clicked on (add the .active class with JS), and when you move the mouse over it (hover) */
      .active, .accordion:hover {
        background-color: #ccc;
      }

      /* Style the accordion panel. Note: hidden by default */
      .panel {
        padding: 0 18px;
        background-color: white;
        display: none;
        overflow: hidden;
      }
    </style>
  </head>
<body>
  <h1>Frequently Asked Questions</h1>
  <button class="accordion">Meetings: When and Where?</button>
    <div class="panel">
      <p>Check back soon to find out our meeting plans for the Fall 2020 semester.</p>
  </div>
  <button class="accordion">How often do we host builds?</button>
    <div class="panel">
      <p>We will typically have about two a month. Come to our meetings or join our Groupme for more information and to sign up to join.</p>
    </div>
  <button class="accordion">Are builds always on Saturdays?</button>
    <div class="panel">
      <p>No; there are currently weekday builds available, though all builds have a limited number of spots due to social distancing requirements.</p>
    </div>
  
  <script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var panel = this.nextElementSibling;
    if (panel.style.display === "block") {
      panel.style.display = "none";
    } else {
      panel.style.display = "block";
    }
  });
}
</script>
</body>    
</html>
