# hello-world
Bootstrap project to test how to use git and github

<!doctype html>
<html lang="en">
  <head>
    <script src="https://kit.fontawesome.com/30e1f68b63.js" crossorigin="anonymous"></script>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/css/bootstrap.min.css" 
    rel="stylesheet" 
    integrity="sha384-F3w7mX95PdgyTmZZMECAngseQB83DfGTowi0iMjiWaeVhAn4FJkqJByhZMI3AhiU" 
    crossorigin="anonymous">

    <title>Bootstrap</title>
    <style type="text/css">
    body{
      position: relative;
    }
     .carousel-item {
       height:32rem;
       background-color:black;
       color:#FFF;
       position:relative;
     }
     .container {
       position:relative;
       bottom:0;
       left:0;
       right:0;
       padding-bottom: 50px;
       text-align:center;
     }
     .heading{
       position:absolute;
       text-align:left;
     }
     .overlay-image {
      position:absolute;
      bottom:0;
      left:0;
      right:0;
      top:0;
      background-position: center;
      background-size:cover;
      opacity:0.5;
     }
     h2{
       padding-top: 20px;
     }
     .card{
       margin-right:30px;
       margin-bottom:20px;
     }
     .downloadSec{
       background-image:url()
     }
     
    </style>
    
  </head>
    <body data-bs-spy="scroll" data-bs-target="#navbar">

      <nav class="navbar fixed-top navbar-expand-lg navbar-dark bg-dark" id="navbar">
        <div class="container-fluid nav" role="tablist">
          <a class="navbar-brand" href="#"><i class="fas fa-cloud-sun-rain"></i> WeatherApp</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#Home">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#InOtherNews">In Other News</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#DownloadTheApp">Download The App</a>
              </li>
            </ul>
            <form class="d-flex">
              <input class="form-control me-2" type="email" placeholder="Email Address" aria-label="Search">
              <input class="form-control me-2" type="password" placeholder="Password" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Login</button>
              <button class="btn btn-outline-success" type="submit">SignUp</button>
            </form>
          </div>
        </div>
      </nav>

      <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel" >
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner" id="Home">
          <div class="carousel-item active" data-bs-interval="7000">
            <div class="overlay-image" style="background-image: url(./storm-img.jpg) ;"></div>
            <div class="container heading">
                <h1>Top Stories</h1>
                  <p>Todays forcast for the USA offers a new wave of storms hitting the West Coast. 
                    While still offering higher temperatures, we'll notice many spirts of low-to-high winds along with light showers. Keep up with the 
                    latest weather trends by downloading the WeatherApp today! </p>
                    <a href="#" class="btn btn-lg btn-primary">Download the App Today!</a>
            </div>
          </div>
          <div class="carousel-item" data-bs-interval="5000" >
            <div class="overlay-image" style="background-image: url(./city-bus.jpg) ;"></div>
            <div class="container heading">
              <h1>Top Stories</h1>
                <p>What you should expect of this year's winter weather in your area. Keep up with the 
                  latest weather trends by downloading the WeatherApp today! </p>
                <a href="#" class="btn btn-lg btn-primary">Download the App Today!</a>
            </div>
          </div>
          <div class="carousel-item" data-bs-interval="5000">
            <div class="overlay-image" style="background-image: url(./fall-szn.jpg) ;"></div>
            <div class="container heading">
              <h1>Top Stories</h1>
              <p>Todays forcast for the USA offers a new fall season. 
              As thanksgiving and christmas comes upon us, heres what you should expect fall weather to be like in your area. 
              Keep up with the latest weather trends by downloading the WeatherApp today! </p>
              <a href="#" class="btn btn-lg btn-primary">Download the App Today!</a>
            </div>
          </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>

    <div class="container marketing">
      <div class="row col d-flex justify-content-center ">
        <h2 id="InOtherNews"> In Other News</h2>
        <p>Here's the latest stories</p>

        <div class="card" style="width: 18rem;">
          <img src="./forcast.jpeg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title"><i class="fas fa-sun"> </i>This weeks Forcast</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary" style="margin-top: 53px;">Go To Article</a>
          </div>
        </div>

        <div class="card" style="width: 18rem;">
          <img src="./baseball-game.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title"><i class="fas fa-baseball-ball"> </i>
              Games Delayed This Weekend</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go To Article</a>
          </div>
        </div>

        <div class="card" style="width: 18rem;">
          <img src="./vacation.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title"><i class="fas fa-plane-departure">  </i>Best Vacation Spots This Fall</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go To Article</a>
          </div>
        </div>


      </div>
    </div>

    <div class="container downloadSec" id="DownloadTheApp">
      <h2><i class="fas fa-cloud-sun-rain"></i> WeatherApp</h2>
      <p>Now Available On All App Stores</p>
      <h1 href="#"><i class="fab fa-android"></i></h1>
      <br>
      <h1 href="#"><i class="fab fa-apple"> </i></h1>
      <br>
      <h1 href="#"><i class="fab fa-amazon"> </i></h1>
      <h1>Download the Weather App Today!</h1>
    </div>



<div class="container">
  <footer class="py-3 my-4">
    <ul class="nav justify-content-center border-bottom pb-3 mb-3">
      <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">Home</a></li>
      <li class="nav-item"><a href="#InOtherNews" class="nav-link px-2 text-muted">In Other News</a></li>
      <li class="nav-item"><a href="#DownloadTheApp" class="nav-link px-2 text-muted">Download The App</a></li>
    </ul> 
    <p><i class="fas fa-cloud-sun-rain"> </i> 2021 WeatherApp,Inc. All rights reserved.</p>   
  </footer>
</div>

    


      
  
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-/bQdsTh/da6pkI1MST/rWKFNjaCP5gBSY4sEBT38Q/9RBh9AH40zEOg7Hlq2THRZ" crossorigin="anonymous">
    </script>

    <script type="text/javascript">


    </script>

</body>
</html>
