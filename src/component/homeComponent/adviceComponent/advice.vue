<template>
  <div class="advice-container ">
      <div class="">
        <div class="advice-box row" data-aos="fade-right">
                <div class="align-center col-sm">
                            <div class="advice-box-image"></div>
                    </div>
                    <div class="advice-box-item col-sm" data-aos="fade-right">
                            <div class="advice-box-title">
                                AIHA là một nền tảng giao dịch không giám sát hoặc bị giám sát bởi bất kì bên thứ ba nào. Chúng tôi phát triển nền tảng này với mong muốn cung cấp các giải pháp giao dịch tự động an toàn, hiệu quả và giảm thiểu tối đa rủi ro cho các nhà giao dịch nhờ vào các công nghệ Blockchain tiên tiến.
                            </div>
                    </div>
                    <div class="advice-box-item col-sm" data-aos="fade-right">
                                <h1>Lời khuyên</h1>
                            <div class="advice-box-title">
                            AIHA là một công cụ hỗ trợ giao dịch tự động, giúp nhà giao dịch đưa ra các quyết định mua hoặc bán dựa vào các phân tích, dấu hiệu từ thị trường và hoàn toàn không dựa vào cảm tính. Bên cạnh đó, công cụ này sẽ hỗ trợ đàm phán hiệu quả và giao dịch một cách an toàn.

        Hãy là một nhà giao dịch thông minh, sử dụng robot AIHA như là một công cụ quản lý vốn đầu tư có mức độ hiệu quả tương đương với các chuyên gia tài chính với công thức “Sức Khỏe, Trí Tuệ và Kỹ Luật”
                            </div>
                            <div class="advice-title-bottom">
                                AIHA GIÚP BẠN TỰ DO TỰ TẠI – TỰ DO TÀI CHÍNH
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
    .advice-container{
            // background: red;
          background: linear-gradient(0deg, rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('../../../../images/bg 4.png');
            // position: absolute;
              background-repeat: no-repeat;
                            background-size: 100%;
            width: 100%;
            // height: 1040px;
            // left: 0px;
            // top: 4639px;
            .advice-box{
                 
                    // background: red;
                    //  border: 1px solid #0b0faa;
                    width: 80%;
                    margin: 0 auto;
                     border-radius: 10px;
                    display: flex;
                    flex-direction: column;
                    justify-content: center;
                    align-items: center;
                    /* padding: 0px 150px 80px; */
                    gap: 80px;
                     .advice-box-image{
                            background: url('../../../../images/logo.png');
                            background-repeat: no-repeat;
                            background-size: cover;
                            background-position: 100%;
                            // width: 604px;
                            height: 335.56px;
                            width: 80%;
                            margin: 0 auto;
                                                    
                        }
                   
                       
                        .advice-box-text{
                            width: 100%;
                            height: 100%;
                            // background:blue; 
                        
                        }
                        .advice-box-item{
                            padding: 59px 155px;
                            box-sizing: border-box;
                              border: 1px solid #0b0faa;
                            // margin-top: 20%;
                            display: flex;
                            flex-direction: column;
                            justify-content: center;
                            align-items: center;
                            padding: 20px;
                            gap: 10px;
                            width: 100%;
                            height: 230px;
                            background: linear-gradient(135deg, rgba(7, 63, 95, 0.28) 0%, rgba(7, 67, 101, 0.46) 100%);
                            backdrop-filter: blur(20px);
                            border-radius: 10px;
                            h1{
                                // padding: 0;
                                margin: 0;
                                font-family: 'IBM Plex Sans';
                                font-style: normal;
                                font-weight: 700;
                                font-size: 32px;
                                line-height: 42px;
                                /* identical to box height */

                                text-align: center;

                                color: #FFFFFF;
                            }
                            .advice-box-title{
                                font-family: 'IBM Plex Sans';
                                font-style: normal;
                                font-weight: 400;
                                font-size: 18px;
                                line-height: 28px;
                                /* or 156% */

                                text-align: center;

                                color: #FFFFFF;
                            }
                            .advice-title-bottom{
                                font-family: 'IBM Plex Sans';
                                font-style: normal;
                                font-weight: 700;
                                font-size: 20px;
                                line-height: 36px;
                                /* identical to box height, or 180% */


                                /* Secondary */

                                color: #FF3333;

                            }
                        }

                    
            }
    }
    @media only screen and (max-width: 680px){
    .advice-container {
        .advice-box{
            gap: 40px!important;
            .advice-box-image{
                    height: 9rem!important;
            }
            .advice-box-item{
                height: 100%!important;

                .advice-box-title{
                    font-size: 16px!important;
                }
                
            }
        } 
    }
}
</style>