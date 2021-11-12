<template>
    <div>
        <div class="foot">
            <span>SYMBOL</span>

            <span>PRICE</span>
            <span>% RETURN</span>
            <span> TOTAL NET COST</span>
            <span>MARKET VALUE</span>
            <span> TOTAL GAIN</span>
            <span>DAILY GAIN</span>
            <span>%PORTFOLIO</span>

        </div>

         <div class="foot_1">
            <span>
                <img class="apple" src="Group 1024.png" alt="">
                AAPL</span>

            <span>= $ 234.00</span>
            <span class="grenn"> $ 45.43</span>
            <span> $1 234.00</span>
            <span>$ 1345.87</span>
            <span class="grenn"> $ 456.34</span>
            <span>- $ 3.45</span>
            <span class="reder">13,45%</span>

        </div>
    </div>
</template>


<style scoped lang="scss">
    .foot{
        padding-left: 24%;
        span{
            font-size: 10px;
    color: #bab7c3;
    padding: 0rem 1rem;
        }

        span:first-child{
                margin: 3rem 9rem 0rem 0rem;

        }

        
    }

    .foot_1{

    padding-left: 24%;
    padding-top: 1rem;
    padding-bottom: 1rem;

span{
      padding: 0rem 1rem;
      font-weight: 500;
}


        span:first-child{
                      margin: 0rem 3.2rem 0rem 0rem;
      font-weight: 700;


        }
    }

    .apple{
            margin: 0rem 1rem -0.5rem 0rem;

    }
    .grenn{
  color: #44aba9;
 
}
  .reder{
      color: #C47476;


    }
    .foot_1::after{
          content: " ";
    width: 3px;
    height: 40px;
    background: #44aba9;
    display: block;
    margin: -27px -1rem;
    position: absolute;
        border-radius: 1px;
    }



@media only screen and (max-width: 600px) {
     .foot_1{
  padding-left: 0rem;
  
}

.foot{
  padding-left: 0rem;
  
}

}

</style>