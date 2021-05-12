<template>
<div id="app" class="body">
<div class="appHeader bg-primary text-light">
        <div class="left">
            <a href="#" class="headerButton" data-toggle="modal" data-target="#sidebarPanel">
               <svg style="color: #ffffff; height: 24px" xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512"><title>Menu</title><path fill="none" stroke="currentColor" stroke-linecap="round" stroke-miterlimit="10" stroke-width="32" d="M80 160h352M80 256h352M80 352h352"></path></svg>
            </a>
        </div>
        <div class="pageTitle">
            <h1 alt="logo" class="logo" style="font-size: 28.5px; color: white; max-height: 27.01px; cursor: pointer;">Cryptodex</h1>
        </div>
        <div class="right">
            <router-link to="/blog" class="headerButton">
                <svg style="color: #ffffff; height: 24px" xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512"><title>Notifications</title><path d="M427.68 351.43C402 320 383.87 304 383.87 217.35 383.87 138 343.35 109.73 310 96c-4.43-1.82-8.6-6-9.95-10.55C294.2 65.54 277.8 48 256 48s-38.21 17.55-44 37.47c-1.35 4.6-5.52 8.71-9.95 10.53-33.39 13.75-73.87 41.92-73.87 121.35C128.13 304 110 320 84.32 351.43 73.68 364.45 83 384 101.61 384h308.88c18.51 0 27.77-19.61 17.19-32.57zM320 384v16a64 64 0 01-128 0v-16" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"></path></svg>
            </router-link>
        </div>
    </div>
     <!-- navbar 
      <div class="navbar navbar-expand-lg fixed-top navbar-dark bg-primary">
        <div class="container">
        <router-link to="/" class="navbar-brand">Home</router-link>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav">
      
            <li class="nav-item">
              <router-link class="nav-link" to="/blog">Blog</router-link>
            </li>
            <li class="nav-item">
            <router-link class="nav-link" to="/services">Services</router-link>
            </li>
            <li class="nav-item">
             <router-link class="nav-link" to="/contact">contact</router-link>
            </li>
          </ul>
        </div>
        </div>
      </div> -->
      <div class="container">
       <transition name="moveInUp">
         <router-view/>
       </transition>

      </div>


  <div class="appBottomMenu" style="background: #f8f8f8;">
        <router-link class="nav-link" to="/" class="item active" style="font-size: 9px; letter-spacing: 0; text-align: center; width: 100%; height: 56px; line-height: 1.2em; display: flex; align-items: center; justify-content: center; position: relative;">
            <div class="col">  
         <svg style="height: 24px;" xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512"><title>Home</title><path d="M80 212v236a16 16 0 0016 16h96V328a24 24 0 0124-24h80a24 24 0 0124 24v136h96a16 16 0 0016-16V212" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"></path><path d="M480 256L266.89 52c-5-5.28-16.69-5.34-21.78 0L32 256M400 179V64h-48v69" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"></path></svg>
                <strong style="font-size: 9px;margin-top: 4px; display: block; color: #6236FF !important; font-weight: 400; transition: 0.1s all;font-family: arial;">Home</strong>
            </div>
       </router-link>
        <router-link class="nav-link" to="/" class="item" data-toggle="modal" data-target="#exchangeActionSheet" style="font-size: 9px; letter-spacing: 0; text-align: center; width: 100%; height: 56px; line-height: 1.2em; display: flex; align-items: center; justify-content: center; position: relative;">
            <div class="col">    
           <svg style="height: 24px; color:#27173E; line-height: 1.2em;" xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512"><title>Bar Chart</title><path d="M32 32v432a16 16 0 0016 16h432" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"></path><rect x="96" y="224" width="80" height="192" rx="20" ry="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"></rect><rect x="240" y="176" width="80" height="240" rx="20" ry="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"></rect><rect x="383.64" y="112" width="80" height="304" rx="20" ry="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"></rect></svg>
             <strong style="font-size: 9px;margin-top: 4px; display: block; color: #27173E !important; font-weight: 400; transition: 0.1s all;font-family: arial;">Analysis</strong></div>

        </router-link>
        <router-link to="/contact" class="item" style="font-size: 9px; letter-spacing: 0; text-align: center; width: 100%; height: 56px; line-height: 1.2em; display: flex; align-items: center; justify-content: center; position: relative;">
            <div class="col">    
           <svg style="height: 24px; color:#27173E; line-height: 1.2em;" xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512"><title>Compass</title><path d="M448 256c0-106-86-192-192-192S64 150 64 256s86 192 192 192 192-86 192-192z" fill="none" stroke="currentColor" stroke-miterlimit="10" stroke-width="32"></path><path d="M350.67 150.93l-117.2 46.88a64 64 0 00-35.66 35.66l-46.88 117.2a8 8 0 0010.4 10.4l117.2-46.88a64 64 0 0035.66-35.66l46.88-117.2a8 8 0 00-10.4-10.4zM256 280a24 24 0 1124-24 24 24 0 01-24 24z"></path></svg>
                <strong style="font-size: 9px;margin-top: 4px; display: block; color: #27173E !important; font-weight: 400; transition: 0.1s all;font-family: arial;"> Explore</strong>
            </div>
        </router-link>
        <router-link class="nav-link" to="/blog" class="item" style="font-size: 9px; letter-spacing: 0; text-align: center; width: 100%; height: 56px; line-height: 1.2em; display: flex; align-items: center; justify-content: center; position: relative;">
            <div class="col">    
           <svg style="height: 24px; color:#27173E; line-height: 1.2em;" xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512"><title>Card</title><rect x="48" y="96" width="416" height="320" rx="56" ry="56" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"></rect><path fill="none" stroke="currentColor" stroke-linejoin="round" stroke-width="60" d="M48 192h416M128 300h48v20h-48z"></path></svg>
                <strong style="font-size: 9px;margin-top: 4px; display: block; color: #27173E !important; font-weight: 400; transition: 0.1s all;font-family: arial;">My Cards</strong>
            </div>
        </router-link>
        <router-link class="nav-link" to="/services" class="item" style="font-size: 9px; letter-spacing: 0; text-align: center; width: 100%; height: 56px; line-height: 1.2em; display: flex; align-items: center; justify-content: center; position: relative;">
            <div class="col">    
           <svg style="height: 24px; color:#27173E; line-height: 1.2em;" xmlns="http://www.w3.org/2000/svg" class="ionicon" viewBox="0 0 512 512"><title>Settings</title><path d="M262.29 192.31a64 64 0 1057.4 57.4 64.13 64.13 0 00-57.4-57.4zM416.39 256a154.34 154.34 0 01-1.53 20.79l45.21 35.46a10.81 10.81 0 012.45 13.75l-42.77 74a10.81 10.81 0 01-13.14 4.59l-44.9-18.08a16.11 16.11 0 00-15.17 1.75A164.48 164.48 0 01325 400.8a15.94 15.94 0 00-8.82 12.14l-6.73 47.89a11.08 11.08 0 01-10.68 9.17h-85.54a11.11 11.11 0 01-10.69-8.87l-6.72-47.82a16.07 16.07 0 00-9-12.22 155.3 155.3 0 01-21.46-12.57 16 16 0 00-15.11-1.71l-44.89 18.07a10.81 10.81 0 01-13.14-4.58l-42.77-74a10.8 10.8 0 012.45-13.75l38.21-30a16.05 16.05 0 006-14.08c-.36-4.17-.58-8.33-.58-12.5s.21-8.27.58-12.35a16 16 0 00-6.07-13.94l-38.19-30A10.81 10.81 0 0149.48 186l42.77-74a10.81 10.81 0 0113.14-4.59l44.9 18.08a16.11 16.11 0 0015.17-1.75A164.48 164.48 0 01187 111.2a15.94 15.94 0 008.82-12.14l6.73-47.89A11.08 11.08 0 01213.23 42h85.54a11.11 11.11 0 0110.69 8.87l6.72 47.82a16.07 16.07 0 009 12.22 155.3 155.3 0 0121.46 12.57 16 16 0 0015.11 1.71l44.89-18.07a10.81 10.81 0 0113.14 4.58l42.77 74a10.8 10.8 0 01-2.45 13.75l-38.21 30a16.05 16.05 0 00-6.05 14.08c.33 4.14.55 8.3.55 12.47z" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"></path></svg>
                <strong style="font-size: 9px;margin-top: 4px; display: block; color: #27173E !important; font-weight: 400; transition: 0.1s all;font-family: arial;">Settings</strong>
            </div>
       </router-link>
    </div>
     </div>
</template>
<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.moveInUp-enter-active{
  animation: fadeIn 2s ease-in;
}
@keyframes fadeIn{
  0%{
    opacity: 0;
  }
  50%{
    opacity: 0.5;
  }
  100%{
    opacity: 1;
  }
}

.moveInUp-leave-active{
  animation: moveInUp .3s ease-in;
}
@keyframes moveInUp{
 0%{
  transform: translateY(0);
 }
  100%{
  transform: translateY(-400px);
 }
}
      iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        overflow: visible;
        border: 0;
      }

</style>
