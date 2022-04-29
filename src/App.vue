<template>
  <div id="app">
    <router-view />
  </div>
</template>
<style lang="css">
body::-webkit-scrollbar-track
{
	border: 1px solid rgb(136, 136, 136);
	background-color: #F5F5F5;
}

body::-webkit-scrollbar
{
	width: 10px;
	background-color: #F5F5F5;
}

body::-webkit-scrollbar-thumb
{
	background-color: #0466C8;	
  border-radius: 10px;  
}
</style>