
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Landing Page</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  <link rel="stylesheet" href="style.css">
</head>


<body>

  <!-- Start of navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="collapse navbar-collapse" id="navbarSupportedContent">

      <ul class="navbar-nav mr-auto">
        <div class= col-md-8>
          <div class='row'>
          <div class='col-2'></div>    
           <a class="btn-success" href="index.html"> Lattitude </a>
          </div>
        </div> 
      </ul>
      <ul class="nav navbar-nav navbar-right navbar-right-custom">
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Plots
          </a>

          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="visualizations/temp.html">Max Temperature</a>
            <a class="dropdown-item" href="visualizations/humidity.html">Humidity </a>
            <a class="dropdown-item" href="visualizations/cloudiness.html">Cloudiness</a>
            <a class="dropdown-item" href="visualizations/wind.html">Wind Speed</a>
          </div>
        </li>

        <li class="nav-item active">
          <a class="nav-link" href="Comparison.html">Comparison <span class="sr-only">(current)</span></a>
        </li>

        <li class="nav-item">
          <a class="nav-link" href="data.html">Data <span class="sr-only">(current)</span></a>
        </li>

      </ul>

    </div>
  </nav>
 <!-- End of navbar -->


 <div class="container">
  <section class="row">
    <div class="col-8">
      
      <!-- <div class="page-header"> -->
        <h1 class="title">Summary: Latitude vs. X</h1>
        <hr>
      <!-- </div> -->
      <img  src="Resources/assets/images/Fig1.png"  alt=""/>
      <p> The purpose of this project was to analyze how weather changes as you get closer to the equater. To accomplish this analysis. we first pulled data from the OpenWeatherMapAPI to assemble a dataset on over 500 cities.
      </p>
      <p>After assembling the dataset, we used Matplotlib to plot various aspects of the weather vs. latitude. Factors we looked at included:temperature, cloudiness, windspeed, and humidity. This site provides the source data and visualizations created as part of the analysis,as well as explanations and descriptions of any trends and correlations witnessed.
      </p>
    </div>
    

    <div class="col-md-4">
      <h1 class="title">visualizations</h1>
        <a href="visualizations/temp.html"><img src="Resources/assets/images/Fig1.png" alt="Latitude vs. Max Temperature" class="img-thumbnail"></a>
        <a href="visualizations/humidity.html"><img src="Resources/assets/images/Fig2.png" alt="Latitude vs. Humidity" class="img-thumbnail"></a>
        <a href="visualizations/cloudiness.html"><img src="Resources/assets/images/Fig3.png" alt="Latitude vs. Cloudiness" class="img-thumbnail"></a>
        <a href="visualizations/wind.html"><img src="Resources/assets/images/Fig4.png" alt="Latitude vs. Wind Speed" class="img-thumbnail"></a>
    </div>
  </section>
 </div>

      <!-- Start of footer -->
      <footer class="text-center">
        <div class="footer">&copy; Landing Page</div>
      </footer>
      <!-- End of footer -->
  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  
  </body>
</html>
