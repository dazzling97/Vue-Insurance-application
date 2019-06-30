<template>
   <div class="summary-filter-section">
        <div class="summary-filter-border">
            <div class="row">
                
                <!-------------Filter section---------->
                <div class="col-md-3">
                    <div class="summary-color-identify">
                        <div class="summary-target">
                                <img class="summary-target-rectangle" src="../assets/rounded-rectangle-target.png" width="30" height="26" alt="">
                                <h6 class="summary-target-text">Target</h6>
                        </div>
                        <div class="summary-actual">
                               <img class="summary-actual-rectangle" src="../assets/rounded-rectangle-actual.png" width="30" height="26" alt="">
                                <h6 class="summary-actual-text">Actual</h6>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-9">
                    <div class="date-filter">
                        <div class="date-filter-from">
                             <h6 class="date-filter-text">From</h6>
                             <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="DD:MM:YYYY">
                        </div>

                         <div class="date-filter-to">
                            <h6 class="date-filter-text">To</h6>
                             <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="DD:MM:YYYY">
                        </div>

                        <div class="date-filtert-button">
                            <button type="button" class="btn btn-outline-dark btn-filter">Filter</button>
                        </div>


                    </div>
                </div>

            </div>
        </div>  


        <!--------Summery table---------->
<div class="row">
    <div class="col-md-12">

        <div class="summery-table">
            <div class="summery-table-style">
                <table>
                        <tr>
                            <td>Criteria</td>
                            <td>Week 1</td>
                            <td>Week 2</td>
                            <td>Week 3</td>
                            <td>Week 4</td>
                            <td>Total</td>
                        </tr>
                        <tr>
                            <td>Recruitment </td>
                            <td>B2</td>
                            <td>C2</td>
                            <td>A2</td>
                            <td>B2</td>
                            <td>C2</td>
                        </tr>
                        <tr>
                            <td>Quotations </td>
                            <td>A3</td>
                            <td>A3</td>
                            <td>A3</td>
                            <td>A3</td>
                            <td>A3</td>
                        </tr>
                        <tr>
                            <td>Active advisors </td>
                            <td>B1</td>
                            <td>C1</td>
                            <td>A1</td>
                            <td>B1</td>
                            <td>C1</td>
                        </tr>
                        <tr>
                            <td>Pending clearance</td>
                            <td>B2</td>
                            <td>C2</td>
                            <td>A2</td>
                            <td>B2</td>
                            <td>C2</td>
                        </tr>
                        <tr>
                            <td>Meeting Notes</td>
                                <td>
                                    <ol>
                                        <li>Proposals : 3</li>
                                        <li>Suspense : 250,000</li>
                                        <li>Renewals : 120, 000</li>
                                        <li>Revivals : 25,000</li>
                                    </ol>
                                </td>
                                
                            <td><ol>
                                        <li>Proposals : 3</li>
                                        <li>Suspense : 250,000</li>
                                        
                                    </ol></td>
                            <td><ol>
                                        <li>Proposals : 3</li>
                                        <li>Suspense : 250,000</li>
                                        <li>Renewals : 120, 000</li>
                                        <li>Revivals : 25,000</li>
                                    </ol></td>
                            <td><ol>
                                        <li>Proposals : 3</li>
                                        <li>Suspense : 250,000</li>
                                        <li>Renewals : 120, 000</li>
                                       
                                    </ol></td>
                            <td><ol>
                                        <li>Proposals : 3</li>
                                        <li>Suspense : 250,000</li>
                                       
                                    </ol></td>
                        </tr>
                        <tr>
                            <td>Actions</td>
                            <td><div class="btn-group">
  <button type="button" class="btn btn-outline-danger dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    Action
  </button>
  <div class="dropdown-menu">
    <a class="dropdown-item" href="#">Action</a>
    <a class="dropdown-item" href="#">Another action</a>
    <a class="dropdown-item" href="#">Something else here</a>
    <div class="dropdown-divider"></div>
    <a class="dropdown-item" href="#">Separated link</a>
  </div>
</div></td>
                            <td><div class="btn-group">
  <button type="button" class="btn btn-outline-success dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    Action
  </button>
  <div class="dropdown-menu">
    <a class="dropdown-item" href="#">Action</a>
    <a class="dropdown-item" href="#">Another action</a>
    <a class="dropdown-item" href="#">Something else here</a>
    <div class="dropdown-divider"></div>
    <a class="dropdown-item" href="#">Separated link</a>
  </div>
</div></td>
                            <td><div class="btn-group">
  <button type="button" class="btn btn-outline-warning dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    Action
  </button>
  <div class="dropdown-menu">
    <a class="dropdown-item" href="#">Action</a>
    <a class="dropdown-item" href="#">Another action</a>
    <a class="dropdown-item" href="#">Something else here</a>
    <div class="dropdown-divider"></div>
    <a class="dropdown-item" href="#">Separated link</a>
  </div>
</div></td>
                            <td><div class="btn-group">
  <button type="button" class="btn btn-outline-success dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    Action
  </button>
  <div class="dropdown-menu">
    <a class="dropdown-item" href="#">Action</a>
    <a class="dropdown-item" href="#">Another action</a>
    <a class="dropdown-item" href="#">Something else here</a>
    <div class="dropdown-divider"></div>
    <a class="dropdown-item" href="#">Separated link</a>
  </div>
</div></td>
                            <td><div class="btn-group">
                                <button type="button" class="btn btn-outline-danger dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                    Action
                                </button>
                                <div class="dropdown-menu">
                                    <a class="dropdown-item" href="#">Action</a>
                                    <a class="dropdown-item" href="#">Another action</a>
                                    <a class="dropdown-item" href="#">Something else here</a>
                                    <div class="dropdown-divider"></div>
                                    <a class="dropdown-item" href="#">Separated link</a>
                                </div>
                                </div>

                    </td>
                        </tr>
                        
                    </table>
            </div>
        </div>  




    </div>
</div>

        
    </div>


    
</template>




<script>



export default {
   components:{
       
    }
}
</script>


<style lang="scss" scoped>
@import "../styles/varibles.scss";
@import "../styles/mixin.scss";


/*---------------summary-filter style--------------*/ 

.summary-filter-border{
        max-width: 97.5%;
        background-color:rgba(244, 244, 250, 0.55);
        @include border-radius(4px)
        /*@include border(solid 0.3px #b7b7b7)*/
        border:solid 0.5px #d6d6ee;
        position: relative;
        left: 1.5%;
        top: 11px;
}

.summary-color-identify{
    display:flex;
    padding:10px;

    .summary-target-text{
        font-family: Poppins;
        font-size: 12px;
        font-weight: normal;
        font-style: normal;
        font-stretch: normal;
        letter-spacing: normal;
        color: $target-box-color;
         margin-top:5px;
        margin-left:10px;
         margin-right:7px;
    }

    .summary-actual-text{
        font-family: Poppins;
        font-size: 12px;
        font-weight: normal;
        font-style: normal;
        font-stretch: normal;
        letter-spacing: normal;
        color:$actual-box-color;
        margin-top:5px;
        margin-left:10px;
        margin-right:7px;
    }

    .summary-target{
        display:flex;
        border-radius: 4px;
        border: solid 0.6px $target-border-color;
        background-color: #ffffff;
        padding:5px;
       
    }

    .summary-actual{
        margin-left:20px;
        display:flex;
        border-radius: 4px;
        border: solid 0.6px $actual-border-color;
        background-color: #ffffff;
        padding:5px;
    }
}

/*---------------date filter style--------------*/

.date-filter{
     display:flex;
     position:relative;
     top:11px;
     left: 11%;

    .date-filter-from{
         display:flex;
    }
    .date-filter-to{
        display:flex;
    }
    .date-filter-text{
        position:relative;
        top:8px;
        margin-left:20px;
        margin-right:30px;
        font-family: Poppins;
        font-size: 14px;
        font-weight: medium;
        font-style: normal;
        font-stretch: normal;
        line-height: 1.56;
        letter-spacing: normal;
        color: $primary-color;

    }
    .date-filtert-button{
        margin-left:30px;

    }

    .btn-filter{
         border-radius: 1.5px;
        @include box-shadow(rgba(19, 38, 57, 0.14))
         border: solid 0.5px $primary-color;
         padding-left:24px;
         padding-right:24px;
        
    }

}

/*---------------summery table style--------------*/

.summery-table{
        max-width:100%;
        margin-top:20px;

        table {
                border-collapse: collapse;
                width: 97.7%;
                position: relative;
                margin-top: 30px;
                left: 1.4%;     
                }
        .tr , td{
                width: 97.1px;
                height: 27.6px;
                border-radius: 5px;
                border: solid 15px #ffff;
                background-color: #f9f9fc;
                padding:10px;
                margin:10px;
        }
        
    
}

</style>
