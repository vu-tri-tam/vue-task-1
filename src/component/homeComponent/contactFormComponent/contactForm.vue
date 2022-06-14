<template>
  <div class="contact-container pt-5 ">
      <div class="contact-box container"  data-aos="fade-up-right">
          <div class="text-center contact-tittle">Liên hệ</div>
          <div class="contact-form row">
              <div class="contact-form-container p-5 col-sm">
                <form action="">
                    <label for="">Họ và tên</label>
                    <input type="text">
                     <label for="">Email</label>
                    <input type="text">
                    <label for="">Câu hỏi</label>
                    <textarea name="" id="" cols="30" rows="10"></textarea>
                    <button>Gửi</button>
                 </form>
              </div>
              <div class="contact-form-support col-sm">
                  <div class="contact-form-support-all">
                    <h1>HỖ TRỢ HAPPY TO HELP</h1>
                    <div>
                        Nếu bạn có bất kỳ thăc mắc nào, vui lòng gửi câu hỏi đến cho chúng tôi.
                    Thắc mắc sẽ được đội ngũ chúng tôi giải đáp sau 24 giờ.
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
.contact-container{
      color: white;
    display: flex;
    flex-direction: column;
    /* justify-content: center; */
    align-items: center;
    /* padding: 80px 150px; */
    gap: 40px;
    /* position: absolute; */
    /* max-width: 710px; */
    width: 90%;
    // height: 845px;
    margin: 0 auto;
    
    .contact-form-container{
        display: flex;
        flex-direction: row;
        form{
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            padding: 0px;
            // position: absolute;                                  
            width: 100%;
            height: 477px;
            left: 10%;
            /* top: 225px; */
            gap: 24px;
            input{
                width: 100%;
                height: 52px!important;
                background: #FFFFFF;
                border-radius: 10px;
            }
            textarea{
                width: 100%;
                    border-radius: 10px;
            }
            button{
                display: flex;
                flex-direction: row;
                justify-content: center;
                align-items: center;
                padding: 10px;
                gap: 10px;

                width: 126px;
                height: 38px;

                /* Gradient R */

                background: linear-gradient(135deg, #FF3333 0%, #541012 100%);
                border-radius: 10px;
                color: white;
                border: none;
            }
        }
        
    }
    .contact-form{
         box-sizing: border-box;
            margin: 5% 0 5% 0;
    /* position: absolute; */
    width: 100%;
    border: 1px solid #0b0faa;
    height: 603px;
    /* margin: 0 auto; */
    background: linear-gradient(135deg, rgba(7, 63, 95, 0.28) 0%, rgba(7, 67, 101, 0.46) 100%);
    backdrop-filter: blur(20px);
    border-radius: 54px;
.contact-form-support{
   display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 0px;
    gap: 24px;
    /* position: absolute; */
    width: 285px;
    height: 218px;
    .contact-form-support-all{
  width: 60%;
    text-align: center;
    /* margin: 0 auto; */
    margin-top: 30%;
    }
    /* left: 645px; */
    /* top: 179px;*/
}
    }
    .contact-box{
           .contact-tittle{
               font-family: 'IBM Plex Sans';
font-style: normal;
font-weight: 700;
font-size: 32px;
line-height: 42px;
/* identical to box height */

text-align: center;
           }
        h1{
      font-family: 'IBM Plex Sans';
font-style: normal;
font-weight: 700;
font-size: 20px;
line-height: 36px;
/* or 180% */

text-align: center;

color: #FFFFFF;
        }
    }
}
@media only screen and (max-width: 680px){
    .contact-container{

    }
    .contact-box{
        width: 100%!important;
        height: 100%!important;
        .contact-form-container{
            input{
              width: 100%!important;
            }
        }
        .contact-form{
            display: flex;
            flex-direction: column!important;
            width: 100%!important;
            height: 100%!important;
        .contact-form-support{
            height: 100%!important;
            width: 100%!important;
            .contact-form-support-all {
               display: flex;
               flex-direction: column;
                //    text-align: center;
                width: 100%!important;
    /* margin: 0 auto; */
                margin-top: 10%!important;
                padding: 5%!important;
                h1{
                    font-size: 18px!important;
                }
                .contact-form-support-content{
                    text-align: left;
                }
            }
        }
}
       
    }
}
</style>