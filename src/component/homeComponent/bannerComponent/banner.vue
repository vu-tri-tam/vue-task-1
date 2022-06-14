<template>

  <div class="banner-container container mt-5 mb-5">

      <div class="banner-infomation row "  data-aos="fade-right">  
        <div class="banner-box-item-left col-sm" >
            <div class="p-3"  data-aos="fade-up" data-aos-anchor=".other-element">
                <div class="banner-item-text">
                        <h3>AIHA - Sự Lựa Chọn Hoàn Hảo</h3>
                        <h1>ROBOT GIAO DỊCH TỰ ĐỘNG SỐ 1 THẾ GIỚI</h1>
                </div>
                <div class="banner-item-button"  >
                        <button class="button-left">Đăng ký</button>
                        <button class="button-right">Đăng Nhập</button>
                </div>
            </div>
           
        </div>
        <div class="banner-box-item-right col-sm">
        
            <div class="banner-box-image-gadient"></div>
            <div class="banner-box-image">
               
            </div>
             
            <a data-bs-toggle="modal" data-bs-target="#staticBackdrop">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16">
            <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.007 2.007 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.007 2.007 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31.4 31.4 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.007 2.007 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A99.788 99.788 0 0 1 7.858 2h.193zM6.4 5.209v4.818l4.157-2.408L6.4 5.209z"/>
            </svg>
            </a>

            <!-- <img :src="image" alt=""> -->
        </div>
         
      </div>
      <div class="banner-all container mt-5 " data-aos="fade-down-right">
        <div class="banner-option row">
                <div class="banner-option-box col-sm">
                    <div class="banner-text">Giao dịch dựa trên vào cảm xúc</div>
                </div>
                <div class="banner-option-box col-sm">
                    <div class="banner-text">Không có kinh nghiệm</div>
                </div>
                <div class="banner-option-box col-sm">
                    <div class="banner-text-3">Kinh tế thế giới rơi vào khủng hoảng</div>
                </div>

        </div>
      </div>
  <Modal/>

   

    
  </div>
</template>

<script>
import Modal from './modalBanner/modal.vue'
export default {
    data() {
        return {
            image: "../../../../public/images/image 13.png",
            showModal: false
        };
    },
    components: { Modal }
}
</script>

<style lang="scss" scoped>
.banner-container{
    .banner-infomation{
       
    h3{
        color: white;
    }
    .banner-box-item-right{
        // position: absolute;
        position: relative;
    
// transform: matrix(-1, 0, 0, 1, 0, 0);
        width: 100%;
        height: 446px;
        
        .banner-box-image{
        position: absolute;
        width: 100%;
        height: 431px;
        /* left: -166px; */
        top: 10px;
        background: url('../../../../public/images/image 13.png');
                background-size: cover;
    background-repeat: no-repeat;
    background-position-x: 52%;
            background-repeat: no-repeat;
            border-radius: 10px;
    }
    .bi-youtube{
            position: absolute;
            z-index: 10;
            width: 100px;
            height: 70px;
            left: 61%;
            top: 43%;
            width: 3;
            /* font-size: 27px!important; */
            border-radius: 12px;
                // color: white;
               
            }
    .banner-box-image-gadient{
        background: linear-gradient(135deg, #2892CE 0%, #093A55 100%);
        filter: blur(40px);
        transform: matrix(-1, 0, 0, 1, 0, 0);
        width: 100%;
        height: 446px;
        left: 1621px;
        top: 282px;
    }
    }
    
    .banner-item-text{
        width: 449px;
        margin-bottom: 24px;
        // height: 84px;
        h1{
            font-family: 'IBM Plex Sans';
font-style: normal;
font-weight: 700;
font-size: 32px;
line-height: 42px;
   margin-top: 24px;
color: #FFFFFF;
        }
        h3{
         
                font-family: 'IBM Plex Sans';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 28px;
    color: #FFFFFF;
    opacity: 0.8;
        }
    }
    .banner-item{
        width: 449px;
        height: 84px;
    }
    .banner-item-button{
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        padding: 0px;
        gap: 30px;

// width: 282px;
// height: 126px;

        .button-left{
            background: linear-gradient(135deg, #FF3333 0%, #541012 100%);
        }
        .button-right{
            background: linear-gradient(135deg, #2892CE 0%, #093A55 100%);
        }
        button{
            font-family: 'IBM Plex Sans';
            font-style: normal;
            font-weight: 700;
            font-size: 20px;
            line-height: 36px;
            text-align: center;
            color: #FFFFFF;
            box-shadow: inset -4px -4px 8px rgba(0, 0, 0, 0.25), inset 4px 4px 8px rgba(255, 255, 255, 0.25);
            border-radius: 50px;
            display: flex;
            flex-direction: row;
            justify-content: center;
            align-items: center;
            padding: 10px;
            gap: 10px;
            width: 92px;
            height: 92px;
    

        }
 

      
    }
    }
    .banner-option{
       
        gap: 30px;
       
        .banner-option-box{
            display: flex;
            border: 1px solid #0b0faa;

            flex-direction: row;
            justify-content: center;
            align-items: center;
            padding: 20px;
            gap: 10px;

            width: 250px;
            height: 126px;

            background: linear-gradient(135deg, rgba(7, 63, 95, 0.28) 0%, rgba(7, 67, 101, 0.46) 100%);
            backdrop-filter: blur(20px);
            /* Note: backdrop-filter has minimal browser support */
            border-radius: 10px;
       
        .banner-text{
            width: 148px;
            height: 72px;
            font-family: "IBM Plex Sans";
            font-style: normal;
            font-weight: 700;
            font-size: 20px;
            line-height: 36px;
            text-align: center;
            color: #FFFFFF;
          
            /* Inside auto layout */
            flex: none;
            order: 0;
            flex-grow: 0;
            &-3{
                order: 2;
                font-size: 20px;
                font-family: "IBM Plex Sans";
                font-style: normal;
                font-weight: 700;
                text-align: center;
                color: #FFFFFF;
            }
            }
        }
    }
}
@media(max-width: 992px){
   .banner-option{
       
        gap: 30px;
       
        .banner-option-box{
            width: 100%!important;
        }
   }
   .banner-box-item-left{
       .banner-item-text{
           width: 100%!important;
       }
   }
   .banner-box-item-right{
     .banner-box-image{
    position: absolute;
    width: 90%!important;
    height: 355px!important;
    left: 0!important;
    top: 10px;
    margin: 0 auto;
    right: 0;
 
}
.banner-box-image-gadient{
        height: 367px!important;
}
   }
}
</style>