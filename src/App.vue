<template>
  <router-view />
</template>

<style>

body, h1, h2, h3, h4, h5 {margin: 0px; padding: 0px;font-family: "DM Sans", Arial, Tahoma, sans-serif;}
ul, li {margin: 0px; padding: 0px; list-style-type: none;}

#app {font-family: "DM Sans", Arial, Tahoma, sans-serif;-webkit-font-smoothing: antialiased;-moz-osx-font-smoothing: grayscale;text-align: center;color: #2c3e50;}
#nav {padding: 30px;}
a.router-link-exact-active {color: #2196f3 !important;border-bottom: 2px solid #2196f3 !important;}

/* other styles */
/* Selection Color */
::selection {background:#1fcfd4;color:#fff;text-shadow:none;}
::-moz-selection {background:#1fcfd4;color:#fff;text-shadow:none;}
::-webkit-selection {background:#1fcfd4;color:#fff;text-shadow:none;}

/* Let's get this party started */
::-webkit-scrollbar {width: 5px;}
::-webkit-scrollbar:hover {width: 5px;cursor:pointer;} 
/* Track */
::-webkit-scrollbar-track {box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.11);-webkit-border-radius: 0px;border-radius: 0px;}
/* Handle */
::-webkit-scrollbar-thumb {-webkit-border-radius: 0px;border-radius: 0px;background: rgba(0, 0, 0, 1);box-shadow: inset 0 0 15px rgba(237, 237, 237, 1);}
::-webkit-scrollbar-thumb:window-inactive {background: rgba(60, 49, 49, 0.56);}

/*placeholder*/
::-webkit-input-placeholder {color: #ccc; font-weight: 100;}
::-moz-placeholder {color: #ccc; font-weight: 100;}
:-ms-input-placeholder {color: #ccc; font-weight: 100;}
:-moz-placeholder {color: #ccc; font-weight: 100;}

/* input focus */
input:focus, select:focus, textarea:focus {outline:none;}

</style>
