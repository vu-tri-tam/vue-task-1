<template>
  <div class="blog-container">
      <div class="blog-box" data-aos="fade-down-right">
          <div class="blog-tittle">Blog kiến thức</div>
  
          <div class="blog-box-content auto-blog-row col-sm-5">
              <div class="blog-box-content-item auto-layout-blog">
                  <div class="blog-box-content-item-image"></div>
                  <div class="blog-box-content-item-content">
                      <div class="blog-box-content-item-content-container">
                          <h1>BOT TRADING LÀ GÌ</h1>
                          <div>
                              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vitae fermentum congue enim dolor sed dictum quam… 
                          </div>
                          <button>Đọc thêm</button>
                      </div>
                  </div>
              </div>
              <div class="blog-box-content-item auto-layout-blog">
                  <div class="blog-box-content-item-image"></div>
                  <div class="blog-box-content-item-content">
                      <div class="blog-box-content-item-content-container">
                          <h1>ƯU ĐiỂM CỦA BOT TRADING?</h1>
                          <div>
                             Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vitae fermentum congue enim dolor sed dictum quam… 
                          </div>
                              <button>Đọc thêm</button>
                      </div>
                  </div>
              </div>
               <div class="blog-box-content-item auto-layout-blog">
                  <div class="blog-box-content-item-image"></div>
                  <div class="blog-box-content-item-content">
                      <div class="blog-box-content-item-content-container">
                          <h1>CÁC “MẸO” GIÚP SỬ DỤNG BOT TRADING HiỆU QUẢ</h1>
                          <div>
                              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vitae fermentum congue enim dolor sed dictum quam… 
                          </div>
                              <button>Đọc thêm</button>
                      </div>
                  </div>
              </div>
          </div>
      </div>

  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.blog-container{
    color: white;
    padding: 0 8%;
    // display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    gap: 80px;

    // height: 723px;
  .blog-tittle{
      text-align: center;
      font-family: "IBM Plex Sans";
    font-style: normal;
    font-weight: 700;
    font-size: 32px;
    line-height: 42px;
    text-align: center;
    color: #FFFFFF;
  }
     h1{
        font-family: 'IBM Plex Sans';
    font-style: normal;
    // text-align: center;
    font-weight: 700;
    font-size: 20px;
    line-height: 36px;
    }
    .blog-box-content{
        
        .blog-box-content-item-image{
            width: 355px;
            height: 187px;
            background: url('../../../../public/images/unsplash_-bX6sdYw48s.png');
            border-radius: 10px 10px 4px 0px;
            background-size: 100% 100%;
        }
    }
    .blog-box-content-item{
      button{
            background: linear-gradient(135deg, #FF3333 0%, #541012 100%);
            border-radius: 10px;
            display: flex;
            flex-direction: row;
            justify-content: center;
            align-items: center;
            padding: 10px;
            gap: 10px;
            width: 126px;
            height: 38px;
            color: white;
            border: none;
            margin-top: 10px;
      }
      .blog-box-content-item-content-container{
          padding: 4%;
      }
    }
}

.auto-layout-blog{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
border: 1px solid #0b0faa;
    width: 355px;
    height: 433px;

    background: linear-gradient(135deg, rgba(7, 63, 95, 0.28) 0%, rgba(7, 67, 101, 0.46) 100%);
    backdrop-filter: blur(20px);
    /* Note: backdrop-filter has minimal browser support */

    border-radius: 10px;
}
.auto-blog-row{
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    padding: 0px;
    gap: 38px;
    margin-top: 80px;
    width: 1141px;
    // height: 441px;
}
@media(max-width: 992px){
    .blog-container{
        
         .blog-box-content-item-image{
                width: 100%!important;
                
         }
    }
      
.auto-layout-blog{
    width: 100%!important;

}
.auto-layout-blog-option{
    width: 100%!important;
}
.auto-blog-row{
      width: 100%!important;
    flex-direction: column!important;;
    align-items: flex-start;
  
    // height: 441px;
}
}
</style>