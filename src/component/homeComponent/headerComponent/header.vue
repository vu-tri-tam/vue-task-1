<template>
  <section>
      <div class="header-container pb-5 w-100">
          <div class="header-item">
              
                  
                 


                    <!-- test reponsive -->
                  <nav class="navbar navbar-expand-lg navbar-light text-white w-100 mx-2">
                    <div class="container-fluid">
                        <div class="navbar-brand">
                                    <img :src="image" alt="">
                        </div>
                        <!-- <a class="navbar-brand" href="#">Navbar</a> -->
                        <button class="navbar-toggler backGround-menu-mobile" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                        </button>
                        <div class="collapse navbar-collapse" id="navbarSupportedContent">
                        <ul class="navbar-nav me-auto mb-2 mb-lg-0 backGround-mobile ">
                            <li class="nav-item active">
                            <a class="nav-link p-4" href="#">Trang chủ</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link p-4" href="#">Về chúng tôi</a>
                        </li>
                       <li class="nav-item">
                            <a class="nav-link p-4" href="#">Ưu điểm</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link p-4" href="#">Trải nghiệm</a>
                        </li>
                         <li class="nav-item">
                            <a class="nav-link p-4" href="#">Team</a>
                        </li>
                         <li class="nav-item">
                            <a class="nav-link p-4" href="#">Blog</a>
                        </li>
                         <li class="nav-item">
                            <a class="nav-link p-4" href="#">Liên hệ</a>
                        </li>
                        </ul>
                        
                        </div>
                    </div>
                </nav>
                  </div>
                  
              </div>
       
  </section>
</template>

<script>
export default {
    data(){
        return {
            image:'../../../../images/logo_aiha-removebg 1.png'
        }
    }
}
</script>

<style lang="scss" scoped>

.header-item{
    display: flex;
    width: 100%;
    margin: 0 auto;
    justify-content: space-between;
    // padding: 5rem;
}
.header-nav ul li{
    display: inline-block;
    list-style: none;
    color:white;
    padding: 1rem;

}
.header-nav{
    .header-list{
        padding: 1rem;
    }
}
.backGround-menu-mobile{
        background: none!important;
    }
 .backGround-mobile{
        background:none;
   
       li{
           a{
           color: white!important;

           }
       }

    }
@media(max-width: 992px){
    .backGround-menu-mobile{
        background: linear-gradient(135deg, #f9fafb 0%, rgb(241 250 255 / 46%) 100%) !important;
    }
    .backGround-mobile{
        background: linear-gradient(135deg, rgba(7, 63, 95, 0.28) 0%, rgba(7, 67, 101, 0.46) 100%)!important;
        // background: white!important;
        border-radius: 10px;
        li{
           a{

           color: rgb(240, 239, 239)!important;

           }
       }
       li:hover{
               border: 1px solid #0b0faa;
            background: linear-gradient(135deg, rgba(7, 63, 95, 0.28) 0%, rgba(7, 67, 101, 0.46) 100%)

       }
       
    }
    
}

</style>