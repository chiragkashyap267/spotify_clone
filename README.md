<!DOCTYPE html>
<html lang="en">
  <head>
    <link
      rel="icon"
      type="image/png"
      href="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\icon.png"
      style="border-radius: 50%"
    />

    <title>Spotify-Web player music for everyone</title>
    <link
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css"
      rel="stylesheet"
    />

    <link
      href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css"
      rel="stylesheet"
    />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />
    <link rel="stylesheet" href="spotify.css" />
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <div class="header">
      <div class="spotify">
        <i class="fa-brands fa-spotify" style="color: #ffffff"></i>
      </div>
      <div class="searchbar">

        <i class="fa-solid fa-house" style="color: #ffffff;"></i>
        <input class="form-control" id="search" style="border-radius: 40px;" placeholder="What you want to play" > <i style="color: white;" class="fa-solid fa-magnifying-glass"></i></input>

      </div>
      <div class="explore">

        <span class="badge " id="expbutton">Explore all</span>
        <span class="badge " id="app">Install app</span>

      </div>
      <div class="signin">
        
        <i class="fa-regular fa-bell" style="color: #ffffff;"></i>

        <div><i class="fa-solid fa-user" style="color: #ffffff;"></i></div>
      
      
      </div>
    </div>

<div class="middle">

  <div class="librarybg">

    <div class="libheader">


    <div class="left"><i class="fa-solid fa-bars" style="color: #767676;"></i>Your Library</div>
    <div class="right"> <i class="fa-solid fa-plus" style="color: #7a7a7a;"></i><i class="fa-solid fa-arrow-right" style="color: #737373;"></i></div>

  </div>

  <div class="artist">Artists</div>

  <div class="lib3">

    <div class="lens"> <i class="fa-solid fa-magnifying-glass" style="color: #ffffff;"></i></div>
    <div class="recent"> Recents <i class="fa-solid fa-list" style="color: #ffffff;"></i></div>
  </div>


  
    
  <div class="ar1">
    <div class="img"><img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\SINGERS\shubh1.png" id="image"></div>
    <div class="name" style="line-height: 0.5rem; padding-top: 10px;"><p>Shubh</p><p>Artist</p></div>

    

    


  </div>
  <div class="ar1">
    <div class="img"><img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\SINGERS\arijit.png" id="image"></div>
    <div class="name" style="line-height: 0.5rem; padding-top: 10px;"><p>Arijit singh</p><p>Artist</p></div>

    

    


  </div>
  <div class="ar1">
    <div class="img"><img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\SINGERS\arrehman.png" id="image"></div>
    <div class="name" style="line-height: 0.5rem; padding-top: 10px;"><p>A.R Rehman</p><p>Artist</p></div>

    

    


  </div>

  </div>

  <div class="songbg">

    <div class="songheader">
      <p class="paragraph">All</p>
      <p class="paragraph">Music</p>
      <p class="paragraph">Podcast</p>
    </div>

    <h2 id="chirag">Made for chirag kashyap</h2>



    <div class="songs">

    
      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\SINGERS\shubh.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">Shubh Mashup</h5>
          <p class="card-text">Shubh, AP Dhillon,
            Cheema Y and more....</p>
        </div>
      </div>

      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\SINGERS\guru.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">Guru Mashup</h5>
          <p class="card-text">Guru Randhawa, Diljit
            Dosanjh, Ikka and more</p>
        </div>
      </div>


      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\SINGERS\Talha.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">King</h5>
          <p class="card-text">King and Arjun
            Kanungo</p>
        </div>
      </div>


      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\SINGERS\Yunus.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">Talha Anjum, Yunus</h5>
          <p class="card-text">Young Stunners and
            Faisal Kapadia</p>
        </div>
      </div>

      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\SINGERS\Raju.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">Raju Punjabi</h5>
          <p class="card-text">Raju punjabi Haryanvi</p>
        </div>
      </div>

      <h2 id="chirag2">Popular Artists</h2>
      <div style="width: 100%;"></div>

      <div class="arimages">

      <img id="goat" style="border: 2px solid white; border-radius: 60%;" src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\SINGERS\1.png" >
      <img id="goat" style="border: 2px solid white; border-radius: 50%;" src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\SINGERS\2.png" >
      <img id="goat" style="border: 2px solid white; border-radius: 50%;" src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\SINGERS\3.png" >
      <img id="goat" style="border: 2px solid white; border-radius: 50%;" src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\SINGERS\4.png" >
      <img id="goat" style="border: 2px solid white; border-radius: 50%;" src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\SINGERS\shubh1.png" >
    </div><div style="width: 100%;"></div>








      <h2 id="chirag2">Best Episodes of the week</h2>
      <div style="width: 100%;"></div>

<div class="episode">

      

      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\podcast\billion .png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">Billions Club </h5>
          <p class="card-text">Billions Club Live
            with The Weeknd•...</p>
        </div>
      </div>

      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\podcast\modi.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">Narendra Modi</h5>
          <p class="card-text">People with The
            Prime Minister Sh...</p>
        </div>
      </div>

      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\podcast\section 302.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">Episode-01</h5>
          <p class="card-text">Episode - 01 - Case
            31 -Dramatic Heis...</p>
        </div>
      </div>

      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\podcast\human.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">Aadarsh gaurav</h5>
          <p class="card-text">Adarsh Gourav on
            Love, Rejections,...</p>
        </div>
      </div>

      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\podcast\kavita seth.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">Kavita seth</h5>
          <p class="card-text">Kavita Seth &
            Kanishk Seth on...</p>
        </div>
      </div>

      
      </div>

      <div style="width: 100%;"></div>


      <h2 id="chirag2">Polular Radio</h2>
      <div style="width: 100%;"></div>

<div class="episode">

      

      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\RADIO\arijit.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">Arijit Singh</h5>
          <p class="card-text">With Sachin-Jigar,
            Vishal-Shekhar, Amit...</p>
        </div>
      </div>

      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\RADIO\shreya.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">Shreya Ghoshal</h5>
          <p class="card-text">With A.R. Rahman,
            Vishal-Shekhar, Atifm</p>
        </div>
      </div>

      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\RADIO\ar.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">A.R Rehman</h5>
          <p class="card-text">With Harris Jayaraj,
            Anirudh Ravichander,.„</p>
        </div>
      </div>

      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\RADIO\udit.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">Udit Narayan</h5>
          <p class="card-text">With Abhijeet, Utam
            Singh, Kavitam</p>
        </div>
      </div>

      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\RADIO\yoyo.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">YoYo Honey Singh</h5>
          <p class="card-text">With Badshah, Diljit
            Dosanjh, Harrdy Sandhm</p>
        </div>
      </div>

      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\RADIO\kumar.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">Kumar Shanu</h5>
          <p class="card-text">With Asha Bhosle,
            Abhijeet, Jatin-Lalit an...</p>
        </div>
      </div>

      <div class="card">
        <img src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\RADIO\kk.png" id="cimage">
        <div class="card-body">
          <h5 class="card-title">KK</h5>
          <p class="card-text">With Pritam, Mohit
            Chauhan, Armaan Malikm</p>
        </div>
      </div>


      



    

    </div>
      

    



    

<div style="height: 400px;"></div>

   
  </div>

   
</div>




<div class="bottom">

  <div  class="bleft">
    <div class="playing">
      <img style=" margin-bottom: 20px;  border-radius: 5px; width: 4rem; height: auto;" src="D:\WEB DEVELOPMENT PRATICE\PROJECTS\Project 05 (spotify front page)\podcast\billion .png" alt="">
      <div>the billion dreams
       .......
      </div>
    </div>
    
   
 
  </div>
  
  <div  class="bcenter">

    <div id="icons">
    <i style="transform: scaleX(-1);" class="fa-solid fa-rotate-right"></i>
    <i class="fa-solid fa-square-caret-left"></i>
    <i style="font-size: 2rem; padding: 5px; color: white;" class="fa-solid fa-play" ></i>
    <i class="fa-solid fa-square-caret-right"></i>
    <i  class="fa-solid fa-rotate-right"></i>
    </div>
  <div>
    <input id="bar"  type="range">
  </div>
  </div>
  <div  class="bright">
    <i class="fa-regular fa-circle-play"></i>
    <i class="fa-solid fa-bars"></i>
    <i class="fa-solid fa-laptop"></i>
    <i class="fa-solid fa-laptop-file"></i>
    <input id="rightbar" type="range">
    <i class="fa-solid fa-volume-high"></i>
    <i class="fa-solid fa-minimize"></i>
    <i class="fa-sharp fa-solid fa-maximize"></i>
  </div>

  



  







</div>
  </body>
</html>
