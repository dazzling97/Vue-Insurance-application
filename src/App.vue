<template>

 <div class="Container-fluid">

<!-- ----------------Navbar--------------------- -->
<navbar></navbar>
<!-- ----------------End-Navbar--------------------- -->
 

      <div class="wraper">
      <div class="row">
      <div class="col-md-9 sm-9 lg-9">

            <div class="Weekly-review-wraper">

                  <div class="header-section">
                      <div class="weekly-header-text">
                          <h3 class="weekly-header-mainText">Weekly review summary</h3>
                          <h5 class="weekly-header-subText">Last Updated <span>2019.06.26</span> by <span>Robert perera</span> </h5>
                      </div>

                      <div class="weekly-header-button">
                          <button class="btn btn-primary btn-compare">Compare</button>
                      </div>
                  </div>



                  <div class="Middle-table-section">
                      <div class="Middle-filter-section">

                      <app-summary></app-summary>
                       
                      </div>
                  </div>



            </div>
      </div>


        <div class="col-md-3 sm-3 lg-3">
            <div class="team-leader">
                <div class="team-leader-card">

                 <img class="team-leader-main-icon" src="../src/assets/enterprise.png" width="100" height="100" alt="">

                    <div class="Team-leader-header">

                        <div class="Team-leader-profile">
                            <div class="Team-leader-image">
                                <img class="team-leader-profile" src="../src/assets/profile.jpg" width="60" height="60" alt="">
                            </div>
                        </div>

                        <div class="Team-leader-text">
                         
                            <div class="Team-leader-name"><label>R.M Roshan Perera</label></div>
                            <div class="Team-leader-position"><label>Team leader</label></div>
                        </div>
                        
                    </div>


                     <div class="Team-leader-footer">
                        <img class="team-leader-team-icon" src="../src/assets/enterprise.png" width="20" height="20" alt="">
                        
                        <div class="Team-name"><label> Team Gampaha</label></div>
                        <img class="team-leader-code-icon" src="../src/assets/shopping-bag.png" width="20" height="20" alt="">

                        <div class="Team-leader-code"><label>#001897A</label></div>
                    </div>
                   
                </div>
            </div>


<!------Meeting notes form------>
        <div class="meeting-notes">
                <h4>Meeting Notes</h4>
                 <div class="form-group">
                    <label for="exampleFormControlTextarea1">Add Meeting Notes</label>
                    <textarea class="form-control" id="exampleFormControlTextarea1" rows="6"></textarea>
                </div>

                <div class="meeting-note-btnset">
                    <button type="button" class="btn btn-outline-dark">Cancel</button>
                    <button type="button" class="btn btn-dark">Save</button>
                </div>
        </div>



      </div>




</div>
      </div>

  </div>
  

</template>

<script>

import Summary from './components/Summary'

export default {
   components:{
        "app-summary":Summary,
       
    },
}
</script>



<style lang="scss" scoped>
@import "./styles/varibles.scss";
@import "./styles/mixin.scss";


#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.wraper{
   margin:0;
   max-width:100%;
   background-color:$main-background-color;
   overflow:hidden;
}
.Weekly-review-wraper{
   margin:10px;
   max-width:100%;
   background-color:#ffff;
  @include border-radius(4px)
   

  .header-section{
    display:flex;
    padding:15px;

    .weekly-header-mainText{
        width: 300px;
        height: 18.5px;
        font-family:Roboto;
        font-size: 24px;
        font-weight: bold;
        font-style: normal;
        font-stretch: normal;
        line-height: 1.23;
        letter-spacing: normal;
        color:$primary-color;
      }

    .weekly-header-subText{
        width: 250px;
        font-family: $font-family-popins;
        font-size: 11px;
        font-weight: 300;
        font-style: normal;
        font-stretch: normal;
        line-height: 1.5;
        letter-spacing: normal;
        color: $primary-color;
        position: relative;
        top: 4px;
    }

     .weekly-header-subText span{
        color: $fame-orange;
        }

    .weekly-header-button{
        margin-left: auto;
        position: relative;
    }
   
    
  }

    .Middle-table-section{
       margin-left:15px;
       margin-right:15px;
       margin-bottom:20px !important;
       padding:10px;
       max-width:100%;
       background-color:$secondery-background-color;
       @include border-radius(4px)
        /*@include border(solid 0.3px #b7b7b7)*/
       border:solid 0.5px #b7b7b7;

    }
}

.team-leader{
    width: 100%;
    height: 150px;
    border-radius: 2.5px;
    box-shadow: 0 0 19px 0 rgba(247, 142, 30, 0.16);
    background-color: $fame-orange;
    top: 12px;
    position: relative;
    right: 4.7%;

    .team-leader-main-icon{
            position: absolute;
            top: 34%;
            opacity: 0.1;
    }

    .team-leader-profile{
        border-radius:100%;
    }
    .Team-leader-text{
        position: relative;
        left: 5%;
        top: 9px;

        .Team-leader-position{
            position: relative;
            bottom: -8%;
            font-family: Poppins;
            font-size: 12px;
            font-weight: 300;
            font-style: normal;
            font-stretch: normal;
            letter-spacing: normal;
            color: #ffffff;
        }
        .Team-leader-name{
            height: 17.5px;
            font-family: Poppins;
            font-size: 16px;
            font-weight: normal;
            font-style: normal;
            font-stretch: normal;
            letter-spacing: normal;
            color: #ffffff;
        }
      
    }
      .Team-name{
            font-family: Poppins;
            font-size: 11px;
            font-weight: 300;
            font-style: normal;
            font-stretch: normal;
            letter-spacing: normal;
            color: #ffffff;
            position: relative;
            left: -35px;
        }

        .Team-leader-code{
            font-family: Poppins;
            font-size: 11px;
            font-weight: 300;
            font-style: normal;
            font-stretch: normal;
            letter-spacing: normal;
            color: #ffffff;
        }

}

.Team-leader-header{
      display:flex; 
      position: relative;
      left: 10%;
      top: 30px;
}
 .Team-leader-footer{
     display:flex;
     justify-content:flex-end;
     position: relative;
     left: -21px;
     top: 60px;

        .team-leader-team-icon{
                position: relative;
                right: 12%;
                bottom: 4px;
        }

        .team-leader-code-icon{
                position: relative;
                right: 1%;
                bottom: 4px;
        }
    } 

    /*Meeting notes form*/
        .meeting-notes{
            border-radius: 4px;
            background-color: #ffffff;
            padding:15px;
            position: relative;
            left: -5.0%;
            top: 36px;

            .meeting-note-btnset{
                display:flex;
            }
        }     
</style>
