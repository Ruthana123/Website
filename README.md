body{
  background-color: lightblue;
}
header{
  text-align: center;
  background-color: grey;
  padding: 10px;
  margin: 0px;
  position: fixed;
  width: 100%;
  z-index: 1;
  left: 0;
  top: 0;
}
header h1{
  color: white;
  border: 4px solid white;
  padding: 3px 6px;
  display: inline-block;
  border-radius: 20px;
}
banner{
  position: relative;
}
.banner img{
  max-width: 100px;
}
nav{
  background-color: black;
  padding: 10px;
}
nav ul{
  white-space: nowrap;
  max-width: 1200px;
  margin: 0 auto;
}
nav li{
  width: 25%;
  display: inline-block;
  font-size: 24px;
}
nav li a{
  text decoration: none;
  color: white;
}
article h2{
  color: white;
  font-size: 40px;
}
article p{
  line-height: 2em;
  color: black;
  font-size: 20px;
}
.images{
  text-align: center;
  margin: 0;
}
.images li{
  display: inline-block;
  width: 100%
}
.images li img{
  max-width: 100%;
}
.join{
  background: black;
  text-align: center;
  padding: 0px 20px;
  color: lightblue;
}
.join h2{
  font-size: 40px;
}
form input{
  margin: 20px 0;
  padding: 10px 20px;
  font-size: 24px;
  border radius: 28px;
  border: 4px solid black;
}
/*pseudo classes*/
  nav li a: hover{
    text-decoration: underline;
  }
  .images li: hover{
    position: relative;
    top: -4px;
  }
  form input: focus{
    border: 4px dashed black;
    outline: none;
  }
  section.join p:: first-letter{
    font-size: 1.5em;
  }
  section.join p:: selection{
    background-color: white;
    color: black;
  }
footer{
  background-color: pink;
  text-align: center;
}
h2{
  text-align: center;
  font-size: 40px;
}
