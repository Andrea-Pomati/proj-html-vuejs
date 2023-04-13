<script>
export default {
  name: "KnowFirst",
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
                <h4>NEWSLETTER</h4>
                <div id="flex-h1">
                    <h1 id="know">KNOW</h1>
                    <h1>FIRST</h1>
                </div>
                
                <p>Follow closely and receive content about our company <br> and the news of the current market</p>

            </div>

            <div id="parte-destra">
                <input type="text" placeholder="Name">
                <input type="text" placeholder="Email">
                <button>SUBSCRIBE</button>
            </div>
        </div>
    </div>
</template>



<style lang="scss" scoped>

#background {
    background-image: url(../public/img/bg-1.jpg);  
}

#container {
    max-width: 1400px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 300px;
    padding-bottom: 300px;
    display: flex;
    gap: 50px;
    padding-left: 300px;
    padding-right: 300px;
}

#parte-sinistra {
    display: flex;
    flex-direction: column;
    gap: 10px;
    h4 {
        color: #02A4A6;

    }


}

#know {
   background-color: rgba(2, 163, 166, 0.3764705882);
}

#flex-h1 {
    display: flex;
    gap: 10px;
}

#parte-destra {
    display: flex;
    flex-direction: column;
    gap: 25px;
    input {
        padding-left: 20px;
        padding-right: 20px;
        padding-top: 10px;
        padding-bottom: 10px;
        width: 400px;
    }

    button {
        width: 200px;
        padding: 10px 50px;
        background-color: #058283;
        color: white;
    }
}
</style>