<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Pure Bootstrap</title>
   
    <!-- bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-LN+7fdVzj6u52u30Kp6M/trliBMCMKTyK833zpbD+pXdCLuTusPj697FH4R/5mcr" crossorigin="anonymous">
   
    <!-- style sheet -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.13.1/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="C:\Users\User\Desktop\Web dev\bootstrap installation\pure_style.css">

    <!-- google fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap" rel="stylesheet">

   
    
</head>
  <body>
    <section id="title">
      <div class="container-fluid">
        <nav class="navbar navbar-expand-lg">
          <!-- <div class="container-fluid"> -->
            <a class="navbar-brand" href="#">Hasti Tech</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
              <ul class="navbar-nav">
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#">Home</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Features</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Pricing</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link disabled" aria-disabled="true">Disabled</a>
                </li>
              </ul>
            </div>
          <!-- </div> -->
        </nav>
        <div class="row">
          <div class="col-lg-6">
              <h1>Welcome to the Tech World</h1>
              <button type="button" class="btn btn-dark btn-lg Download-button"><i class="bi bi-apple"></i>
                  Download</button>
              <button type="button" class="btn btn-outline-light btn-lg Download-button"><i class="bi bi-google-play"></i> Download</button>
          </div>
          
          <div class="col-lg-6">
              <img class="rotate" src="C:\Users\User\Desktop\Web dev\bootstrap installation\images\iphone6.png" alt="mobile phone">
          </div>
          
        </div>

      </div>
                 
    </section>

     <!-- Features -->

    <section id="features">
      <div class="row">
        <div class="col-lg-4 feature">
          <i class="bi bi-check-circle"></i>
          <h3> Easy to use.</h3>
          <p>So easy to use, even your dog could do it.</p>
        </div>
       
        <div class="col-lg-4 feature">
          <i class="bi bi-bullseye"></i>
          <h3> Elite Clientele</h3>
          <p>We have all the dogs, the greatest dogs.</p>
        </div>
    
        <div class="col-lg-4 feature">
          <i class="bi bi-heart"></i>
          <h3> Guaranteed to work.</h3>
          <p>Find the love of your dog's life or your money back.</p>
        </div>
      </div>
     
  
    </section>

     <!-- Testimonials -->

  <section id="testimonials">

    <h2>I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
    <img class="testimonial-image" src="images/dog-img.jpg" alt="dog-profile">
    <em>Pebbles, New York</em>

    <!-- <h2 class="testimonial-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
    <img class="testimonial-image" src="images/lady-img.jpg" alt="lady-profile">
    <em>Beverly, Illinois</em> -->

  </section>

   <!-- Press -->

   <section id="press">
    <img class="press-logo" src="C:\Users\User\Desktop\Web dev\bootstrap installation\images\TechCrunch.png" alt="tc-logo">
    <img class="press-logo" src="C:\Users\User\Desktop\Web dev\bootstrap installation\images\tnw.png" alt="tnw-logo">
    <img class="press-logo" src="C:\Users\User\Desktop\Web dev\bootstrap installation\images\bizinsider.png" alt="biz-insider-logo">
    <img class="press-logo" src="C:\Users\User\Desktop\Web dev\bootstrap installation\images\mashable.png" alt="mashable-logo">

  </section>


  <!-- Pricing -->

  <section id="pricing">

    <h2>A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>

    <div class="card-deck">

      <div class="row">

        <div class=" priccing-col col-md-4">
          <div class="card">
            <div class="card-header">
              <h3>Chihuahua</h3>
            </div>
            <div class="card-body">
              <h2>Free</h2>
              <p>5 Matches Per Day</p>
              <p>10 Messages Per Day</p>
              <p>Unlimited App Usage</p>
              <button class="Download-button btn btn-lg btn-outline-primary" type="button">Sign Up</button>
            </div>
          </div>
        </div>

        <div class=" priccing-col col-md-4">
          <div class="card">
            <div class="card-header">
              <h3>Labrador</h3>
            </div>
            <div class="card-body">
              <h2>$49 / mo</h2>
              <p>Unlimited Matches</p>
              <p>Unlimited Messages</p>
              <p>Unlimited App Usage</p>
              <button class="Download-button btn btn-lg btn-primary" type="button">Sign Up</button>
            </div>
          </div>
        </div>

        <div class=" priccing-col col-md-4">
          <div class="card">
            <div class="card-header">
              <h3>Mastiff</h3>
            </div>
            <div class="card-body">
              <h2>$99 / mo</h2>
              <p>Pirority Listing</p>
              <p>Unlimited Matches</p>
              <p>Unlimited Messages</p>
              <p>Unlimited App Usage</p>
              <button class="Download-button btn btn-lg btn-primary" type="button">Sign Up</button>
            </div>
          </div>
        </div>
      </div> 
    </div>
    
  </section>

  <!-- Call to Action -->

  <section id="cta">

    <h3>Find the True Love of Your Dog's Life Today.</h3>
    <button class="btn btn-lg btn-primary Download-button" type="button"><i class="bi bi-apple"></i> Download</button>
    <button class="btn btn-lg btn-primary Download-button" type="button"><i class="bi bi-google-play"></i> Download</button>

  </section>


  <!-- Footer -->

  <footer id="footer">

    <i class="bi bi-telephone footer-i"></i>
    <i class="bi bi-whatsapp footer-i"></i>
    <i class="bi bi-envelope footer-i"></i>
    <p>© Copyright TinDog</p>

  </footer>


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/js/bootstrap.bundle.min.js" integrity="sha384-ndDqU0Gzau9qJ1lfW4pNLlhNTkCfHzAVBReH9diLvGRem5+R9g2FzA8ZGN954O5Q" crossorigin="anonymous"></script>
  </body>
</html>


/* tags */
h1{
    font-family: "Montserrat-black";
    font-size: 4rem;
    line-height: 1.5;
}
p{
    color: #8f8f8f;
}
body{
    font-family: "Montserrat";
}
i{
    color: antiquewhite;
    font-size: 20px;
}

/* id's */
#cta{
    text-align: center;
    background-color: antiquewhite;
    padding: 7% 15%;
}
#footer{
    text-align: center;
    padding: 7% 15%;
}
#navbarNav{
    position: absolute;
    right: 10px;
}
#title{
    background-color: antiquewhite;
}
 #features{ 
    margin: 50px 0 100px; 
    text-align: center; 
}

#testimonials{
    background-color: antiquewhite;
    padding: 7% 15%;
    text-align: center;
    font-family: "Montserrat-Bold";
}
#press{
    background-color: antiquewhite;
    padding: 0 15% 7%;
    text-align: center;
}
#pricing{
    padding: 7% 15%;
    text-align: center;
}

/* classes */
.priccing-col{
    padding: 3% 2%;
} 
.press-logo{
    width: 15%;
}
.testimonial-image{
    width: 15%;
    border-radius: 100%;
    margin: 20px;
}
.Download-button{
    margin: 5% 3% 5% 0;
}

.navbar{
    padding-bottom: 4.5rem;
}
.navbar-brand{
    font-size: 1,5rem;
    font-family: "Ubuntu";
    font-weight: bold;
}
.nav-item{
    padding: 0 10px;
}

.nav-link{
    font-size: 1.2rem;
    font-family: "Montserret-light";
}
.container-fluid{
    padding: 3% 15%;
   
}
.footer-i{
    padding: 1rem;
}
.rotate {
    width: 60%;
    transform: rotate(25deg); /* Equal to rotateZ(45deg) */
  }
.feature{
    padding: 5%;
}
.bi:hover{
    color: #ff4c68;
}
