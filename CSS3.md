
.parallax {
  /* The image used */
  background-image: url(../Photos/FcBck.jpg);

  /* Set a specific height */
  height: 500px;

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}


.header{
    font-family: 'Op', serif;
    font-size: 40px;
    color: #DAA520;
}
img{
  border-radius: 8px;
  width: 100%;
  height: 100%;
  object-fit: cover;
}


.column {
    float: left;
    width: 30%;
    padding: 20px;
    margin-left: 12px;
  }
  /* centers last Scion member */
  .column2{
    float: center;
    width: 30%;
    padding: 20px;
    margin-left: auto;
    margin-right: auto;
  }

  
  
  /* Clearfix (clear floats) */
  .row::after {
    content: "";
    clear: both;
    display: table;
  }
  /* Touches edge of screen */
  hr.FullBar {
    border: 5px solid  #DAA520;
    border-radius: 3px;
    box-shadow: 2px 2px black;
  }

  /* Doesnt touch edge of screen*/
  hr.MidBar{
    border: 5px solid  #DAA520;
    border-radius: 3px;
    box-shadow: 2px 2px black;
    width: 95%;
  }
  h3{
    text-shadow: 2px 4px black;
    text-align: center;
    font-size: 42px;
    color: #DAA520; 
  }
  h2{
    text-shadow: 2px 2px black;
    text-align: center;
    color: #DAA520;
    font-size: 28px;
  }
  h1{
    text-shadow: 2px 3px black;
    text-align: center;
    font-size: 30px;
    color: #DAA520;
  }

/* <p> with left side text */
.pLeft{
  margin-left: 20px;
  color: #DAA520;
  text-shadow: 2px 2px black;
  font-size: 24px;
  width: 45%;
  }

/* <p> with right side font */
.pRight{
  float: right;
  margin-right: 20px;
  color: #DAA520;
  text-shadow: 2px 2px black;
  font-size: 24px;
  width: 45%;
  }
