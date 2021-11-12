<template>
  <div class="side_bar">
    <div class="user_section">
        <img src="image 14.png" />

        <p>Kristen Ramos</p>
        <p>kristenramos@email.com</p>
    </div>


    <div class="selection_icon">
      <div>
<svg width="18" height="18" fill="none" xmlns="http://www.w3.org/2000/svg"><circle cx="9" cy="9" r="8.547" fill="#fff" fill-opacity=".85" stroke="#000" stroke-width=".906"/><path d="M15.75 7.875a5.625 5.625 0 0 0-5.625-5.625v5.625h5.625Z" fill="#000"/></svg> <span class="focus"> Dasboard </span> </div><br>
<div>
<svg width="18" height="16" fill="none" xmlns="http://www.w3.org/2000/svg"><mask id="a" fill="#fff"><rect y=".536" width="18" height="14.786" rx=".643"/></mask><rect y=".536" width="18" height="14.786" rx=".643" fill="#fff" stroke="#000" stroke-width="1.671" mask="url(#a)"/><path fill="#fff" stroke="#000" stroke-width=".643" d="M11.25 6h6.429v3.214H11.25z"/></svg> <span> Holdings</span> 
   </div>
   <br>

   <div>
<svg width="14" height="14" fill="none" xmlns="http://www.w3.org/2000/svg"><rect x=".5" y="7.5" width="1" height="6" rx=".5" fill="#000" stroke="#000"/><rect x="4.5" y="2.5" width="1" height="11" rx=".5" fill="#000" stroke="#000"/><rect x="8.5" y="5.5" width="1" height="8" rx=".5" fill="#000" stroke="#000"/><rect x="12.5" y=".5" width="1" height="13" rx=".5" fill="#000" stroke="#000"/></svg> <span> Performance</span>
   </div>


    </div>

      <div class="log_out">
<svg width="28" height="26" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M9.374 18.933c-.313.33-.3.855.057 1.137A8.999 8.999 0 1 0 7.285 8.365c-.234.39-.059.885.351 1.082.41.198.898.023 1.14-.362a7.352 7.352 0 1 1 1.794 9.782c-.363-.274-.882-.264-1.196.066Z" fill="#130F26"/><path fill="#000" d="M4 13h17v2H4z"/><path d="m.507 13.836 4.005-2.93.123 5.684-4.128-2.754Z" fill="#000"/></svg><span> Logout</span>
   </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.side_bar{
  background:transparent;
  position: fixed;
}

.user_section{
  margin: 2rem 3rem;
  img{
        width: 20%;
    border-radius: 9px;
  }

  p{
    margin: -2.2rem 1rem 2rem 3rem;
    font-size: 12px;
  }
  p:last-child{
    margin: -2rem 1rem 2rem 3rem;
    font-size: 10px;



  }
}
.selection_icon{
      margin: 5rem 3rem;
      div{
        margin: 0rem 0rem 1rem -1rem;
      }
    svg{
          margin: -0.2rem 1rem;
    }
    span{

    font-weight: 800;
    font-size: 12px;

    }
    .focus::after{
    content: " ";
    width: 20px;
    height: 2px;
    background: red;
    display: block;
    margin: 0rem 3.4rem;

    }
}

.log_out{
    position: absolute;
    bottom: -17rem;
        margin: 0rem 0rem 1rem 2rem;

    span{
    font-weight: 800;
    font-size: 12px;
    }

     svg{
          margin: -0.6rem 1rem;
    }
}
</style>
