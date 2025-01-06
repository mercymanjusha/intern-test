<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Advanced Software Solutions</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header -->
  <header>
    <div class="coone">
      <div class="logo"><b>LOGO</b></div>
      <nav>
        <ul>
          <li><a href="home.html">Home</a></li>
          <li><a href="about us.html">About Us</a></li>
          <li><a href="services.html">Services</a></li>
          <li><a href="news.html">News</a></li>
          <li><a href="webinar.html">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="container">
      <h1>Advanced software, advanced <br>research for <span>SIMPLE </span>life</h1>
      <h3>We harness the latest technologies to develop cutting-edge<br> digital solutions for modern business requirements.</h3>
      <div class="cta">
        <!DOCTYPE html>
<html>

        <a href="#contact" class="button">Get a Quote</a>
        <div class="metrics">
          <div class="metric">
            <h1>1234</h1>
            <p>Happy Clients</p>
          </div>
          <div class="metric">
            <h1>1234</h1>
            <p>Projects Completed</p>
          </div>
        </div>
      </div>
    </div><section id="home" class="hero">
      <div class="container">
        <!-- Floating Profile Card -->
        <div class="profile-card">
          <img src="pr13.jpg" alt="John Rickey">
          <div class="profile-details">
            <h3>John Rickey</h3>
            <p>Lorem ipsum in simply dummy.</p>
            <img src="bell.png">
            <img class="img" src="bulb.png">
          </div>
        </div>
        <section id="about" class="about">
          <div class="container">
            <h1>
              
             <span style="color:black">About</span> <span style="color:skyblue">Lorem</span> </h1>
            
              <p>At AFQ Tech, we believe in a systematic approach for any project,be it's complex or simple. We are a group of individuals<br> with a various set of skill set varies  from Digital Marketing to IoT/Robotics solutions.
      We have our dedicated team for your<br> project which uses  various methods, such as agile Scrum&agile Kanban.We  ensure top-notch quality, on-time delivery,<br> and agility for all our projects.</p>
            
            <div class="about-grid">
              <div class="card">
                <img src="pr1.png" alt="Technology Icon">
                <h3>Cutting Edge Technology</h3>
                <p>Take the advantage of the cutting-edge<br> solutions to increase your Return of<br>investment on it .</p>
              </div>
              <div class="card">
                <img src="pr2.png" alt="Compatibility Icon">
                <h3>Cross Device Compatibility</h3>
                <p>Multi device compatibility ensure that<br>creating viewing and providing quick and<br> easy.</p>
              </div>
              <div class="card">
                <img src="pr3.png" alt="Tailored Solutions Icon">
                <h3>Tailor Made Development</h3>
                <p>Scalable and dynamic systems with the<br>ever changing trends to meet your dynamic<br>business needs.</p>
              </div>
            </div>
          </div>
        </section>
      
        <!-- Footer -->
        <footer>
          <div class="container">
            <p>&copy; 2025 Advanced Software Solutions. All rights reserved.</p>
          </div>
        </footer>
        
    
        
    
        
    </section>
   /* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
}

/* Header */
header {
  background: #111;
  color: #fff;
  padding: 1rem 0;
}

header .coone {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header ul {
  list-style: none;
  display: flex;
  gap: 1rem;
}

header a {
  color: #fff;
  text-decoration: none;
  padding: 0.5rem 1rem;
}

header a:hover {
  background: #333;
  border-radius: 5px;
}

/* Hero Section */
.hero {
  background:black;
  color: #fff;
  padding: 5rem 1rem;
  text-align: center;
}.profile-card {
  width: 300px; /* Adjust width */
  height: 120px; /* Adjust height */
  background-color: #1d1d2b; /* Same as card background */
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 10px;
  gap: 10px;
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
  color: #fff;
  font-family: 'Arial', sans-serif;
}


.profile-card img {
  width: 60px; /* Size for the profile image */
  height: 60px;
  border-radius: 50%;
}

.profile-card .info {
  display: flex;
  flex-direction: column;
  gap: 5px;
}

.profile-card .info h4 {
  font-size: 16px; /* Adjust font size */
  margin: 0;
}

.profile-card .info p {
  font-size: 14px; /* Adjust secondary text size */
  margin: 0;
  color: #bbb;
}



.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.hero span {
  color: #007bff;
}

.hero p {
  margin-bottom: 2rem;
}

.hero .btn {
  background: #007bff;
  color: #fff;
  padding: 0.5rem 1rem;
  border: none;
  border-radius: 5px;
  text-decoration: none;
}

.hero .metrics {
  display: flex;
  justify-content: center;
  gap: 2rem;
  margin-top: 2rem;
}

.hero .metric h1 {
  font-size: 2rem;
  margin-bottom: 0.5rem;
}

/* About Section */
.about {
  background: whitesmoke;
  padding: 2rem 1rem;
}

.about .container {
  max-width: 1200px;
  margin: 0 auto;
  text-align: center;
}

.about h1 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.about-grid {
  display: flex;
  gap: 2rem;
  justify-content: center;
  margin-top: 2rem;
}

.about .card {
  background: #fff;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  padding: 1rem;
  text-align: center;
}

.about .card img {
  max-width: 100px;
  margin-bottom: 1rem;
}

.about .card h3 {
  margin-bottom: 0.5rem;
}

.about .card p {
  color: #666;
}

/* Footer */
footer {
  background: #111;
  color: #fff;
  text-align: center;
  padding: 1rem 0;
}
.img{
  position: absolute;
  top:200px;
  right:100px;
  transform:rotate(-70deg)
  skewX(-20deg);
}
h2{
  text-align: center;
  color:black;
}
h2 span{
  color:skyblue;

}
p{
  color:black;
  align-content: center;
}

         
      
  

  
