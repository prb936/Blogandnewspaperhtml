wow is that a readme thing for jekyll 
<html>
<head>
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial;
  padding: 20px;
  background: #f1f1f1;
  }
.header {
  padding: 30px;
  font-size: 40px;
  text-align: center;
  background: white;
       }


.leftcolumn {   
  float: left;
  width: 75%;
}


.rightcolumn {
  float: left;
  width: 25%;
  padding-left: 20px;
}

.fakeimg {
  background-color: lightblue;
  width: 100%;
  padding: 20px;
}

/* Add a card effect for articles */
.card {
   background-color: lightyellow;
   padding: 20px;
   margin-top: 20px;
}

/* Clear floats after the columns Without .row:after, 
.row might not properly contain .column elements because 
they are floated  */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
  margin-top: 20px;
}


</style>
</head>
<body>

<div class="header">
  <h2> Pratiking and Pratoshington Blogs</h2>
</div>

<div class="row">
  <div class="leftcolumn">
    <div class="card">
      <h2>Deepfakes: The Rise of AI-Generated Deception and Its Impact on Society</h2>
      <h5> How the machine generated content of yesterday became the winner of today</h5>
      <div class="fakeimg" style="height:200px;">Image</div>
      <p>This technology, powered by deep learning algorithms, has exciting applications in
	  entertainment, education, and accessibility but also raises ethical and legal concerns.
	  Deepfakes have been used for creating CGI effects in movies, realistic training simulations,
	  and even helping individuals with speech impairments.</p>
      
    </div>
    <div class="card">
      <h2>TITLE HEADING</h2>
      <h5>Title description, Sep 2, 2017</h5>
      <div class="fakeimg" style="height:200px;">Image</div>
      <p>Some text..</p>
      <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
    </div>
  </div>
  <div class="rightcolumn">
    <div class="card">
      <h2>About Me</h2>
      <div class="fakeimg" style="height:100px;">
	  </div>
      <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
    </div>
    <div class="card">
      <h3>Popular Post</h3>
      <div class="fakeimg">Image</div><br>
      <div class="fakeimg">Image</div><br>
      <div class="fakeimg">Image</div>
    </div>
    <div class="card">
      <h3>Follow Me</h3>
      <p>Some text..</p>
    </div>
  </div>
</div>

<div class="footer">
  <h2>Copyright:PratikRajBista2025 || All rights reserved ||</h2>
</div>

</body>
</html>
