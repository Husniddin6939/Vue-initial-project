<template>
    <section>
        <div class="container">

            <div class="left">
                <h1>Stay ahead of the curve with our forward-thinking </h1>
                <p>An award-winning SEO agency with disciplines in digital marketing, <br> design, and website development. focused on understanding you.</p>
                <div class="view">
                    <button>Schedule call <i class="bi bi-arrow-right-short"></i></button>
                    <ul><li>View Case Study</li></ul>
                </div>
                <div class="brands">
                    <small>Trusted by the world's <br> biggest brands</small>
                    <img src="/public/brand 1.svg" alt="brand">
                    <img src="/public/brand 2.png" alt="brand">
                    <img src="/public/brand 3.png" alt="brand">
                </div>

            </div>

            <div class="right">

                <div class="up">
                    <div class="img">
                        <img class="second" src="/public/black round.png" alt="img">
                        <img class="first" src="/public/intro green.png" alt="img">
                    </div>
                    <div class="card">
                        <small>230+</small>
                        <p>some big companies that we work with, and trust us very much</p>
                        <div class="line">
                            <img class="black" src="/public/black line.png" alt="img">
                            <img src="/public/slite line.png" alt="img">
                        </div>
                    </div>
                </div>
                
                <div class="down">
                    <img class="whiteback" src="/public/whiteback.png" alt="img">
                    <div class="post">
                        <h2> <div class="line"></div> Drive More Traffic and Sales </h2>
                        <h1>Drive more traffic <br> and product sales </h1>
                    </div>
                    <div class="chart">
                        <img src="/public/green charts.png" alt="chart">
                    </div>
                </div>
            </div>

        </div>
    </section>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
    section{
        padding: 0 80px;
        .container{
        margin: 0 auto;
        padding: 0;
        display: flex;
        align-items: center;
        gap: 10px;

        .left{
            width: 700px;

            h1{
                font-size: 72px;
                font-weight: 600;
                line-height: 79.2px;
                margin-bottom: 48px;
            }

            p{
                color: #878C91;
                font-size: 16px;
                font-weight: 500;
                margin-bottom: 48px;
            }

            .view{
                display: flex;
                align-items: center;
                gap: 56px;
                margin-bottom: 94px;
                
                button{
                    display: flex;
                    align-items: center;
                    padding: 22px 32px;
                    gap: 42px;
                    font-size: 16px;
                    font-weight: 700;
                    line-height: 22px;
                    background-color:black;
                    color: #fff;
                    border-radius: 70px;
                    border: none;
                    cursor: pointer;

                    &:hover{
                        color: #010205;
                        border: 1px solid #010205;
                        background-color: #fff;
                        
                    }

                    i{
                        width: 24px;
                        height: 24px;
                    }

                    
                }

                ul{
                    
                    li{
                        
                        list-style-type: none;
                        text-decoration: underline;
                        
                }
            }
            }

            .brands{
                display: flex;
                align-items: center;
                gap: 27px;

                small{
                    margin-right: 37px;
                    font-size: 14px;
                    font-weight: 600;
                    line-height: 22px;
                }
            }

        }

        .right{
            width: 588px;
            height: 547px;
            padding-top: 70px;

            .up{
                display: flex;
                align-items: center;
                gap: 24px;
                margin-bottom: 24px;
                
                .img{                    
                    position: relative;

                    .first{
                        width: 303px;
                        height: 275px;
                        object-fit: cover;
                    }
                    
                    .second{
                        position:absolute;
                        top: -50px;
                        right: -10px;
                        z-index: 9999;
                    }
                }

                .card{
                    width: 255px;
                    height: 281px;
                    background-color: #F0F0F0;
                    border-radius: 20px;
                    padding: 15px 28px;

                    small{
                        font-size: 84px;
                        font-weight: 700;
                        margin-bottom: 30px;
                    }

                    p{
                        color: #5C5D5F;
                        font-size: 16px;
                        font-weight: 500;
                        margin-bottom: 50px;
                    }

                    .line{
                        display: flex;
                        position: relative;

                        .black{
                            position: absolute;
                        }
                    }
                }
            }

            .down{
                width: 588px;
                height: 216px;
                background-color: #010205;
                border-radius: 20px;
                overflow: hidden;
                position: relative;

                .whiteback{
                    position: absolute;
                }

                .post{
                    position: absolute;
                    z-index: 99999;
                    margin: 20px 30px;

                    h2{
                        font-size: 14px;
                        font-weight: 600;
                        line-height: 18px;
                        color: #fff !important;
                        display: flex;
                        align-items: center;
                        gap: 13px;
                        top: 35px;
                        left: 40px;

                        .line{
                            width: 54px;
                            height: 0;
                            border: 1px solid #fff;
                        }


                    }
                    h1{
                        color: #fff;
                        font-size: 32px;
                        font-weight: 600;
                        line-height: 42px;
                    }
                }

                .chart{
                    position: absolute;
                    bottom: -4px;
                    right: 20px;
                }
            }




        }


    }
    }
</style>