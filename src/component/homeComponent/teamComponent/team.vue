<template>
  <div class="team-container">
      <div class="team-box"  data-aos="fade-up" data-aos-anchor=".other-element">
          <h1>Team</h1>
        <div class="team-box-container auto-box-team none-slider">
            <div class="team-box-item-1 auto-layout">
                <div class="team-box-item-image"></div>
                <div class="team-box-item-text">
                    <div class="team-box-item-text-container auto-box-content">
                        Daniel Paul <strong>CEO</strong>
                    </div>
                </div>
            </div>
             <div class="team-box-item-1 auto-layout">
                <div class="team-box-item-image"></div>
                <div class="team-box-item-text">
                    <div class="team-box-item-text-container auto-box-content">
                       Alex Kurokhin <strong>Lập Trình Viên</strong>
                    </div>
                </div>
            </div>
         <div class="team-box-item-1 auto-layout">
                <div class="team-box-item-image"></div>
                <div class="team-box-item-text">
                    <div class="team-box-item-text-container auto-box-content">
                        Vincent Le Bartz <strong>Lập Trình Viên</strong>
                    </div>
                </div>
            </div>
            <div class="team-box-item-1 auto-layout">
                <div class="team-box-item-image"></div>
                <div class="team-box-item-text">
                    <div class="team-box-item-text-container auto-box-content">
                        Daniel Paul <strong>Lập Trình Viên</strong>
                    </div>
                </div>
            </div>
        </div>
        

    <!-- reponsive -->
        <div class="team-box-container auto-box-team show-slider">
            <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
            <div class="team-box-item-1 auto-layout">
                        <div class="team-box-item-image"></div>
                        <div class="team-box-item-text">
                            <div class="team-box-item-text-container auto-box-content">
                                Daniel Paul <strong>CEO</strong>
                            </div>
                        </div>
                    </div>
            </div>
        <div class="carousel-item">
        <div class="team-box-item-1 auto-layout">
                <div class="team-box-item-image"></div>
                <div class="team-box-item-text">
                    <div class="team-box-item-text-container auto-box-content">
                        Daniel Paul <strong>CEO</strong>
                    </div>
                </div>
            </div>
        </div>
        <div class="carousel-item">
        <div class="team-box-item-1 auto-layout">
                <div class="team-box-item-image"></div>
                <div class="team-box-item-text">
                    <div class="team-box-item-text-container auto-box-content">
                        Daniel Paul <strong>CEO</strong>
                    </div>
                </div>
            </div>
        </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
            
        </div>
      </div>
  </div>
</template>
<script setup>

</script>
<script>
export default {
data() {
    return {
      
    };
  },
}
</script >

<style lang="scss" scoped>

.team-container{
      background-repeat: no-repeat!important;
            background-size: 100% 100%!important;
    // position: absolute;
width: 100%;
height: 682px;
// left: 0px;
// top: 2688px;

background: radial-gradient(50% 50% at 50% 50%, rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 0.7) 100%), url('../../../../public/images/bg 3.png');
// opacity: 0.6;
.team-box{
// background: red;
    width: 80%;
    height: 516px;
    margin: 0 auto;
    /* padding: 5%; */
    /* left: 388px; */
    /* right: 372px; */
    // background: red;
    // margin: 7% 20% 10% 20%;
    /* top: 0; */
    // background: red;
    h1{
        font-family: 'IBM Plex Sans';
        font-style: normal;
        font-weight: 700;
        font-size: 32px;
        line-height: 42px;
        text-align: center;
        padding: 4%;
        /* identical to box height */


color: #FFFFFF;
    }
    .team-box-item-image{
       
    width: 100%;
    height: 96rem;
  background-repeat: no-repeat!important;
    background-size: auto;
    height: 15.5rem;

        background: url('../../../../images/Ellipse 16.png');
    }
    .team-box-item-text{
        width: 100%;
    .team-box-item-text-container{
  
    }
      
    }
}
}
.auto-layout{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 0px;
    gap: 47px;

    width: 250px;
    height: 480px;
}
.auto-box-team{
   display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    /* padding: 20px; */
    gap: 10px;
    /* width: 15rem; */
    /* height: 126px; */
    // background: linear-gradient(135deg, rgba(7, 63, 95, 0.28) 0%, rgba(7, 67, 101, 0.46) 100%);
    backdrop-filter: blur(20px);
    border-radius: 10px;
}
.auto-box-content{
   display: flex;
    border: 1px solid #0b0faa;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 10px;
    gap: 10px;
    text-align: center;
    color: #FFFFFF;
    height: 126px;
    background: linear-gradient(135deg, rgba(7, 63, 95, 0.28) 0%, rgba(7, 67, 101, 0.46) 100%);
    backdrop-filter: blur(20px);
    border-radius: 10px;
    
}
strong{
            font-weight: 700;
        }
.show-slider{
    display: none;
}

@media (max-width: 992px){
    
    .team-box-item-1{
         width: 100%!important;
         .team-box-item-image{
                 width: 67%!important;
    height: 18rem!important;
             background-size: 100% 100%!important;
         }
    }
  .show-slider{
    display: block;
    }
   .none-slider{
    display: none;
}
.auto-box-content{
      width: 60%!important;
    margin: 0 auto!important;
      height: 100%!important;
}
.auto-layout{
    gap: 20px!important;
}
}
</style>