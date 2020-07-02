+++
widget = "blank"
headless = true
weight = 4
+++
<html>
  <head>
    <style>
      /* Make two columns of equal size */
      .column {
        float: left;
        width: 50%;
        }
      .body {
      width: 100%;
      }
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
      /* Add a background color to the button if it is clicked on (add the .active class with JS), and when you move the 
      mouse over it (hover) */
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
      /* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
      @media screen and (max-width: 600px) {
      .column {
        width: 100%;
  }
} 
    </style>
  </head>
	<body>
	  <h1>Frequently Asked Questions</h1>
	  <div class = "column">
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
     <button class="accordion">What happens if I can't attend a meeting?</button>
		<div class="panel">
		  <p>We keep track of attendance in order to reward members who are actively participating, but attendance is not necessary. There is not a mandatory attendance requirement in order to maintain membership. All of the important dates and PowerPoints will be posted on our social media and on our website. Those who come to meetings have priority when it comes to signing up for builds, but if there are extra spots available, we will post it on the Facebook page. Bi-weekly emails will be sent with all the important information you need</p>
		</div>
    <button class="accordion">How can I become an officer?</button>
		<div class="panel">
		  <p>Every Spring semester, we will hold officer elections. There are eligibility requirements in order to run for your preferred officer position. If you’re interested in becoming an officer or have any specific questions about positions or requirements, please email president@habitatucf.com.</p>
	  </div>
	  <div class = "column">
		<button class="accordion">What is Habitat for Humanity?</button>
		<div class="panel">
		  <p>HFH is a non-profit international organization that strives to alleviate substandard housing for families in need. To accomplish this mission, affiliates around the world provide stable and affordable homes. For more information, visit <a href="www.habitat.org" target="blank" >habitat.org.</a></p>
	  </div>
	  <button class="accordion">What are the dues and what can they help pay for?</button>
		<div class="panel">
		  <p>Membership dues are $25 for one semester or $35 for the whole year. With membership dues, you get a Habitat UCF t-shirt and the ability to go to builds (yes, that is the one condition to go on builds). Contact our Treasurer if you're interested in joining.</p>
		</div>
	  <button class="accordion">Do I have to fill out an application?</button>
		<div class="panel">
		  <p>No! The only requirement you need to fulfill to be a member is to pay membership dues.</p>
		</div>  
		</div>
    <button class="accordion">Can I get approved hours for a scholarship or program?</button>
		<div class="panel">
		  <p>Yes! As long as we have documented proof of your involvement in our campus chapter, we would be more than happy to approve your service hours.  Please bring the required forms with you during your service.</p>
		</div>
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
