<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">

    <!-- box-icon -->
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap");

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
}

body {
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: rgb(157, 154, 154);
}

.profile-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    max-width: 370px;
    width: 100%;
    background: white;
    border-radius: 24px;
    padding: 25px;
    box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
}

img {
    position: relative;
    height: 150px;
    width: 150px;
    border-radius: 50%;
    background-color: rgb(94, 101, 240);
    padding: 3px;
    margin-bottom: 10px;
}

img .profile-image {
    height: 100%;
    width: 100%;
    object-fit: cover;
    border-radius: 50%;
    border: 3px solid #fff;
}

.profile-card,
.text-data {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.text-data,
.name {
    font-size: 22px;
    font-weight: 500;
}

.text-data
.Job {
    font-size: 15px;
    font-weight: 400;
}

.profile-card
.media-buttons {
    display: flex;
    align-items: center;
    margin-top: 15px;
}

.media-buttons 
.link {
   display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  font-size: 18px;
  height: 34px;
  width: 34px;
  border-radius: 45%;
  margin: 0 25px;
  background-color: #4070f4;
  text-decoration: none;
}
.profile-card .buttons{
    display: flex;
    align-items: center;
    margin: 25px;
}
.buttons .button{
    margin: 0 10px;
    border: none;
    border-radius: 20px;
    color: white;
    font-size: 14px;
    font-weight: 400;
    padding: 8px 24px;
    background-color: rgb(74, 74, 243);
    cursor: pointer;
    transition: all 0.3s ease;
}
.button:hover{
    background-color: blue;
}
.profile-card .analytics {
  display: flex;
  align-items: center;
  margin-top: 25px;
}
.analytics .data {
  display: flex;
  align-items: center;
  color: #333;
  padding: 0 20px;
  border-right: 2px solid #e7e7e7;
}
.data i {
  font-size: 18px;
  margin-right: 6px;
}
.data:last-child {
  border-right: none;
}
</style>
</head>

<body>
    <div class="profile-card">
        <div class="image">
            <img src="i.png" alt="Rishabh" class="profile-image">
        </div>
        <div class="text-data">
            <span class="name">Coding Lab</span>
            <span class="Job">Blogger</span>
        </div>  
        <div class="media-buttons">
            <a href="#" style="background: #4267b2" class="link">
                <i class='bx bxl-facebook'></i>
            </a>
            <a href="#" style="background: black;" class="link">
                <i class='bx bxl-github'></i>
            </a>
            <a href="#" class="link" style="background: #1da1f2">
                <i class='bx bxl-twitter'></i>
            </a>
            <a href="#" style="background: #e1306c" class="link">
                <i class='bx bxl-instagram'></i>
            </a>
        </div>
        <div class="buttons">
            <button class="button">Subscribe</button>
            <button class="button">Message</button>
        </div>
        <div class="analytics">
            <div class="data">
                <i class="bx bx-heart"></i>
          <span class="number">60k</span>
        </div>
        <div class="data">
          <i class="bx bx-message-rounded"></i>
          <span class="number">20k</span>
        </div>
        <div class="data">
          <i class="bx bx-share"></i>
          <span class="number">12k</span>
            </div>
        </div>
    </div>
</body>

</html>
