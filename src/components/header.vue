<template>

    <header>
        <div class="left">
            <div class="icon">
           <img src="/public/headericon.svg" alt="icon">
           <h1>MAC</h1>
        </div>
        <div class="dropdown">
            <p>Service <i class="bi bi-chevron-down"></i></p>
            <p>Agency <i class="bi bi-chevron-down"></i></p>
            <p>Case study <i class="bi bi-chevron-down"></i></p>
            <p>Resources <i class="bi bi-chevron-down"></i></p>
            <p>Contact <i class="bi bi-chevron-down"></i></p>
        </div></div>
        <div class="button">
            <button>Get started</button>
            <div class="bell">
                <i class="bi bi-bell"></i>
            </div>
        </div>
    </header>

</template>


<style lang="scss" scoped>

  header{
    padding: 38px 80px;
    display: flex;
    align-items: center;
    justify-content: space-between;

    .left{
        display: flex;
        .icon{
        display: flex;
        gap: 8px;
        h1{
            font-size: 24px;
            font-weight: 700;
            color: #020407;
            margin-right: 74px;
        }
    }
    .dropdown{
        display: flex;
        gap: 33px;

        p{
            font-size: 14px;
            font-weight: 600;
            color: #020407;
            display: flex;
            align-items: center;
            gap: 7px;
            cursor: pointer;
        }
    }
    }

    .dropdown{
        p{
            font-size: 14px;
            font-weight: 600;
            line-height: 18px;
        }

    }

    .button{
        display: flex;
        align-items: center;
        gap: 9px;

        button{
            background-color: transparent;
            border: 1px solid #010205;
            border-radius: 50px;
            padding: 13px 35px;
            font-size: 16px;
            font-weight: 700;
            cursor: pointer;

            &:hover{
                background-color: #010205;
                color: #fff;
            }
        }

        .bell{
            background-color: #020407;
            color: #fff;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            place-content: center;
            text-align: center;
            cursor: pointer;
        }
    }
  }
  
</style>