# membuat-login-html
portopolio

<html>
  <head>
    <title> Form Login Type 1 </title>
    <link href="login1.css" rel="stylesheet" type="text/css" >
  </head>

  <body>
    <div id="utama">

      <div class="header">

        <div class="header_isi">

          <div class="gambar">

            <form action="login.php" method="POST">
              <img src="bbbb.jpeg" ><br /><br />

              <input type="text" name="username" placeholder="Username" class="login_regis">     <br />
               <input type="password" name="password" placeholder="Password" class="login_regis"> <br />
              <input type="Submit" name="login" value="Masuk" class="tombol_login">
            </form>
            <hr width="74%" align="center">

          </div>
        </div>

      </div>

    </div>
  </body>
</html>


 {
  padding: 0px;
  margin: 0px;
}

#utama{
background: #7FFF00;
height: 980px;

}

.header_isi {
  width: 335px;
  height: 230px;
  padding: 180px 0px 90px 480px;
}

.gambar {
  background-color: rgba(248, 248, 255);
  height: 330px;
  border: 2px solid rgba(170, 114, 123 ,1);
}

img {
  width: 331px;
  height: 60px;
  margin-left: 0px;
  margin-top: 0px;
}

.login_regis {
  height: 30px;
  width: 270px;
  text-align: left;
  color: white;
  font-size: 15px;
  border-radius: 2px;
  background-color: rgba(225, 255, 255, 0.4);
  border: 2px solid #FFFFFF;
  margin-left: 22px;
  margin-top: 40px;
}

.tombol_login {
  width: 260px;
  height: 30px;
  text-align: center;
  background-color:#40E0D0;
  color: white;
  font-size: 17px;
  border: 5px solid #40E0D0;
  border-radius: 2px;
  margin-top: 30px;
  margin-left: 42px;
}

.chexbox {
  font-size: 15px;
  color: white;
  margin-left: 45px;
  margin-top: 10px;
}

.login_regis:hover {
  border: 3px solid #fff;
}

.tombol_login:hover {
  background-color: white;
  color: #0288D1;
  border: 2px solid white;
}

.icon{
position: relative;
}
.ion-icon{
font-size: 20px;
position: absolute;
top: 10px;
left: 15px;
}
.copyright {
  margin-top: 150px;
  color: #0288D1;
  font-size: 17px;
  margin-left: 10px;
}

a {
  text-decoration: none;
  color: black;
}

.copyright a {
  color: #0288D1;
}
