<script>
export default {
  name: "TheCompany",
   data() {
     return {      
     }
   }
}

</script>



<template>

<div id="background">

    <div id="container">

        <div class="containers" id="container-left">
            <h4>ABOUT THE NETWORK</h4>
            <h1>The Company</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis ducimus nemo architecto sequi facere molestiae, autem laborum similique fugiat est quam in, placeat voluptas dolore totam quibusdam quod. Similique, pariatur.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut sint sapiente ab omnis voluptas sunt explicabo sed rerum velit, aliquam mollitia est id dolor eos esse dolore ullam eveniet blanditiis.</p>

        </div>

        <div class="containers" id="container-right">

        <div class="flex-two" id="margin-bot">
            <div>
                <h2><i class="fa-solid fa-medal"></i> Tradition</h2>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore est temporibus, ipsum quae rem facere natus</p>
            </div>

            
            <div>
                <h2> <i class="fa-solid fa-lock"></i> Security</h2>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore est temporibus, ipsum quae rem facere natus</p>
            </div>
        </div>
         
        <div class="flex-two">
            <div>
                <h2><i class="fa-solid fa-pen-to-square"></i> Certificate</h2>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore est temporibus, ipsum quae rem facere natus</p>
            </div>

            
            <div>
                <h2><i class="fa-solid fa-graduation-cap"></i> Expertise</h2>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore est temporibus, ipsum quae rem facere natus</p>
            </div>
        </div>    

            
        </div>






    </div>


    
</div>

</template>


<style lang="scss" scoped>

#background {
    background-color: #111117 ;
}

#container {
    max-width: 1400px;
    margin-right: auto;
    margin-left: auto;
    display: flex;
    justify-content: space-between;


}

.containers {

    width: 650px;
    
    margin: 100px 0;

    h4 {
        color: #02A4A6 ;


    }

    h1 {
        font-size: 45px;

    }

    p {

        color: rgb(124, 124, 124);
    }



}

#container-left {
    display: flex;
    flex-direction: column;
    gap: 50px;
}

#container-right {
    display: flex;
    flex-direction: column;


}

.flex-two {
    display: flex;
   height: 200px;
    gap: 30px;
}

.fa-solid {
    color: #02A4A6;


}

#margin-bot {
    margin-bottom: 70px;
}
</style>