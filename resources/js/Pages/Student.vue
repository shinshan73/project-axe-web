<template>
    <app-layout>
        <body>
            <header>
                 <ul>
                    <li>Home</li>
                    <li>Join Us</li>
                    <li>For Recruiters</li>
                 </ul>
            </header>

            <article id="firstPage">
                <h1>THE STUDENTS</h1>
                <p>HUGE <span class="orangeSpan">FAMILY</span> OF THE WEB</p>
                <img src="images/Saly-8.png" alt="hand" class="hand">
            </article>

            <article id="secondPage">
                <div class="research">
                    <img src="images/Composant 30.png" alt="" class="researchExemple">
                    <img src="images/Composant 30-2.png" alt="" class="researchExemple">
                </div>
                <div class="secondCountain">

                         <div class="secondCountainExemple">
                        <img src="images/Composant 29.png" alt="" class="exemple">
                        <img src="images/Composant 29.png" alt="" class="exemple">
                        <img src="images/Composant 29.png" alt="" class="exemple">
                        <img src="images/Composant 29.png" alt="" class="exemple">
                        </div>
                        
                        <div class="secondCountainExemple">
                        <img src="images/Composant 29.png" alt="" class="exemple">
                        <img src="images/Composant 29.png" alt="" class="exemple">
                        <img src="images/Composant 29.png" alt="" class="exemple">     
                        <img src="images/Composant 29.png" alt="" class="exemple"> 
                        </div>

                        <div class="secondCountainExemple">
                        <img src="images/Composant 29.png" alt="" class="exemple">
                        <img src="images/Composant 29.png" alt="" class="exemple">
                        <img src="images/Composant 29.png" alt="" class="exemple">
                        <img src="images/Composant 29.png" alt="" class="exemple">
                        </div>
                        
                    </div>   
            </article>

             <footer>
             <img src="images/Image 14.png" alt="Logo IIM" class="logoIim">
            <img src="images/Groupe 204.png" alt="" class="footerDescrition">
             <img src="images/Groupe 203.png" alt="" class="footerDescrition">
              <img src="images/Groupe 202.png" alt="" class="footerDescrition">
              <div>
                  <p>FOLLOW <span class="secondSpan">US</span></p>
                  <img src="images/Groupe 200.png" alt="github" class="github">
                  <img src="images/Groupe 201.png" alt="instagram" class="instagram">
                  <img src="images/Composant 32.png" alt="admin" class="admin">
              </div>
        </footer>
        </body>
    </app-layout>
</template>

<style>
     body{
        background-color: black;
    }
    header li{
        color: #758FFD;
        margin-left: 50px;
        
    }
    header ul{
        display: flex;
        margin-left: 70%;
        padding-top: 5%;
    }
    h1{
        font-size: 60px;
        font-weight: bold;
        color: white;
        text-align: center;
        margin-top: 200px;
    }
    .orangeSpan{
        color: orange;
    }
    #firstPage{
        height: 100vh;
    }
    #firstPage p {
        color: white;
        margin-left: 40%;
        font-weight: bolder;
        font-size: 20px;
    }
    .hand{
        margin-top: -330px;
    }
    .research{
        display: flex;
         margin-left: 70%;
    }
    .researchExemple{
        height: 40px;
        margin-right: 50px;
    }
    .secondCountainExemple{
        display: flex;
    }

    .secondCountain{
        margin-left: 17%;
        margin-top: 50px;
    }
    
    .exemple{
        height: 200px;
        margin: 50px;
    }

    footer{
        height: 40vh;
        display: flex;
        margin-top: 50px;
    }
    .logoIim{
        height: 100px;
        width: 100px;
        margin: 100px;
    }

    .footerDescrition{
        height: 200px;
        width: 200px;
        margin: 50px;
    }

    footer p {
        font-size: 30px;
        color: white;
        font-weight: bold;
        margin-top: 50px;
    }
    .github{
        width: 100px;
        height: 20px;
        margin-left: 70px;
        margin-top: 20px;

    }
    .instagram{
        width: 100px;
        height: 20px;
        margin-left: 70px;
        margin-top: 10px;
    }

    footer div{
        margin-left: 50px;
    }

    .admin{
        margin-top: 20px;
    }
    


</style>

<script>
    import AppLayout from '@/Layouts/AppLayout'
    import Welcome from '@/Jetstream/Welcome'

    export default {
        components: {
            AppLayout,
            Welcome,
        },
    }
</script>