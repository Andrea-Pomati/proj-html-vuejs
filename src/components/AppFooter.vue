<script>

export default {
  name: "AppFooter",
  data() {
    return {
        about: [
        {
          abouts: 'The Company',
        },
        {
          abouts: 'Institutional',
        },
        {
          abouts: 'Social & Events',
        },
        {
          abouts: 'Innovation',
        },
        {
          abouts: 'Environment',
        },
        {
          abouts: 'Technology',
        },
      ],
      
      services: [
        {
          servicess: 'Audit & Assurance',
        },
        {
          servicess: 'Financial Advisory',
        },
        {
          servicess: 'Analytics M&A',
        },
        {
          servicess: 'Middle Marketing',
        },
        {
          servicess: 'Legal Consulting',
        },
        {
          servicess: 'Regulatory Risk',
        },
      ],
    
      support: [
        {
          supports: 'Responsibility',
        },
        {
          supports: 'Terms of Use',
        },
        {
          supports: 'About Cookies',
        },
        {
          supports: 'Privacy Policy',
        },
        {
          supports: 'Accessibility',
        },
        {
          supports: 'Information',
        },
      ],

    }
  }
  
}


</script>



<template>

<div id="background">

    <div id="container">

        <div id="container-cards">

            <div class="cards" id="color-first-card">
                <img src="/public/img/nexgen-logo.svg" alt="logo">
                <p>A Functional HTML Template for Corporate & Business</p>
                <div class="flex-icon">
                    <i class="fa-solid fa-phone"></i> 
                    <span>+1 (305) 1234-5678</span>
                </div>
               <div class="flex-icon">
                <i class="fa-solid fa-envelope"></i>
                <span>hello@example.com</span>
               </div>
                <div class="flex-icon">
                    <i class="fa-solid fa-location-dot"></i>
                    <span>Main Avenue, 987</span>
                </div>
                
                <button>GET IN TOUCH</button>
            </div>
            <div class="cards background-cards">
                <h2>About</h2>
                <div v-for="about in about">
                <div class="flex-chevron"><i class="fa-solid fa-chevron-right"></i>{{about.abouts}}</div>
                </div>
            </div>
            <div class="cards background-cards">
                <h2>Services</h2>
                <div v-for="services in services">
                <div class="flex-chevron"><i class="fa-solid fa-chevron-right"></i>{{services.servicess}}</div>
                </div>
            </div>
            <div class="cards background-cards">
                <h2>Support</h2>
                <div v-for="support in support">
                <div class="flex-chevron"><i class="fa-solid fa-chevron-right"></i>{{support.supports}}</div>
                </div>
            </div>



        </div>

    </div>

</div>

<!-- parte finale -->

<div id="background-finale">

    <div id="container-finale">

        <div id="sinistra-finale">
            <p>Enjoy the low price. We are tracking any intention of piracy.</p>

        </div>

        <div id="destra-finale">
            <i class="fa-regular fa-copyright"></i>
            <p>2020 NEXGEN is Proudly Powered by <span id="codings">Codings</span></p>

        </div>

    </div>

</div>



</template>


<style lang="scss" scoped>

* {
    color: rgb(162, 161, 161);
}

h2 {
    color: white;
}

button {
    color: white;
    background-color: transparent;
    padding: 10px;
    border: 1px solid #058283;
    width: 200px;
}

img {
    width: 200px;
}
#background {
    background-color: #111117 ;


}

#container {
    max-width: 1400px;
    margin-right: auto;
    margin-left: auto;
    padding-top: 150px;
    padding-bottom: 150px;
}

#container-cards {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    gap: 50px;
    
}
.cards {
    // border: 1px solid red;
    width: calc(100% / 4 - 50px / 4 * 3);
    display: flex;
    flex-direction: column;
    gap: 20px;
   
}

.flex-icon {
    display: flex;
    gap: 10px;
    align-items: center;
}

.flex-chevron {
    display: flex;
    gap: 10px;
    align-items: center;
}

.flex-chevron:hover {
    color: #058283;
}

.background-cards {
    background-color: #19191F;
    padding: 20px 60px;
}


//parte finale

#background-finale {
    background-color: #0D0D11;


}

#container-finale {
    max-width: 1400px;
    margin-right: auto;
    margin-left: auto;
    display: flex;
    justify-content: space-between;
    padding: 40px 0;


}

#destra-finale {
    display: flex;
    align-items: center;
}

#codings {
    color: #058283;
}
</style>