<template>
  <div class="avantages-container">
      <div class="avantages-box" data-aos="fade-up-right">
         
          <div class="avantages-box-item" >
               <div class="avantages-tittle">
              Ưu điểm
          </div>
            <div class="avantages-box-item-top container">
                <div class="avantages-box-item-top-1 auto-layout ">
                    <div class="avantages-text">
                     Đa Dạng công Cụ Hỗ Trợ
                     </div>
                     <div class="avantages-content">
                         Sử dụng chỉ báo kỹ thuật nâng cao như RSI, EMA, Bollinger Band, Stoch, StochRSI, Ichimoku, ADX, MFI, … 
                     </div>
                </div>
                <div class="avantages-box-item-top-2 auto-layout ">
                     <div class="avantages-text">
                     Đa Dạng chiến dịch giao dịch
                     </div>
                     <div class="avantages-content">
                         Sử dụng chỉ báo kỹ thuật nâng cao như RSI, EMA, Bollinger Band, Stoch, StochRSI, Ichimoku, ADX, MFI, … 
                     </div>
                </div>
                <div class="avantages-box-item-top-3 auto-layout ">
                   <div class="avantages-text">
                     An toàn tuyệt đối
                     </div>
                     <div class="avantages-content">
                         Sử dụng chỉ báo kỹ thuật nâng cao như RSI, EMA, Bollinger Band, Stoch, StochRSI, Ichimoku, ADX, MFI, … 
                     </div>
                </div>
                
            </div>
            <div class="avantages-box-item-bottom">
                 <div class="avantages-box-item-bottom-1 auto-layout">
                 <div class="avantages-text">
                     Giao dịch tự động liên tục
                     </div>
                     <div class="avantages-content">
                         Sử dụng chỉ báo kỹ thuật nâng cao như RSI, EMA, Bollinger Band, Stoch, StochRSI, Ichimoku, ADX, MFI, … 
                     </div>
                </div>
                <div class="avantages-box-item-bottom-2 auto-layout">
                    <div class="avantages-text">
                                      Giao Diện Dễ Sử Dụng

                     </div>
                     <div class="avantages-content">
                         Sử dụng chỉ báo kỹ thuật nâng cao như RSI, EMA, Bollinger Band, Stoch, StochRSI, Ichimoku, ADX, MFI, … 
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

<style lang="scss" scoped>
.avantages-container{
    // position: absolute;
   width: 100%;
   max-width: 100%;
    .avantages-tittle{
        font-family: 'IBM Plex Sans';
        font-style: normal;
        font-weight: 700;
        font-size: 32px;
        line-height: 42px;
        text-align: center;
    }
    .avantages-box{
        //   position: absolute;
        width: 80%;
        margin: 0 auto;
        // background: red;
        // height: 873.61px;
        // left: 8rem;
        // top: 117rem;
        color: white;
    // color: white;
        .avantages-box-item{
            // background: blue;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 0px;
            gap: 30px;
            // width: 80%;
            margin: 0 auto;
            height: 638px;
            .avantages-box-item-top{
                display: flex;
                flex-direction: row;
                align-items: flex-start;
                padding: 0px;
                gap: 30px;
                width: 100%;
               
            }
            .avantages-box-item-bottom{
                   display: flex;
                    flex-direction: row;
                    align-items: flex-start;
                    padding: 0px;
                    gap: 30px;
                    width: 750px;
                    justify-content: inherit;
                    height: 304px;
            }
        }
    }
}
.auto-layout{
      display: flex;
          border: 1px solid #0b0faa;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 20px;
    gap: 24px;
    text-align: center;
    width: 50%;
   padding: 30px 20px 30px 20px;
    background: linear-gradient(135deg, rgba(7, 63, 95, 0.28) 0%, rgba(7, 67, 101, 0.46) 100%);
    backdrop-filter: blur(20px);
    border-radius: 10px;
}
.title-auto-layout{
    flex: none;
order: 0;
flex-grow: 0;
}
.avantages-text{
    font-family: 'IBM Plex Sans';
font-style: normal;
font-weight: 700;
font-size: 20px;
line-height: 30px;
/* or 180% */

text-align: center;

color: #FFFFFF;
width: 143px;
height: 72px;
}
.avantages-content{
    font-family: 'IBM Plex Sans';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 28px;
    text-align: center;
    color: #FFFFFF;
    width: 100%;
    height: 84px;
}

@media  (max-width: 992px){
    .avantages-container{
        height: 100!important;
        .avantages-box{
        .avantages-box-item{
                height: 100%!important;
            }
        } 
    }
    
  
  .avantages-box-item-top{
          flex-direction: column!important;
            font-size: 16px!important;
            align-items: center!important;;
  }
  .avantages-text{
      font-size: 18px!important;
  }
  .avantages-box-item-bottom{
      flex-direction: column!important;
      width: 100%!important;
       &-1{
            width: 100%;
              flex-direction: row!important;
        }
         &-2{
            width: 100%;
              flex-direction: row!important;
        }
         
  }
  .avantages-box-item{
        // flex-direction: row!important;
        
        width: 100%!important;
        &-top-1{
            width: 100%;
             flex-direction: row!important;

        }
         &-top-2{
            width: 100%;
             flex-direction: row!important;
        }
         &-top-3{
            width: 100%;
             flex-direction: row!important;
        }
  }


}
</style>