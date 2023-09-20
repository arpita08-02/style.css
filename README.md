* {
    font-family: Arial, Helvetica, sans-serif;
    margin: 0px;
    padding: 0px;
  }
  body::-webkit-scrollbar {
    width: 8px;
    background-color: transparent;
  }
  
  body::-webkit-scrollbar-thumb {
    background-color: rgba(0, 0, 0, 0.3);
    border-radius: 4px;
  }
  
  body::-webkit-scrollbar-thumb:hover {
    background-color: rgba(0, 0, 0, 0.5);
  }
 .container {
      color: white;
      height: 44.8em;
      box-shadow: inset 20px -40px 90px 300px #00000097;
      background-image: url(images/netflixBackground.jpg);
  }
  .logo{
      
  }
  .logo img{
      position: relative;
      top: -1em;
      left: 9em;
      height: 120px;
  }
  .container1{
      position: relative;
      top: 9em;
      display: flex;
      flex-direction:column;
      align-items: center;
      justify-content: center;
  }
  .text h1{
      font-weight: bold;
      text-shadow: 2px 2px 20px rgb(0, 0, 0);
      font-size: 50px;
      padding: 10px;
  }
  .intro1{
      display: inline;
      position: relative;
      left: 8em;
      font-size: 19px;
      padding: 10px;
  }
  .intro{
      display: inline;
      position: relative;
      left: 8em;
      font-size: 19px;
      padding: 10px;
  }
  /* language */
  .language{
      position: relative;
      left: 80%;
      top: -36%;
      width: 120px;
      height: 30px;
      background-color: rgba(0, 0, 0, 0);
      border: 1px solid rgba(255, 255, 255, 0.33);
      border-radius: 4px;
      color: white;
      display: flex;
  }
  .language img{
      position: relative;
      left: 5px;
      top: 4px;
      height: 20px;
  }
  .language p{
      font-weight: 500;
      position: relative;
      left: 17px;
      top: 6px;
  }
  .signin{
      position: relative;
      left: 88%;
      top: -40.2%;
      width: 80px;
      height: 30px;
      font-weight: bold;
      background-color: rgb(229,9,20);
      border: none;
      border-radius: 4px;
      color: white;
  }
.wrapper{
    display: flex;

}
.gettingstarted{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 201px;
    height: 55px;
    font-size: 25px;
    font-weight: bold;
    background-color: rgb(229,9,20);
    border: none;
    border-radius: 5px;
    color:white;
    position: relative;
    top: 4.6em;
    left: 24em;
}
.email{
    position: relative;
    top: 8.5em;
    left: 42em;
    background-color: rgba(0, 0, 0, 0.453);
    width: 376px;
    height: 55px;
    color: white;
    font-weight: 600;
    padding-left: 10px;
    border: 0.2px solid rgba(255, 255, 255, 0.465);
    border-radius: 5px;
}

 .page-separator{
    height: 0.5rem;
    padding: 0;
    margin: 0;
    border: none;
    background-color: rgb(35,35,35);
 } 
 .wrapper-main{
    color: white;
    overflow: hidden;
    background-color: black;
 }
.image-wrapper{
    position: relative;
    left: 49em;
    top: -7em;
}
.imagetv{
    position: relative;
    z-index: 1;
}
.video{
    position: relative;
    left: -35em;
    top: -7.4em;
    z-index: 0;

}
.text-enjoy{
    position: relative;
    display: inline;
    top: 6.5em;
    left: 2.4em;
    font-size: 35px;
    font-weight: 600;
}
.intro-discription{
    position: relative;
    top: 12.9em;
    left: 4em;
    padding: 10px;
    font-size: 19px;
    width: 26em;
}

.wrapper-download{
    overflow: hidden;
    background-color: black;
    color: white;
}
.text-download{
    position: relative;
    display: inline;
    top: 6.9em;
    left: 45em;
    z-index: 1;
    font-size: 20px;
    font-weight: 700;
}
.download-text{
    width: 12em;
}
.intro-description-download{
    position: relative;
    top: 9.7em;
    left: 56.2em;
}
.text-wrapper{
    position: relative;
    top: 5em;
    left: -4em;
}
.image-wrapper-download{
    position: relative;
    top: -5em;
    left: 12em;
    z-index: 0;
}
.textwrapper-footer{
   display: flex;
   align-items: center;
   justify-content: space-evenly;
   padding: 30px;

}
.footer-wrapper{
    background-color: black;
    overflow: hidden;
    /* display: grid; */
    /* position: relative; */
    text-decoration: underline;
    color: rgba(255, 255, 255, 0.89);
    
}
.column1,.column2,.column3:hover{
    cursor: pointer;
}
.footer-wrapper ul{
    list-style: none;
}
.column1 li{
    padding: 10px;
}
.column2 li{
    padding: 10px;
    text-decoration: underline;
}
.column3 li{
    padding: 10px;
}
