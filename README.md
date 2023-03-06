<html>
  <head>
    <style>
      body {
  font-family: sans-serif;
  margin:0;
  min-height:300vh;
  margin-bottom:100px;
}
#welcome-section{
  width:100%;
  height:100vh;
  margin:0 auto;
  background:#e0e0eb;
}
#welcome-text{
  padding-top:50vh;
  text-align:center;
  position:relative;
  animation-name:slide;
  animation-duration:8s;
}
@keyframes slide{
  0%{ 
  top:0px;}
  25%{ 
  top:100px;}
  75%{
    top:-100px;
  }
  100%{ 
  top:0px;}
}
#welcome-text h1{
  font-size:40px;
}
@media only screen and (max-width:600px) {
  #welcome-text h1 {font-size:30px;}
}
.nav-bar{
  background-color: #e6fff2;
  overflow:hidden;
  width:100%;
  position:fixed;
  z-index:1;
}
.nav-container {
  float:right;
  padding-top:20px;
  padding-bottom:8px;
  padding-right:10px;
}
.nav-bar a {
  text-decoration:none;
  padding-right:30px;
  text-align:center;
  color:black;
}
#projects{
  margin: 0 auto;
  width:60%;
  margin-top:50px;
}
#projects-title {
  text-align:center;
}
#project-tile{
  width:100%;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  border-radius: 5px;
  margin-top:50px;
  float:center;
  margin-left:0px;
}
#project-img{
  border-radius:5px 5px 0 0;
  margin:0px;
}
#project-tile:hover{
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}
.tiletext{
  padding: 2px 16px;
  margin:0px;
  text-align:center;
  background:white;
}
.tile-container{
  display:grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  grid-template-rows: 1fr;
  grid-gap:40px;
  background:white;
}
    </style>
  </head>
  <body>
  <div class="nav-bar">
    <div class="nav-container">
      <a class="active" href="#welcome-section">Home</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </div>
  </div>
  <section id="welcome-section">
    <div id="welcome-text">
      <h1> Welcome to my Portfolio </h1>
      <h4> a beginner web developer </h4>
      <p> check out my githup <a id="profile-link" href="https://www.google.com" target="_blank">here</a></p>
    </div>
  </section>
  <section id="projects">
    <h2 id="projects-title"> Here are a few of my projects </h2>
    <div class="tile-container">
      <div id="project-tile">
        <img src="https://picsum.photos/seed/picsum/200/250" alt="tile1" id="project-img" style="width:100%">
        <div class="tiletext">
          <p>Random project 1</p>
        </div>
      </div>
      <div id="project-tile">
        <img src="https://picsum.photos/id/1019/200/250" alt="tile1" id="project-img" style="width:100%">
        <div class="tiletext">
          <p>random project 2</p>
        </div>
      </div>
      <div id="project-tile">
        <img src="https://picsum.photos/id/237/200/250" alt="tile1" id="project-img" style="width:100%">
        <div class="tiletext">
          <p>random project 3</p>
        </div>
      </div>
      <div id="project-tile">
        <img src="https://picsum.photos/id/1025/200/250" alt="tile1" id="project-img" style="width:100%">
        <div class="tiletext">
          <p>random project 4</p>
        </div>
      </div>
    </div>
  </section>
</body>
  </html>
