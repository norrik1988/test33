
import { NuxtLayout } from '#build/components';

<template>
  <header>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
  
  </header>
    <div id="app">
      <default />
      <router-view /> 
    </div>
  </template>
  
  <script>
  
  
  export default {
   
    }
  
  </script>
  
  <style>
  
  #app {
    font-family: Arial, sans-serif;
  }
  
  body {
    margin: 0px !important
  }
  </style>