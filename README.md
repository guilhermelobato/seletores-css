# Trabalhando com seletores CSS
Atributos de seleção em css para otimizar customização da página

    /* 1 - Seletor para o primeiro li - color:red	*/
    li:first-child a{
    	color:red;
    }
    
    /* 2 - Seletor para o href que termine com .br -  color:green	*/
    
    a[href$=".br"]{
    	color:green;
    }
    
    
    /* 3 - Seletor para o 4 li - color: blue;	*/
    
    li:nth-child(4) a{
    	color:cyan;
    	border:solid 1px #000
    }
