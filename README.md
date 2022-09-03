<div class="readme">
    <div class="logo-container">    
        <div class="logo">
            <img src="murasaki-logo.png">
        </div>
        <div class="title">
            <h1> Murasaki </h1>
        </div>
    </div>
    <div class="content">
        <p class="description"> 
            Murasaki es un gestor pensado para facilitar el labor de los profesores a cargo de la institución al proporcionar una mejor gestión sobre la información de sus alumnos, sus tareas, sus fortalezas y los informes de pago.
        </p>
        <div class="btns">
            <a href="https://github.com/gonzaloVeron/Murasaki-Frontend" class="btn">Frontend</a>
            <a href="https://github.com/gonzaloVeron/Murasaki-Backend" class="btn">Backend</a>
        </div>
    </div>
</div>

<style>

    a {
        text-decoration: none;
        color: initial;
    }

    .description{
        display: flex;
        justify-content: center;
        align-items: center;
        font-size: 20px;
    }

    .btns{
        display: flex;
        align-items: center;
        justify-content: space-around;
        margin-top: 3%;
    }

    .readme{
        width: 100vw;
        height: 100vh;
    }

    .logo-container {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }

    .title{
        margin-top: 2%;
    }

    .logo{
        width: 150px;
        height: 150px;
    }

    .content{
        margin-top: 3%;
        flex-direction: column;
    }

    .mr-1{
        margin-right: 1%;
    }

    a.btn {
        -webkit-appearance: button;
        -moz-appearance: button;
        appearance: button;

        color: white;

        background-color: hsl(310deg 51% 43%);
        border: none;
        
        padding: 15px 32px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        cursor: pointer;
        border-radius: 5px;
        transition-duration: 0.4s;
    }

    .btn:hover {
        box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);
    }
</style>