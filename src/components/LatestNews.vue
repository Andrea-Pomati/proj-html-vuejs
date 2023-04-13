<script>
export default {
  name: "LatestNews",
   data() {
     return {      
     }
   }
}


</script>


<template>
    <div id="container">   
        <div id="container-scritte">
            <h4>OUR EDITORIAL CONTENT</h4>
            <div id="flex-h1">

                <H1>LATEST</H1>
                <H1 id="news">NEWS</H1>
                
            </div>
            <div id="flex-pb">
                <p id="grey">Every week we publish about what is best in the business world</p>
                <button id="see-all">SEE ALL</button>

            </div>
        </div>

        <div id="container-cards">
            <div class="cards">
                <img src="/public/img/news-1.jpg" alt="">
                <p>Increasing creativity is possible for everyone</p>
            </div>
            <div class="cards">
                <img src="/public/img/news-2.jpg" alt="">
                <p>Because market research is part of the business plan</p>
            </div>
            <div class="cards">
                <img src="/public/img/news-3.jpg" alt="">
                <p>Working from home is now a trend</p>
            </div>

            <!-- prova -->

           


        </div>


    </div>
</template>


<style lang="scss" scoped>
* {
    color: black;
}

#container {
    max-width: 1400px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 150px;
   h4 {
    color: #02A4A6;;
   }
   
}

#grey {
     color: rgb(124, 124, 124);

   }
#container-scritte {
    display: flex;
    flex-direction: column;
    gap: 20px;
}

#flex-h1 {
    display: flex;
    gap: 20px;

}

#flex-pb {
    display: flex;
    justify-content: space-between;
    margin-bottom: 50px;

}

#news {
    color: #02A4A6;
    background-color: #02a3a660;
}

#see-all {
    padding: 10px 50px;
    background-color: #058283;
    color: white;

}

//inizio cards


#container-cards {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    gap: 50px;
    margin-bottom: 250px;
   
}

.cards {
    // border: 1px solid red;
    width: calc(100% / 3 - 50px / 3 * 2);
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    gap: 20px;
    position: relative;
    
    p {
        position: absolute;
        bottom: 20px;
        left: 20px;
        color: rgb(225, 255, 245);
        font-size: 30px;
        font-weight: bold;
        
        text-shadow: -1px 0 #000, 0 1px #000, 1px 0 #000, 0 -1px #000;
    }
}

img {
    width: 100%;
    
    filter: grayscale(50%); 
    
}

//prova


</style>