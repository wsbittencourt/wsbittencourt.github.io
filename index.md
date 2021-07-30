<style>

    * {
        font-size: 18px;
    }

    h1{
        font-weight: bold;
        font-size: 46px !important;
    }
    
    h2{
        font-size: 32px !important;
        margin-bottom: 10px !important;
    }
    
    #huggy, #huggy:visited, #huggy:hover{
        color: #e08;
        text-decoration: none;
        font-weight: bold;
    }
    
    #top{
        text-align: center !important;
        background-color: #444;
        padding: 120px 60px 20px;
        color: #fff;
    }
    
    #banner{
        width: 100% !important;
        height: 400px;
    }
    
    #avatar{
        display: block;
        margin: 0 auto;
        padding-top: 50px;
    }
    
    #banner{
        background: url('img/desktop.png');
        background-position: center center;
        background-repeat: no-repeat;
    }
    
    .card-left{
        background-color: #fff;
        border: 1px solid rgba(0, 0, 0, 0.12);
        box-sizing: border-box;
        border-radius: 12px 0 0 12px;
        padding: 50px;
        width: 500px;
        height: 600px;

        box-shadow:0 8px 8px -4px #bdcbd4;
        ;
    }
    
    .card-right{
        background-color: #fff;
        border: 1px solid rgba(0, 0, 0, 0.12);
        box-sizing: border-box;
        border-radius: 0 12px 12px 0;
        padding: 50px;        
        width: 500px;
        height: 600px;

        box-shadow:0 8px 8px -4px #bdcbd4;
        ;
    }
    
    #skills{
        display: flex;
        justify-content: center;
        margin-top: -30px;
        padding-bottom: 100px;
        text-align: center !important;
    }
    
    @media (max-width: 414px) {
        #avatar{
            width: 120px;
        }
    
        #top{
            padding-bottom: 60px;
        }
    
        #abstract{
            width: 100%;
            margin: 0 auto;
        }
    
        #banner{
            background: url('img/mobale.png');
            background-position: center center;
            background-repeat: no-repeat;
        }
    }
    @media (min-width: 414px) {
        #avatar{
            width: 172px;
        }
        #top{
            padding-bottom: 160px;
        }
        #abstract{
            width: 500px;
            margin: 0 auto;
        }
    }
    
    </style>
    <div id="top">
    
    <h1> Profissional de TI & Desenvolvedor de Sistemas </h1>
    
    <h2>Olá, sou o Wagner. Prazer em conhecê-lo!</h2>
        <img style="padding-bottom: 20px !important;" id="avatar" src="img/avatar.png" alt="Profile photo">
        <section id="abstract">
            Atuo como Font-end Developer na <a id="huggy" href="https://www.huggy.io/" target="_blank">Huggy</a>, sou apaixonado pelo que faço e me encanta adiquirir novas habilidades relaconadas a TI. Ao longo dos mais de 10 anos que estudo e trabalho com tecnologia, já tive o prazer de participar de projetos de pesquisas acadêmicas e realizar projetos pessoas os quais me orgulho muito, todos essas etapas do meu aprendizado pode ser conferida nesta Landing Page.
        </section>
    </div>
    
    <section id="banner"></section>
    
    <section id="skills">
        <div class="card-left">
            <img src="img/icons/tools-solid.svg" style="width: 40px">
        </div>
        <div class="card-right">
            <img src="img/icons/laptop-code-solid.svg" style="width: 50px">
        </div>
    </section>
