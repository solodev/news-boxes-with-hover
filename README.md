# news-boxes-with-hover
It’s not always possible to show a full news article title in a visual display; with hover effects, however, you can achieve consistent designs while still display important information.

## Tutorial
For detailed instruction's, view Solodev's [How to Create News Boxes that Show Additional Information on Hover](https://www.solodev.com/blog/web-design/how-to-create-news-boxes-that-show-additional-information-on-hover.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/e56pL7dv/).

## HTML
The tutorial contains the following basic HTML markup.

```
 <div class="container">
      <div class="row">
        <div class="col-md-12 content">
          <div class="newsroom" id="scroll-section4">
            <div class="section-heading text-center">
              <h2 class="sectional-title mt-4">Recent News</h2>
              <p>Get caught up on the latest news and stay current with the latest from LunarXP</p>
            </div>
            <div class="row" id="news-title">
              <div class="col-xs-6 col-sm-6 col-md-4 col-xl-3 thumbnail-container">
                <div class="thumbnail" onclick="location.href='#'">
                  <div class="overlay">
                    <div class="overlay-inner">
                      <a href="#">
                        <h4 class="title-hover" id="test">LunarXP has won a prestigious award for its participation in a variety of cosmic explorations.</h4>
                      </a>
                    </div>
                  </div>
                  <img alt="LunarXP Wins Space Innovator of the Year Award" class="img-responsive cover" src="https://raw.githubusercontent.com/solodev/news-boxes-with-hover/master/images/news-1.jpg">
                </div>
              </div>
              <div class="col-xs-6 col-sm-6 col-md-4 col-xl-3 thumbnail-container">
                <div class="thumbnail" onclick="location.href='#'">
                  <div class="overlay">
                    <div class="overlay-inner">
                      <a href="#">
                        <h4 class="title-hover">The new bill gives LunarXP a decade-long budget to fulfill the mission of space exploration</h4>
                      </a>
                    </div>
                  </div>
                  <img alt="New Spending Bill Expands Funding for Space Exploration" class="img-responsive cover" src="https://raw.githubusercontent.com/solodev/news-boxes-with-hover/master/images/news-2.jpg">
                </div>
              </div>
              <div class="col-xs-6 col-sm-6 col-md-4 col-xl-3 thumbnail-container">
                <div class="thumbnail" onclick="location.href='#'">
                  <div class="overlay">
                    <div class="overlay-inner">
                      <a href="#">
                        <h4 class="title-hover">LunarXP Sets Target for First Mars Landing in 2030</h4>
                      </a>
                    </div>
                  </div>
                  <img alt="LunarXP Sets Target for First Mars Landing in 2030" class="img-responsive cover" src="https://raw.githubusercontent.com/solodev/news-boxes-with-hover/master/images/news-3.jpg">
                </div>
              </div>
              <div class="col-xs-6 col-sm-6 col-md-4 col-xl-3 thumbnail-container">
                <div class="thumbnail" onclick="location.href='#'">
                  <div class="overlay">
                    <div class="overlay-inner">
                      <a href="#">
                        <h4 class="title-hover">Habitat Offerings to Include New Hydroponics Lab</h4>
                      </a>
                    </div>
                  </div>
                  <img alt="Habitat Offerings to Include New Hydroponics Lab" class="img-responsive cover" src="https://raw.githubusercontent.com/solodev/news-boxes-with-hover/master/images/news-4.jpg">
                </div>
              </div>
            </div>
            <!--close row-->
          </div>
        </div><!-- col-md-12 -->
      </div>
    </div>   
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```

