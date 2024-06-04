# Demo

Some description!

<html>
<body style="background-color:rgb(71, 12, 209);">
<h1 style="font-size: 120px; text-align: center;"> EMOJI SITEs </h1>
<h1 style="font-size: 120px; text-align: center;"> EMOJI SITE </h1>


<!-- LOOP CONSTRUCT COMBINED IN TABLE -->
<!-- FOR IN LOOP CONSTRUCT -->
<p style="font-size: 50px; font-style: italic;"> <h2>FANCY EMOJI</h2></p>
<table>
    <tr>
        <td>
            
<p id = "output" > </p>
   <script>
      let output = document.getElementById("output");
      let emoji = { Smile:"&#x1F601" , Wink:"&#x1F609" , Angry:"&#x1F621", Clown:"&#x1F921" }
      for (e in emoji) {
         output.innerHTML += e + "     ---->    " + emoji[e] + "<br>";
      }
    </script>
</td>
<!-- FOR OF LOOP CONSTRUCT -->
