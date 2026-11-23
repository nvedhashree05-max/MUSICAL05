# MUSICAL05
A musical page where i've used HTML,CSS and Bootstrap to build this page
#HTML Part
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous"/>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div>
        <div class="card-container d-flex flex-column justify-content-center">
            <h1 class="head-container">MUSIC<br/>
            FUSION <br/>
            FESTIVAL</h1>
            <p class="para-container">Blend genres , create<br/>
            hormony, ignite passion</p>
            <a href="#sectionourmission" class="head2-container">Our Mission</a>
        </div>
        <div id="sectionourmission" class="ourmissioncard">
            <h1 class="ourmissionhead">OUR MISSON</h1>
            <p class="ourmissionpara">A Harmony heights, were passionate about bringing diverse<br/>
            musical genres together.Our team of musicians and event<br/>
            organuzes work tireleslly cultures</p>
            <div class="d-flex flex-row justify-content-center">
                <div class="d-flex flex-column">
                <img src="https://s3.ap-south-1.amazonaws.com/new-assets.ccbp.in/frontend/loading-data/niat_static/niat_bootstrap/html_hyperlinks_1_v8_img_1.jpg" class="img-cont"/>
                <p class="ourmissionpara2">Listen</p>
                </div>
                <div class="d-flex flex-column">
                <img src="https://s3.ap-south-1.amazonaws.com/new-assets.ccbp.in/frontend/loading-data/niat_static/niat_bootstrap/html_hyperlinks_1_v8_img_2.jpg" class="img-cont"/>
                <p class="ourmissionpara2">Blend</p>
                </div>
                <div class="d-flex flex-column">
                <img src="https://s3.ap-south-1.amazonaws.com/new-assets.ccbp.in/frontend/loading-data/niat_static/niat_bootstrap/html_hyperlinks_1_v8_img_3.jpg" class="img-cont"/>
                <p class="ourmissionpara2">Experience</p>
                </div>
            </div>
        </div>
    </div>
  </body>
</html>


#CSS PART
@import url("https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap");
.card-container{
    background-image:url("https://s3.ap-south-1.amazonaws.com/new-assets.ccbp.in/frontend/loading-data/niat_static/niat_bootstrap/html_hyperlinks_1_v8_bg_1.jpg");
    background-size:cover;
    height:100vh;
    text-align:center;
    padding:30px;
}
.head-container{
    color:#FF1493;
    font-family:Monoton;
}
.para-container{
    color:#FFD700;
    font-family:Lobster;
}
.head2-container{
    color:#FF1493;
    font-family:Lobster;
    text-decoration:line-through;
    font-size:28px;
}
.ourmissioncard{
    background-color: black;
    background-size:cover;
    height:100vh;
    text-align:center;
    padding:30px;
}
.ourmissionhead{
    font-family:Monoton;
    color:#FFD700;
}
.ourmissionpara{
    color:white;
    font-family:Roboto;
}
.ourmissionpara2{
    color:#FF1493;
    font-family:Lobster;
}
.img-cont{
    height:50px;
    width:60px;
    border-radius:25px;
}
