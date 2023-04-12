<script>
export default {
  name: "ExcellenceInServices",
   data() {
     return {      
     }
   }
}




</script>



<template>

<div id="background">
    
    <div id="first-part">
        <h4>OUR BUSINESS AREAS</h4>
        <div id="flex-title"><h1>Excellence in</h1><h1 id="services">Services</h1></div>
            <div id="flex-p">

                <p>We are leaders in providing consultancy services with a set of cutting-edge technologies and a team of <br> experienced and renowned professionals. These are some options that you can hire.</p>
                <button id="see-all">SEE ALL</button>

            </div>
        

    </div>
    <div id="container-cards">
        <div class="cards">
            <div id="flex-arrow"> 
                <i class="fa-solid fa-sitemap"></i>
                <i class="fa-solid fa-arrow-right"></i>
            </div>
           

            <h2>Audit & Assurance</h2>
            <p>Lorem ipsum dolor sit amet <br> consectetur adipisicing elit </p>
        </div>

        <div class="cards">
            <div id="flex-arrow"> 
                <i class="fa-solid fa-briefcase"></i>
                <i class="fa-solid fa-arrow-right"></i>
            </div>

            <h2>Audit & Assurance</h2>
            <p>Lorem ipsum dolor sit amet <br> consectetur adipisicing elit </p>

        </div>

        <div class="cards">
            <div id="flex-arrow"> 
                <i class="fa-solid fa-chart-simple"></i>
                <i class="fa-solid fa-arrow-right"></i>
            </div>

            <h2>Audit & Assurance</h2>
            <p>Lorem ipsum dolor sit amet <br> consectetur adipisicing elit </p>

        </div>

        <div class="cards">
            <div id="flex-arrow"> 
                <i class="fa-solid fa-plane-up"></i>
                <i class="fa-solid fa-arrow-right"></i>
            </div>

            <h2>Audit & Assurance</h2>
            <p>Lorem ipsum dolor sit amet <br> consectetur adipisicing elit </p>

        </div>

        <div class="cards">
            <div id="flex-arrow"> 
                <i class="fa-solid fa-earth-americas"></i>
                <i class="fa-solid fa-arrow-right"></i>
            </div>
            <h2>Audit & Assurance</h2>
            <p>Lorem ipsum dolor sit amet <br> consectetur adipisicing elit </p>

       </div>

       <div class="cards">
            <div id="flex-arrow"> 
                <i class="fa-solid fa-inbox"></i>
                <i class="fa-solid fa-arrow-right"></i>
            </div>

            <h2>Audit & Assurance</h2>
            <p>Lorem ipsum dolor sit amet <br> consectetur adipisicing elit </p>

        </div>


    </div>

    
</div>


</template>


<style lang="scss" scoped>
* {
    color: black;
}

#background {
    max-width: 1400px;
    margin-right: auto;
    margin-left: auto;
   

}

#first-part {
    display: flex;
    flex-direction: column;
    gap: 30px;
    padding-top: 150px;
    margin-bottom: 50px;
    h4 {
        color: #02A4A6;
    }

}

#flex-title {
    display: flex;
    gap: 12px;

    h1 {
        font-size: 50px;
    }
}

#services {
    color: #02A4A6;
    background-color: #02a3a660;
    
}


#flex-p {
    display: flex;
    justify-content: space-between;
    margin-bottom: 50px;
    p {
        color: rgb(124, 124, 124);
        
    }

}

#see-all {
    padding: 10px 50px;
    background-color: #058283;
    color: white;

}

// fine prima parte
#container-cards {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    gap: 20px;
    margin-bottom: 400px;
}
.cards {
    
    width: calc(100% / 3 - 20px / 3 * 2);
    display: flex;
    flex-direction: column;
    gap: 20px;
   
}

#flex-arrow {
    display: flex;
    flex-direction: row;
    justify-content: space-between;


}

.fa-solid {
    color: #02A4A6;
    font-size: 40px;
}

.fa-arrow-right {
    font-size: 25px;
}
</style>