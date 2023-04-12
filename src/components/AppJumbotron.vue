<script>
export default {
  name: "AppJumbotron",
  data() {
    return {
        links: [
        {
          link: 'home',
        },
        {
          link: 'about',
        },
        {
          link: 'services',
        },
        {
          link: 'process',
        },
        {
          link: 'team',
        },
        {
          link: 'blog',
        },
        {
          link: 'get in touch',
        },
        
      ],
      
      
    }
  }
  
}

</script>


<template>
<div id="background-building">
    <!-- container margini -->
    <div id="container-jumbo">

        <div id="container-logo-links"><img src="/public/img/nexgen-logo.svg" alt="logo-nexgen" id="logo-nexgen"></div>

        <div  id="flex-link">
            <div v-for="link in links">
            <div>{{link.link}}</div>
        </div>

    </div>
       
  
    </div>

    <div id="container-insurance">

        <div id="insurance-left"></div>
        <div id="insurance">
                <h4 id="fusions">FUSIONS & ACQUISITIONS</h4>
                <h1 class="insurance-consulting">Insurance</h1>
                <h1 class="insurance-consulting">Consulting</h1>
                <div id="flex-input">
                    <input type="text" placeholder="Name">
                    <input type="text" placeholder="Email">
                    <input type="text" placeholder="Phone">
                    <input type="text" placeholder="More Info">   
                </div>

                <div id="flex-button">
                    <button class="get-in-touch">GET IN TOUCH</button>
                    <button class="read-more">READ MORE</button>
                </div>

        </div>





    </div>



    
<!-- /container margini -->
</div>

</template>


<style lang="scss" scoped>

#background-building {
    background-image: url(../public/img/bg-6.jpg);
    height: 1000px;
    color: black;

}

#container-jumbo {
    max-width: 1400px;
    margin-right: auto;
    margin-left: auto;
    display: flex;
    justify-content: space-between;
    padding-top: 20px;

}

#container-logo-links {
    
    height: 80px;


}

#logo-nexgen {
    height: 100%;

}

#flex-link {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 20px;
    text-transform: uppercase;
    font-size: 30px;
}


/* insurance consulting */

#container-insurance {
    max-width: 1400px;
    margin-right: auto;
    margin-left: auto;
    display: flex;
    justify-content: space-between;

}

#insurance {
    width: 500px;
    height: 500px;
  
    margin-top: 200px;
    
}

#fusions {
    color: #058283;

}

.insurance-consulting {
    color: #21333E;
    font-size: 70px;
    margin-bottom: 40px;
}

#flex-input {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    margin-bottom: 30px;
    
    input {
        width: 240px;
        height: 50px;
        padding-left: 20px;
        background-color: #CDD0D3;
        border: none;

       

    }


}


#flex-button {
    display: flex;
    gap: 20px;
}

.get-in-touch {
    padding: 10px;
    background-color: #058283;
    color: white;

}

.read-more {
    padding: 10px;
    border: 1px solid #058283;
    color: #058283;

}
</style>