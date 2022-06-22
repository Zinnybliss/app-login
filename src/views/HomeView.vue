<template>
  <div class="home">
    <nav class="flex bg-blue-700 h-14 w-100 justify-between">
      <div class="flex justify-start font-bold text-white p-4 h-14">
        <img src="../assets/images/logo1.png" alt="" />
        ChelseaNG Fan Page
      </div>
      <!-- <h2 class="text-2xl font-semibold m-10"> Welcome to Zinny's coffee shop </h2> -->
      <ul class="flex justify-center items-center text-l text-white font-bold">
        <a class="mx-2" href="/login">LOGIN</a>
        <!-- <a class="mx-2" href="#banana">banana</a> -->
      </ul>
    </nav>
    <section class="image-container pt-8 w-screen bg-gray-100 flex">
      <div
        class="welcome text-6xl font-bold text-blue-600 ml-32 p-32 leading-none"
      >
        Welcome to the
        <p class="text-gray-400">ChelseaNG</p>
        fan page
      </div>
      
      <div class="player-image">
        <img src="../assets/images/player3.png" alt="" />
      </div>
    </section>
    <!-- <div class=" welcome italic pl-32 pt-8 font-semibold  content-end text-blue-900 ml-80"> Over the years, It should be prominent to note that Chelsea Fc has been the leading club in England with fans scattered all over the world. in Nigeria today, we have approximately over 30% of the number of fans based in Nigeria

      </div> -->

    <section class="bg-white">
      <h2
        class="flex items-center font-black m-8 text-3xl italic justify-center space-x-8 text-black bg-white"
      >
        Photo Gallery
      </h2>
      <div class=" main-img flex">
        <div>
        <img class="img1" src="../assets/images/88de6245836a2fbc166c57d8e945d20b.jpeg"/>
        <p class="para1">A rare picture of Kai Havertz behind his other team mates </p>
        </div>
        <div>
        <img class="img1" src="../assets/images/Players.jpeg" />
        <p class="para1">Chelsea Power 5 in a celebratory mood</p>
        </div>
        <div>
        <img class="img1" src="../assets/images/image.jpeg" />
        <p class="para1">Picture of teammates celebrating with Lukaku </p>
        </div>
        <div>
        <img class="img1" src="../assets/images/chels1.jpeg" />
        <p class="para1">Celebration mode after winning UEFA Champions league</p>
        </div>
        <div>
        <img class="img1" src="../assets/images/chels.jpeg" />
        <p class="para1">Reece James controlling the ball with his chest</p>
        </div>
        <div>
        <img class="img1" src="../assets/images/2609.webp" />
        <p class="para1"> Hudson-Callum Odoi celebrating his goal in an iconic way</p>
        </div>
        <div>
        <img id="banana" class="img1 con" src="../assets/images/1554653.jpeg" />
        <p class="para2">Ziyech, Rudiger and Jorghino in a happy mood.</p>
        </div>
      </div>
      <div
        class="div1 flex m-8 items-center justify-center space-x-8 text-blue-700 bg-white"
      >
        <span class="iconify" data-icon="dashicons:facebook-alt"></span>
        <span class="iconify" data-icon="dashicons:instagram"></span>
        <span class="iconify" data-icon="arcticons:twitter"></span>
        <span class="iconify" data-icon="iconoir:youtube"></span>
      </div>
      <div class="flex space-x-8 justify-center items-center text-blue-700">
        <div><a href="#" target="_blank">Contact Us</a></div>
        <div><a href="#" target="_blank">Modern Slavery Act</a></div>
        <div><a href="#" target="_blank">FAQs</a></div>
        <div><a href="#" target="_blank">Careers</a></div>
        <div><a href="#" target="_blank">Privacy Policy</a></div>
        <div><a href="#" target="_blank">Cookie Policy</a></div>
        <div><a href="#" target="_blank">Terms and Conditions</a></div>
      </div>
      <div class="flex space-x-8 justify-center items-center text-blue-700 p-8">
        <span class="iconify" data-icon="ic:outline-copyright"></span>2022
        Chelsea FC. All rights reserved. No part of this site may be reproduced
        without our written permission.
      </div>
    </section>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: "HomeView",
};
</script>

<style scoped>
.welcome-container {
  height: 80vh;
}

.welcome {
  height: 500px;
}
.div1 {
  height: 100px;
  width: 100%;
}

.image-container {
  width: 100%;
  display: flex;
}
.btn{
  border: 1px solid black;
}

.player-image {
  background-image: url("../assets/images/player3.png");
  /* background-repeat:no-repeat;
   background-size:contain; */
  height: 500px;
  width: 1000px;
  background: whitesmoke;
}

.player-image img {
  height: 100%;
  width: 100%;
  object-fit: contain;
}
.img1 {
  display: flex;
  height: 250px;
  width: 350px;
  margin: 20px;
  margin-left: 80px;
  align-items: center;
  justify-content: center;
}
.main-img{
   flex-wrap: wrap;
}
.con{
  display: flex;
  height: 250px;
  width: 350px;
  margin: 20px;
  margin-left: 530px;
  align-items: center;
  justify-content: center;
}
.para1{
  display: flex;
  font-style: italic;
  font-weight: 700;
  margin: 20px;
  align-items: center;
  justify-content: center;
  margin-left: 30px;

}
.para2{
  display: flex;
  margin: 20px;
  margin-left: 530px;
  align-items: center;
  justify-content: center;
  font-style: italic;
  font-weight: 700;
}
</style>
