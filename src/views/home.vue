
<template>
    
    <header>
        <div class="box">
         <div class="one">
            logo
         </div>
         <!-- <div class="two">
           <ul>
            <li>首页</li>
            <li>更多</li>
           </ul>
         </div> -->
         <div class="three">
            <div class="loginbox">
                login
            </div>
         </div>

        </div>
        
    </header>
    <slot name="main" ></slot>

    <footer>
        <p>
            Copyright © 2023 - xzz
        </p>
    </footer>
</template>

<script setup lang='ts'>

</script>

<style lang="scss"  scoped>
header{
    height: 70px;
    background-color: #fff;
  .box{
    display: flex;
    justify-content: space-between;
    margin: 10px;
    .one{
        height: 50px;
        width: 50px;
        background-color: #c69494;
        cursor: pointer;
    }
    // .two{
    //     ul{
    //         display: flex;
    //       li{
    //         list-style: none;
    //       }
    //     }
    // }
    .loginbox{
        height: 50px;
        width: 50px;
        background-color: #c69494;
        cursor: pointer;
    }
  }
}

footer{
    height: 50px;
    background-color: #fff;
    p{

        text-align: center;
        line-height: 50px;
    }
}
</style>