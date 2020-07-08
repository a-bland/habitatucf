+++
widget = "blank"
headless = true
weight = 20
+++
<html>
  <head>
    <style>
      /* Make four columns of equal size */
      .column {
        float: left;
        width: 25%;
        }
      .body {
      width: 100%;
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
    <div id="info">
     <div class="column">
      <h1>Our Meetings</h1>
      <p>Check back soonor stay tuned to our social media to find out our meeting plans for the Fall 2020 semester.</p>
     </div>
     <div class="column">
      <h1>We Volunteer</h1>
      <p>This is a volunteering club. Builds and restore events are usually held on weekends. Sign up at our meetings.</p>
     </div>
     <div class="column">
      <h1>Your Experience</h1>
      <p>You don’t need to have any previous construction experience to volunteer. We all learn as we go!</p>
     </div>
     <div class="column">
      <h1>Socials & Events</h1>
      <p>We have social events and partial proceeds fundraisers throughout the year; we encourage you to join us.</p>
     </div>
    </div>
	</body>    
</html>
