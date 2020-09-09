<template>
  <div class="home">
    <div id="homeSplash">
    <img alt="River Surges logo" id="homeLogo" src="../assets/logo.svg"><h1>River Surges</h1>
    <p>An Unofficial Spirit Island Website</p>
  </div>
</div>
</template>

<style>
    h1{
        font-family: 'Montserrat', sans-serif;
        color: #78B6E4;
        font-size:90px;
        margin:15px;
    }
    #homeSplash {
        display:flex;
        align-items: center;
        flex-flow: column;
        width:100%;
        height: 100%;
        text-transform: uppercase;
    }

    #homeSplash p {
        font-size:26px;
        font-family: 'Roboto';
        color:#aeb1a1;
    }
    #homeLogo {
        height:300px;
    }
</style>