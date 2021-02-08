function changeImage() {

    if (document.getElementById("toggle").src == "https://media.discordapp.net/attachments/800187622705332265/803733057752137838/7pK8YynVOJUdOysgfEqppDgTmA7OBaYX7UpVVwDJgKem2nSRJkiRJkiRJkiRJkiRJkiRJkiRJkiRJkiRJkiRpBP8fUhOHbPyfwu8.png")
    {
        document.getElementById("toggle").src = "https://media.discordapp.net/attachments/800187622705332265/803733057752137838/7pK8YynVOJUdOysgfEqppDgTmA7OBaYX7UpVVwDJgKem2nSRJkiRJkiRJkiRJkiRJkiRJkiRJkiRJkiRJkiRpBP8fUhOHbPyfwu8.png";
    }
    else 
    {
        document.getElementById("toggle").src = "https://media.discordapp.net/attachments/800187622705332265/803733057752137838/7pK8YynVOJUdOysgfEqppDgTmA7OBaYX7UpVVwDJgKem2nSRJkiRJkiRJkiRJkiRJkiRJkiRJkiRJkiRJkiRpBP8fUhOHbPyfwu8.png";
    }
    }



    function LightTheme() {
        var element = document.body;
        element.classList.toggle("LightTheme");
      
        
      }
      



      function LightThemeChange() {
        document.documentElement.classList.add("LightTheme") // this will enable light mode
        document.documentElement.classList.remove("LightTheme") // this will DISABLE lightmode=
      }
      
      <a id="Home" href="https://stealthwave.dev">Home</a>
<a id="About" href="https://stealthwave.dev/projects">About</a>


@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500&family=Raleway:wght@300&display=swap');
@import url(https://fonts.googleapis.com/css?family=Quantico);



body{
  background: rgb(0, 0, 0);
  overflow:hidden;


}

::selection{
  background-color:#1fda82;
  color:black;
}

#GLOBE{
  position:absolute;
  left:95.5%;
  cursor:pointer;
}
#Home{
  position:absolute;
    font-size:2vw;
    color:rgb(255, 255, 255);
    left:62%;
    top:37.5%;
    font-family: 'Poppins', sans-serif;
    text-decoration:none;
    transition:all 0.4s;
} #Home:hover{
  color:#1fda82;
} #About{
  position:absolute;
    font-size:2vw;
    color:rgb(255, 255, 255);
    left:73%;
    top:37.5%;
    font-family: 'Poppins', sans-serif;
    text-decoration:none;
    transition:all 0.4s;
} #About:hover{
    color:#1fda82;
} #Title{
      position:absolute;
      font-size:4.5vw;
      color:rgb(255, 255, 255);
      left:4%;
      top:25%;
      font-family: 'Poppins', sans-serif;
  } #Subtitle{
      position:absolute;
      left:4%;
      top:43%;
      color:#979797;
      font-size:1.5vw;
      font-family: 'Poppins', sans-serif;
    } #Github{
      font-family: 'Poppins', sans-serif;
      color:white;
      position:absolute;
      font-size:1.5vw;
      top:56%;
      left:6.5%;
      cursor:pointer;
      text-decoration:none;
      transition:all 0.4s;
  } #Github:hover{
  color:#1fda82;
  }
    #GithubIcon{
      position:absolute;
      widows:2.2vw;
      height:2.2vw;
      top:56%;
      left:3.7%;
      cursor:pointer;
      } #TwitterIcon{
        position:absolute;
        width:2.2vw;
        height:2.2vw;
        left:20.5%;
        top:56%;
        cursor:pointer;
      }
      #Twitter1{
      font-family: 'Poppins', sans-serif;
      color:rgb(255, 255, 255);
      position:absolute;
      font-size:1.5vw;
      top:56%;
      left:23%;
      cursor:pointer;
      text-decoration:none;
      transition:all 0.4s;
      } #Twitter1:hover{
        color:#1fda82;
        cursor:pointer;
      }
      #Email{
        font-family: 'Poppins', sans-serif;
      color:white;
      position:absolute;
      border-radius:1vw;
      font-size:1.5vw;
      top:56%;
      left:39.5%;
      cursor:pointer;
      text-decoration:none;
      transition:all 0.4s;
      } #Email:hover{
        color:#1fda82;
      }
      
      #MailIcon{
    position:absolute;
        width:2.2vw;
        height:2.2vw;
        left:37%;
        top:56%;
        cursor:pointer;
  }
