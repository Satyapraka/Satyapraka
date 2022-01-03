 <html lang="en">
  <head>
  <style>
    body{

    background-image:url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ3gjmByBfgznQBAs7osDd8efqfYM_5jdLh_g&usqp=CAU");

    background-repeat:;

    background-attachment:fixed;

    background-position:right top;

}

    .font{

        font-size:4px;

        text-decoration:bold;

        font-family:Cursiv;

        text-shadow:1px 1px maroon;

        color:teal;

        background-color:white;

        width:45px;

    }

        .container{

            background-image:url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRlJEjIeFpLWTW2bYdUntvVqfNmbK94_bkJYw&usqp=CAU");

            background-repeat:none;

            border:2;

            border-width:3px;

            border-color:aqua;

            border-style:inset;

            padding-left:8px;

            padding-top:8px;

            text-decoration:bold;

            margin-top:8px;

        }

    input{

        background-color:lightblue;

        padding-top:4px;

        margin-top:4px;

        

    }

.btn{

    background-color:teal;

    border-style:outset;

    border-color:pink;

    border-width:2px;

    text-decoration:bold;

    margin-left:10%;

    margin-top:16px;

    width:75%;

    padding:10px;

    font-weight:bold;

    font-size:1em;

    color:lime;

}

select{

    background-color:aquamarine;

    border-style:outset;

    border-width:4px;

        margin-top:6px;

}
      .cont{
    margin-top:20px;
    margin-left:20px;
       width:260px; background-image:linear-gradient(Olive,teal,purple,maroon);
        border-style:groove;
        border-width:2px;
        border-radius:3px;
        align:center;
        text-decoration:bolder;
        text-indent:5px;
        text-shadow:1px 1px black;
        font-weight:bold;
    }
     .comment{  
     background-color:pink;
     width:99%;
   border-style:ridge;
   border-radius:5px;
   border-width:6px;
   border-color:silver;
     }

    .bhasha{
        background-color:aquamarine;
        border-style:outset;
        border-width:4px;
        margin-top:6px;
        
    }
        .complete{
            font-family:cursive;
            color:maroon;
            text-shadow:1px 2px red;
        }
                .anim{
                    margin-top:-12px;
                    background-color:silver;
                    
                }
            .fb,.insta,.link{
                width:35px;
                height:35px;
                border-radius:0;
            }    
                .gif{
                    width:240px;
                    height:160px;
                    border-style:outset;
                    border-width:1px;
                    border-radius:3px;
                    margin-left:35px;
                    margin-top:5px;
                }
                .cd{
                    text-align:center;
                    color:cyan;
                }
    .detail{
  margin-top:8px;
  margin-bottom:8px;
  padding: 2px 6px;
  width: 300px;
  background-color:gold;
  border-style:groove;
  box-shadow: 3px 3px 4px black;
  cursor: pointer;
}

.summ{
    text-shadow:1px 1px darkgreen;
    color:#FF8C00;
    font-family:Times New Roman;
    font-weight:bold;
}
    </style>
  </head>
    <body text="white">
   
    
    <audio loop id="audio">
    <source src="https://dl.dropbox.com/s/5f41kjghl9yaphn/song%20.mp3?dl=0" type="audio/mp3"> 
  </audio>  
 
  <script>
 
let audio = document.getElementById("audio");

window.addEventListener("click",() => {
  audio.play();
});
    function submited(){
        alert("You Have Completed ☑️☑️☑️")
        alert("Thank You So Much 🚻🚻 For Giving Your Time.... See You Soon 😚")
    }
  </script>
  <fieldset>
  <marquee class="anim" behavior="alternate" direction="right">
  <legend class="font">Akm Royals..</legend>
  </marquee>
  <img class="gif" src="https://miro.medium.com/max/1400/1*rvicjpdEcxw5V71q959IkQ.gif">
  <br /><br /><br />
  <details class="detail">
  <summary align=center class="summ">Open Me Dear..🤗</summary>
  
  <div class="cont">
  <input checked="checked" name="info" type="radio" value="student">STUDENT📚
  <input checked="checked" name="info" type="radio" value="graduated">GRADUATED🎓
  </div>
  <strong><big>
  <div class="container">
  <form action="/action.php" method="post"> Name : <input name="name" type="text" /> <br />
  Age : <input max="90" min="1" name="age" step="1" type="number" value="18" /> 
  <br /> 
  <input checked="checked" name="newsletter" type="radio" value="Male" />Male
  <input name="newsletter" type="radio" value="female" /> Female
 <br />
 You Are :
  <select name="Catagory">  
<option selected="selected" value="student">
Student</option>
 <option value="engineer">
 Software Engineer</option> 
 <option value="computer engineer">
    Computer Science Engineer
 </option>
 <option value="developer">
     Web Developer
 </option>
 <option value="nothing">
    * Nothing
 </option>
 </select>
  <br />
  <article>Your Aim :</article>
  <textarea class="comment" cols="20" name="comments" rows="5">
  Comment</textarea><br />
      Country/Region🌍 :<input name="country" type="text" style="width:99%; padding-top:4px;">
  <br /> 
  City/Town🗾 :<input name="city" type="text" style="width:99%; padding-top:4px;">
  <br />
  Language :
  <select class="bhasha" name="language">
      <option selected="selected" value="pronoun">* Pronoun</option> 
      <option value="UK">
        <option value="Indian">Hindi(#Indian)</option>
      <option value="bhojpuri">
          Bhojpuri
      </option>
      <option value="Sanskrit">Sanskrit</option>
  </select>
  <br />
  <label class="complete">      
  <input name="terms" type="checkbox" value="tandc" />Yeah, I Read And See Your Code...</label>
  <br/><br />
  <center>
  <a href="https://m.facebook.com/">
    <img class="fb" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQoHrHlkgQoTSaaMK8Fr_O-QUV27MaETd16Xg&usqp=CAU"></a>
   <a href="https://www.instagram.com/accounts/signup/phone"><img class="insta" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFCB1MJJ-JImFB4BMuaqCId0fv3QnhwMmlVA&usqp=CAU"></a>
   <a href="https://www.linkedin.com/uas/login?session_redirect=https%3A%2F%2Fwww.linkedin.com%2Fmwlite%2Fhome"><img class="link" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSoxLkMUy64TeKA7rAnvlUA37rnhlL2cPEeLw&usqp=CAU"></a>
   </center>
    <code class="cd">
   Please, Link Your Accounts Here
   </code>
   <br>
   Facebook :<input name="fb" type="text" style="width:99%;">
   <br /><br>
   Instagram :<input name="Insta" type="text" style="width:99%;">
   <br><br>
   Twitter :<input name="twit" type="text" style="width:99%;">
   <br>
   <button class="btn" onclick="submited()">
   Submit
   </button>
   
    </form>
    </div>
    </big>
    </strong>
    </details>
</fieldset>




    </body>
</html>

        
        
        
        
        
        
        
        
        
          English(UK)
      </option>
   
