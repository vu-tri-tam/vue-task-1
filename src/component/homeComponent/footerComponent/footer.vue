<template>
  <div class="footer-container">
      <!-- <div class="footer-box-image"> -->
          <div class="footer-box-container-item container" data-aos="fade-right">
              <div class="footer-box-item auto-footer-row" >
                  <div class="footer-box-item-image"></div>
                  <div class="footer-box-item-text">
                      AIHA TECH là công ty tiên phong áp dụng các công nghệ AI vào các lĩnh vực công nghệ, tài chính, giáo dục, game...
AIHA là Robot giao dịch tự động thế hệ mới nhất trên thế giới được sở hữu bởi Tập Đoàn công nghệ AIHA Tech tại Mỹ
                  </div>
              </div>
              <div class="footer-box-social-container">
                    <div class="footer-box-item auto-layout-socal">
                    <div class="footer-box-item-container">
                      <div class="footer-box-item-1-image"></div>
                      <div class="footer-box-item-1-text">
                          Facebook
                      </div>
                    </div>
                    <div class="footer-box-item-container">
                         <div class="footer-box-item-2-image"></div>
                            <div class="footer-box-item-2-text">
                                Twitter
                            </div>
                    </div>
                    <div class="footer-box-item-container">
                         <div class="footer-box-item-3-image"></div>
                            <div class="footer-box-item-3-text">
                                Telegram
                            </div>
                    </div>
                    <div class="footer-box-item-container">
                         <div class="footer-box-item-4-image"></div>
                            <div class="footer-box-item-4-text">
                                LinkedIn
                            </div>
                    </div>
                    <div class="footer-box-item-container">
                         <div class="footer-box-item-5-image"></div>
                            <div class="footer-box-item-5-text">
                                Reddit
                            </div>
                    </div>
                </div>
                  <div class="auto-layout-socal auto-footer-flex">
                      <div class="footer-item-text-about-us">Về chúng tôi</div>
                      <div class="footer-item-text-about-us">Ưu điểm</div>
                      <div class="footer-item-text-about-us">Trải nghiệm</div>
                      <div class="footer-item-text-about-us">Team</div>
                      <div class="footer-item-text-about-us">Liên hệ</div>
                  </div>
                     
              </div>
                     <div class="footer-box-item auto-layout-center ">
                           <div class="footer-box-option-trade-tittle">
                               <h1>Blog kiến thức</h1>
                           </div>
                         <div class="footer-box-option-trade auto-layout-blog-option">Bot Trading là gì?</div>
                         <div class="footer-box-option-trade auto-layout-blog-option">Ưu điểm của Bot Trading</div>
                         <div class="footer-box-option-trade auto-layout-blog-option" >Các mẹo giúp sử dụng Bot Trading hiệu quả</div>
                     </div>  
                <!-- reponsive -->
                    


          </div>
      <!-- </div> -->
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
    .footer-container{
        // width: 1920px;
height: 700px;
// position: absolute;
width: 100%;
// height: 939px;
// background: red;
// left: 60px;
  background:  url('/images/Rectangle 64.png');
     background-repeat: no-repeat!important;
   background-size: 100% 100%;
     width: 100%;
    // height: 100%;
// top: 5848px;

    // background: radial-gradient(65.08% 100.85% at 0% 0%, #030A12 0%, rgba(0, 0, 0, 0) 100%) /* warning: gradient uses a rotation that is not supported by CSS and may not behave as expected */, url(Mesa de trabajo 6@2x.png);
    
    position: relative;
    .footer-box-container-item{
        color: white;
        // background: red;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: flex-end;
        // padding: 80px 150px;
        gap: 66px;
        margin: 0 auto;
        // position: absolute;
        width: 80%;
        height: 528px;
        // left: 240px;
        // top: 50%;
        .footer-box-social-container{
            display: flex;
            flex-direction: row;
        }
        .footer-box-item{
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            padding: 0px;
            gap: 27px;

            width: 328px;
            // height: 315px;
           .footer-box-option-trade-tittle{
               width: 100%;
              h1{
                   text-align: center;
              }
           }
            .footer-box-item-container{
                display: flex;
                flex-direction: row;
                // justify-content: center;
                align-items: center;
                padding: 0px;
                gap: 24px;
                width: 154.41px;
                height: 36.41px;
            }
            .footer-box-item-1-image{
                    background: url('/images/Group 65.png');
                    background-repeat: no-repeat!important;
                    background-size: 100% 100%;
                    width: 36.41px;
                    height: 36.41px;
            }
             .footer-box-item-2-image{
                    background: url('/images/Group 66.png');
                    background-repeat: no-repeat!important;
                    background-size: 100% 100%;
                    width: 36.41px;
                    height: 36.41px;
            }
            .footer-box-item-3-image{
                 background: url('/images/image 14.png');
                    background-repeat: no-repeat!important;
                    background-size: 100% 100%;
                    width: 36.41px;
                    height: 36.41px;
            }
            .footer-box-item-4-image{
                    background: url('/images/Group 62.png');
                    background-repeat: no-repeat!important;
                    background-size: 100% 100%;
                    width: 36.41px;
                    height: 36.41px;
            }
            .footer-box-item-5-image{
                 background: url('/images/image 15.png');
                    background-repeat: no-repeat!important;
                    background-size: 100% 100%;
                    width: 36.41px;
                    height: 36.41px;
            }
                .footer-box-item-image{
                    // position: absolute;
                    width: 216px;
                    height: 120px;
                    // left: -12px;
                    // top: -60px;

                    background: url('/images/logo.png');
                    background-repeat: no-repeat!important;
                    background-size: 100% 100%;
                 
    background-position: 100%;
    justify-content: center;
                }
        }
    }



// background: radial-gradient(65.08% 100.85% at 0% 0%, #030A12 0%, rgba(0, 0, 0, 0) 100%), url('../../../../images/Rectangle 64.png');
    }
    .auto-layout-center{
        // display: flex;
// flex-direction: row;
justify-content: center;
align-items: flex-end;
padding: 80px 150px;
gap: 66px;
    }
    .auto-layout-blog-option{
        
        background: linear-gradient(135deg, rgba(7, 63, 95, 0.28) 0%, rgba(7, 67, 101, 0.46) 100%);
        backdrop-filter: blur(20px);
        /* Note: backdrop-filter has minimal browser support */

        border-radius: 10px;
        box-sizing: border-box;

        /* Auto layout */
        width: 322px;
        // height: 81px;
        // display: flex;
        flex-direction: row;
        text-align: center;
        align-items: center;
        padding: 20px;
        gap: 10px;

    }
    .auto-layout-socal{
        display: flex!important;
        flex-direction: column!important;
        align-items: flex-start!important;
        justify-content: space-around!important;
        padding: 0px!important;
        gap: 20px!important;

        width: 154.41px!important;
        height: 262.24px!important;
    }
    .auto-footer-flex{
        align-items: flex-end!important;
    }
@media (max-width: 992px){
    
    .footer-container{
          height: 100%!important;
          width: 100%;
        //          overflow-x: scroll;
        //   overflow-y: hidden;
        //   min-height: 700px;
        //   overflow-x: scroll;
        .footer-box-container-item{
                flex-direction: column!important;
                    height: 100%!important;
                    margin-top: 20%;
                    width: 100%!important; 
                    .footer-box-item-image {
                        
                        width: 100%!important;
                        height: 5rem!important;
                    flex-direction: row!important;;
                    }
               .footer-box-social-container{
             width: 100%!important;
        }
        //   min-height: 700px;
   
                 .footer-box-item{
                     height: 100%!important;
                    //  flex-direction: row!important;
                         width: 100%!important; 
                         
                 } 
        }
    }
    .auto-footer-row{
           flex-direction: row!important;
    }
    .auto-footer-box{
        display: flex;
          flex-direction: row!important; 
    } 
    .auto-layout-socal{
        // width: 100%!important;
        .footer-item-text-about-us{
            width: 300px;
        }
    }
    .auto-layout-socal{
         width: 100%!important; 
    }
}
</style>