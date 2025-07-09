/*estilo geral do site*/

*{background-color: rgb(7, 76, 122);
    overflow: hidden;
    
}

.fotos {
    display: flex;
    gap: 30px;
    align-items: center;
    mix-blend-mode: lighten;
}
.texto {
    font-size: 50px;
    text-align: center;
    color: #fff;
    padding-right: 20px;
}
.texto2 {
    display: none
}
.botoes {
    display: none;
}
.logoCelular{
    display: none;
}
.logo {
    display: flex;
    gap: 500px;
    padding-left: 50px;
} & ul{
    align-items: center;
    padding-left: 200px;
     
} 
 .lista {
    display: flex;
    font-size: 40px;
    gap: 800px;
    color: #fff;
 }
.fotosite img {
    width: 500px;
    
}

/*resposividade para celular*/

    @media screen and (max-width : 1020px) {
        /*texto inicial */
        .texto {
         display: none;
        }
        .texto2 {
        display:inline-block;
        width: 400px;
        height: 100px;
        color: #fff;
        font-size: 20px;
        align-items:baseline;
        padding-top: 50PX;
        
        }
        /* botoes e lista cabecalho*/
       .lista {display: none;}
        .botoes {
            
            display: flex;
            padding-top: 30px;
            gap: 20px;
                 & button {
                background-color: #fff;
                border-radius: 40%;
                width: 60px;
                height: 25px;
                
                
            }
         }
         .fotosite {
            display: none;
         }
         .logoCelular {
            display: flex;
            width:180px;
            height: 100px;
         }

            .cabCelular { 
            display: flex;
            gap: 50px;
            
            
         } 
         
         
    }
