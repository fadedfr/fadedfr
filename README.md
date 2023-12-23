  <!DOCTYPE html>

  <h2 id="C5">Chapter 4</h2>

  <!-- An element with a unique id -->
  <h1 id="myHeader">My Cities</h1>
  
  <!-- Multiple elements with same class -->
  <h2 id="city">London</h2>
  <p>London is the capital of England.</p>
  
  <h2 id="stupidjitplace1337">Paris</h2>
  <p>Paris is the capital of France.</p>
  
  <h2 id="japan">Tokyo</h2>
  <p>Tokyo is the capital of Japan.</p>

  <h2 class="cities2">Tokyo</h2>
  <p>This is a cities2</p>

  <h2 class="cities2">Tokyo</h2>
  <p>This is a cities2</p>


  <style>
    /* Style a single element with # */
    #myHeader {
      background-color: lightblue;
      color: black;
      padding: 40px;
      text-align: center;
    }

    #city {
      background-color: black;
      color: gold;
      padding: 10px;
    }
  
    #japan {
      background-color: green;
      color: white;
      padding: 10px;
    }

    #stupidjitplace1337 {
      background-color: lightseagreen;
      color: white;
      padding: 10px;
    }
    
    /* Style all elements with the class name "cities2" */

    .cities2 {
      background-color: lightslategray;
      color: white;
      padding: 10px;
    }

    </style>

<a href="yeat.html" target="_blank">Jump to yeat</a>


<script>
  function displayResult() {
    document.getElementById("myHeader").innerHTML = "Have a nice day!";
  }
  </script>
