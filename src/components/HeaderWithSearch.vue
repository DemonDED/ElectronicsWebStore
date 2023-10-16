<template>
  <div id="header-search-body">
    <h1>DNS</h1>
    <div id="main-search">
      <input type="text" id="main-search" placeholder="Поиск">
    </div>
    <div>
      <div>
        <img src="@/assets/button.png">
        <img src="@/assets/button-1.png">
        <img src="@/assets/button-2.png">
      </div>
    </div>
  </div>
</template>

<style lang="scss">
  #header-search-body {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #0A58CA;
    h1 {
      color: white;
      width: 20%;
    }
    
    #main-search {
      width: 60%;

      input{
        width: 40%;
        padding: 12.5px 15px 12.5px 15px;
      }
    }

    >div {
      width: 20%;
      >div {
        width: 40%;
        display: flex;
        justify-content: center;
        justify-content: space-around;
      }
    }
  }
</style>