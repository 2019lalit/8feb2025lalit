

/*.box{
  height: 300px;
  width: 300px;
  border: 5px solid black;
  background-color: brown;
}

@media (max-width:600px) {
  .box{
    background-color: royalblue;
  }
}*/
*{
  margin: 0%;
  padding: 0%;
  box-sizing: border-box;
}
.main{
  height: 100%;
  width: 100%;
  position: relative;
  
}
.nav{
  height: 100px;
  width: 100%;
  /*background-color: red;*/
  border-bottom: 2px solid #dadada;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 3vw;
 
  
  
}
.nav-part2{
  display: flex;
 /* background-color: blue;*/
 align-items: center;
  gap: 2vw;
  
}
.nav h2{
  font-size: 2vw;
  font-weight: 700;
}
.nav h4{
  font-size: 2vw;
}
.nav i{
  font-size: 1.6vw;
  flex-wrap: 800;
  display: none;
}
@media (max-width:600px) {
  .nav{
    background-color: lightseagreen;
    color: #fff;
    padding: 0 5vw;
  }
  .nav h2{
    font-size: 6vw;
  }
  .nav h4{
    font-size: 4vw;
    display: none;
  }
  .nav i{
    display: block;
    font-size: 6vw;
  }
}
