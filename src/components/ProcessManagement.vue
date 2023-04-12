<script>
export default {
  name: "ProcessManagement.vue",
   data() {
     return {      
     }
   }
}




</script>


<template>
<div id="container">

    <div id="flex-center">
        <h4>HOW IT WORKS IN PRACTICE</h4>
        <div id="flex-h1">
            <h1 id="process">Process</h1>
            <h1>Management</h1>

        </div>

        <p>We work with innovative methodologies to ensure that the entire reformating process is done <br> from start to finisch as planned</p>



    </div>
</div>

<!-- fine container con margini -->

<div id="container-cards">

    <div class="cards">
        <span>01</span>
        <h2>Collection of information</h2>
        <p>Lorem ipsum dolor sit amet consectetur</p>
    </div>
    <div class="cards">
        <span>02</span>
        <h2>Strategic Planning</h2>
        <p>Lorem ipsum dolor sit amet consectetur</p>
    </div>
    <div class="cards">
        <span>03</span>
        <h2>Assignement of responsibilities</h2>
        <p>Lorem ipsum dolor sit amet consectetur</p>
    </div>
    <div class="cards">
        <span>04</span>
        <h2>Formatting process</h2>
        <p>Lorem ipsum dolor sit amet consectetur</p>
    </div>
    <div class="cards">
        <span>05</span>
        <h2>Continuity formalization</h2>
        <p>Lorem ipsum dolor sit amet consectetur</p>
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
}

#flex-center {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    h4 {
        color: #02A4A6;
        padding-bottom: 20px;
    }

    div {
        display: flex;
        gap: 20px;
        padding-bottom: 20px;

    }

    p {
        color: rgb(124, 124, 124);
        padding-bottom: 80px;
        text-align: center;
    }
}

#process {
    color: #02A4A6;
    background-color: #02a3a660;
}

// fine container margini

#container-cards {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    gap: 100px;
    margin-bottom: 250px;
    padding: 0 50px;


}

.cards {
    // border: 1px solid aquamarine;
    width: calc(100% / 5 - 100px / 5 * 4);
    display: flex;
    flex-direction: column;
    gap: 20px;
    align-items: center;
    text-align: center;

    span {
        background-color: #DAECED;
        padding: 10px;
        border-radius: 50px;
        font-weight: bold;
        color: #02A4A6;
    }

    p {
        color: rgb(124, 124, 124);;
    }
}



</style>