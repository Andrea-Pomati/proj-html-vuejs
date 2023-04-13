<script>
export default {
  name: "AppHeader",
  data() {
    return {
        links: [
        {
          orario: 'Open Hours: Mon - Sat - 9.00 - 18.00',
        },
        {
          numero: '+1 (305) 1234-5678',
        },
        {
          mail: 'hello@example.com',
        },
        
      ],
      
      
    }
  }
  
}
</script>

<template>

<div class="background">
    <div class="flex">
        <div v-for="link in links">
            <div>{{link.orario}}</div>
        </div>

        <div v-for="link in links">
            <div>{{link.numero}}</div>
           
            <div>{{link.mail}}</div>            
        </div>

        <div class="flex-icon">
            <i class="fa-brands fa-facebook"></i>
            <i class="fa-brands fa-twitter"></i>
            <i class="fa-brands fa-linkedin"></i>
        </div>

    </div>
</div>


</template>



<style lang="scss" scoped>

* {
    color: white;
    text-decoration: none;
}
.background {

    background-color: #21333E;
    padding: 10px 0;
    

   


}


.flex {
        max-width: 1400px;
        margin-right: auto;
        margin-left: auto;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        


    }

.flex-icon {
    display: flex;
    gap: 20px;
    align-items: center;


}





</style>

