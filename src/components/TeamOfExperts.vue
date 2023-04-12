<script>
export default {
  name: "TeamOfExperts",
   data() {
     return {      
     }
   }
}




</script>


<template>
    
    <div id="background">

        <div id="container">

            <div id="parte-sinistra">

                <div id="team-of-experts">
                    <h4>WE LIKE WHAT WE DO</h4>
                    <div id="flex-h1">
                        <h1 id="team">Team </h1>
                        <h1>of Experts</h1>
                    </div>
                  
                    <p>Ethics and integrity are the bases on which our professionals build their careers. <br> They are fundamentals that become daily attitudes.</p>
                </div>
                <!-- cards -->
                <div id="container-cards">
                    <div class="cards">
                        <div><img src="/public/img/team-1.jpg" alt="" class="img"></div>
                        <div class="container-info">
                            <h2>David Cooper</h2>
                            <span>CTO & CO-FOUNDER</span>
                            <div class="social-container">
                                <i class="fa-brands fa-facebook"></i>
                                <i class="fa-brands fa-twitter"></i>
                                <i class="fa-brands fa-linkedin"></i>
                            </div>

                        </div>

                    </div>
                    <div class="cards">
                        <div><img src="/public/img/team-3.jpg" alt="" class="img"></div>
                        <div class="container-info">
                            <h2>Oliver Jones</h2>
                            <span>CHIEF PROCUREMENT</span>
                            <div class="social-container">
                                <i class="fa-brands fa-facebook"></i>
                                <i class="fa-brands fa-twitter"></i>
                                <i class="fa-brands fa-linkedin"></i>
                            </div>
                        </div>
                    </div>
                    <div class="cards">
                        <div><img src="/public/img/team-2.jpg" alt="" class="img"></div>
                        <div class="container-info">
                            <h2>Emma Lopez</h2>
                            <span>CHIEF MARKETING</span>
                            <div class="social-container">
                                <i class="fa-brands fa-facebook"></i>
                                <i class="fa-brands fa-twitter"></i>
                                <i class="fa-brands fa-linkedin"></i>
                            </div>
                        </div>

                    </div>
                    <div class="cards">
                        <div><img src="/public/img/team-4.jpg" alt="" class="img"></div>
                        <div class="container-info">
                            <h2>T. Johnson</h2>
                            <span>CEO & PRESIDENT</span>
                            <div class="social-container">
                                <i class="fa-brands fa-facebook"></i>
                                <i class="fa-brands fa-twitter"></i>
                                <i class="fa-brands fa-linkedin"></i>
                            </div>
                        </div>
                    </div>

                </div>
                <!--fine cards  -->
            </div>

            <div id="parte-destra">
                <h1>President Speech</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique eligendi ex illum quaerat nemo, sit saepe a fugit delectus iusto distinctio molestias possimus consectetur aut. Recusandae ducimus adipisci officiis labore!</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique eligendi ex illum quaerat nemo, sit saepe a fugit delectus iusto distinctio molestias possimus consectetur aut. Recusandae ducimus adipisci officiis labore!</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique eligendi ex illum quaerat nemo, sit saepe a fugit delectus iusto distinctio molestias possimus consectetur aut. Recusandae ducimus adipisci officiis labore!</p>
                <h2>T. Johnson</h2>
            </div>

        </div>

    </div>

</template>


<style lang="scss" scoped>

#background {
    background-color: #111117;

}

#container {
    max-width: 1400px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 150px ;
   
    display: flex;
    gap: 100px;
}

#team-of-experts {
    h4 {
        color: #02A4A6;
        padding-bottom: 20px;
    }

    p {
        color: rgb(124, 124, 124);
        padding-bottom: 20px;

    }
}

#flex-h1 {
    display: flex;
    gap: 10px;
    padding-bottom: 20px;
}

#team {
    
    background-color: #02a3a660;

}

#parte-destra {
    display: flex;
    flex-direction: column;
    
    padding: 50px 20px;
    gap: 60px;
    width: 30%;
    height: 765px;
    background-color: #02A4A6
}

#parte-sinistra {
   
    width: 70%;
}

#container-cards {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    gap: 100px;
    margin-bottom: 250px;
   
}

.cards {
    // border: 1px solid red;
    width: calc(100% / 2 - 100px / 2 * 1);
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    gap: 20px;
    
}


.img {
    width: 200px;
     
}

.social-container {
    display: flex;
    gap: 10px;
}

.container-info {
    display: flex;
    flex-direction: column;
    gap: 50px;
}


.fa-brands {
    color: #02A4A6;
    font-size: 30px;
}
</style>
