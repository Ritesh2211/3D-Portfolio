   
   */for 3d model to spin
    animation-name: spin;
    animation-duration: 6000ms;
    animation-iteration-count: infinite;
    animation-timing-function: linear; 

    @keyframes spin {
    from {
        transform:rotate(180deg);
    }
    to {
        transform:rotate(360deg);
    }
}


css
.header{
    position: relative;
    display: flex;
    place-items: center;
    justify-content: space-between;
    background-color: #000;
    padding: 0 10vw;
  

}
.logo{
    max-width: 7vw;
    z-index: 3;
}
.main-nav-list{
     display: flex;
     list-style: none;
     gap: 3vw;
     z-index: 3;
}
.main-nav-link{
  text-decoration: seashell;
  color: #fffaff;
  font-size: 15px;
  transition: all 0.5s;
  font-family: serif;    
}
.main-nav-link:hover {
color: #494949 !important;
border-radius: 50px;
border-color: #494949 !important;
transition: all 0.3s ease 0s;

}
.hero{
    position: relative;
    display:grid;
    width: 100vw;
    height: 100vw;
}

.hero-img{
position: absolute;
width: 35vw;
margin-left: 60vw;
z-index: 1;
 }

.bg{
       height: 100vw;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
    }
.hero-description{
    position: absolute;
    width: 20vw;
    height: 10vh;
    margin-top: 10vh;
    margin-left: 20vw; 
    z-index: 2;
}
.hero-title{
    color: #fff;
    font-size: 3vw;
    font-weight: 500;
    font-family: serif;
}
.ritesh{
    color: #7a31bf;
     font-family: serif;
}
.hero-subheading{
    color: #b5a8a8 ;
    font-size: 90%;
    font-weight: 500;
    font-family: serif;
    margin-left: 20px;
}

/*hero model*/
.hero-model{
    position: absolute;

}
model-viewer{
    width: 80vw;
    height: 100vh; 
    z-index: 1;
}
/*about me*/
 .about-me{
    position: relative;
    display: grid;
    place-items: center ;
    width: 100vh;
    height: 100vh;
    padding: 1 0vw;
 }
 .about-me-description{
    width: 60vw;
    height: 65vh;
    position: absolute;
    margin-top: -150vh ;
    margin-left:40vw;
 }
 .introduction{
    color: #7e7575;
    font-size: 1vw;
    padding-bottom: 2vh;
 }
 .about-me-title{
    color: #fff;
    font-size: 3.5vw;
    font-family: sans-serif;
 }
 .about-me-subheading{
    color: #fffa;
    font-size: 1.4vw;
    font-weight: 400;
    font-family: serif;
    line-height: 1.2;
    padding-top: 3vh;
 }
 /*cards*/

 .cards{
    position: absolute;
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    top: 45vh;
 }
 .card{
    position: relative;
    display: grid;
    place-items: center;
    width: 10vw;
    height: 20vh;
    margin: 2vw;
    overflow: hidden;
    border-radius: 20px;
    box-shadow: 0 0 10px #fffa;
 }
.reactImg{
    width: 70%;
    z-index: 1;
}

.htmlcss{
    width: 70%;
    z-index: 1;
}
.java{
    width: 70%;
    z-index: 1;
}
.mysql{
  width: 130%;
  z-index: 1;
  margin-top:-2vh ;
}
.js{
    width: 70%;
    z-index: 1;
}
.title{
    color: #fff;
    position: relative;
    font-size: 1.6vw;
    text-align: center;
    z-index: 10;
    font-family: serif;
    font-weight: 400;
}
.card::before{
    content: '';
    position: absolute;
    width: 20vw;
    height: 25vh;
    background: linear-gradient(#00ccff,#d400d4);
    animation: rotation 5s linear infinite;
}
.card::after{
    content: '';
    position: absolute;
    inset:0.15vw ;
    background-color: #16063a;
    border-radius: 15px;
}
@keyframes rotation {
    0%{
        transform:rotate(0deg);
    }
    100%{
        transform:rotate(360deg);
    }
}
/*TIMEline*/
.time-line-section{
    position: relative;
    display: flex;
    align-items: center;
    width: 100vw;
    height: auto;
    background-color: #010115;
    background-size: 100vw;
    padding: 0 10vw;
}
.time-line-content{
    display: grid;
    place-items: center;
    width: 100vh;
    padding-bottom: 25vh;
}
.heading-description{
    display: grid;
    place-items: center;
    margin-bottom:10vh ;
    margin-left: -50;
}
.time-line-title{
    color: #ffffff5a;
    font-size: 1vw;
    padding-bottom: 2vh;

}
.time-line-subheading{
    color: #fff;
    font-size: 1vw;
    font-family: serif;
    margin-left: 50vw;
}