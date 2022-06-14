<template>
  <div class="globe-container">
      <div class="globe-box" data-aos="fade-left">
        <h1>About Us</h1>
        <div class="globe-box-show-about-us">
            <div class="globe-box-image"></div>
            <div class="globe-box-content">
              <div class="globe-box-content-item">
                <div class="globe-box-content-container">
                      <div class="globe-box-item-left">Company Name:</div>
                  <div class="globe-box-item-right">EggsBook Unichain Solution LLC</div>
                </div>
                 <div class="globe-box-content-container">
                      <div class="globe-box-item-left">Established Time:</div>
                  <div class="globe-box-item-right">9th November, 2021</div>
                </div>
                 <div class="globe-box-content-container auto-globe-gap">
                      <div class="globe-box-item-left">Adress:</div>
                  <div class="globe-box-item-right ml-5">Suite 305, Griffith Centre, Kingstown, st, Vincent and the Grenadines</div>
                </div>
                 <div class="globe-box-content-container">
                      <div class="globe-box-item-left">Company Code:</div>
                  <div class="globe-box-item-right">1569LLC2021</div>
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
.globe-container{
    width: 1920px;
height: 600px!important;
// background: red;
width: 100%;
        height: auto;
        background:  url('/images/bg 5.png');
        background-repeat: no-repeat;
        background-size: 100% ;
        .globe-box{
          width: 70%;
          // background: red;
          margin: 0 auto;
          /* margin-top: 10%; */
          padding: 5%;
          height: 100%;
          h1{
            text-align: center;
    color: white;

          }
          .globe-box-show-about-us{
             display: flex;
            flex-direction: row;
           
            align-items: flex-start;
            padding: 0px;
            border: 1px solid #0b0faa;
            width: 100%;
            padding: 5%;
            // height: 433px;

            background: linear-gradient(135deg, rgba(7, 63, 95, 0.28) 0%, rgba(7, 67, 101, 0.46) 100%);
            // backdrop-filter: blur(20px);
            /* Note: backdrop-filter has minimal browser support */

            border-radius: 10px;
            .globe-box-image{
                height: 300px !important;
              width: 37%;
              height: auto;
              background: url(/images/giay-phep.dbcc463d.jpg);
              background-repeat: no-repeat;
              background-size: 100% 100%;
              // background-position: 100%;
            }
            .globe-box-content-item{
              flex: 1;
              padding: 10% 5%;
              font-size: 16px;
    color: white;
              .globe-box-content-container{
                display: flex;
                flex-direction: row;
               gap: 40px;
                // gap:0 40px;
                .globe-box-item-left{
                  font-weight: 700;
                }
              }
            }
          }
        }
}
.auto-globe-gap{
  gap: 25%!important;
}
@media (max-width: 992px){
    
    .globe-container{
      height: 100%!important;
          background-size: cover!important;
      .globe-box{
        width: 100%!important;
        .globe-box-show-about-us{
          flex-direction: column!important;
          .globe-box-image{
            flex: none!important;
            width: 70%!important;
            margin: 0 auto;
                height: 26rem!important;
          }
        }
      }
    }
    .auto-globe-gap{
  gap: 27%!important;
}
}

</style>