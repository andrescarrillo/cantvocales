cantvocales
===========

voc
// cuantas vocales hay en una palabra

	widos.onload=funtion ()

	{
		var palabra;
		function Cantvocales(palabra)

  		{
   		 var m;
    		 var cant=0;
   		 for(m=0;m<palabra.length;p++)
    			{
     			if(frase.charAt(m)=='a' ||
          		palabra.charAt(m)=='e' ||
          		palabra.charAt(m)=='i' ||
         		palabra.charAt(m)=='o' ||
         		palabra.charAt(m)=='u' || 
          		palabra.charAt(m)=='A' ||
          		palabra.charAt(m)=='E' ||	
         		palabra.charAt(m)=='I' ||
         		palabra.charAt(m)=='O' ||
         		palabra.charAt(m)=='U')
    		  	
				{
      		 		 cant++;
     				 }
  			  }
   		 document.write('Cantidad de vocales:'+cant);
 		 }
			
	palabra=prompt('Ingrese una palabra :','');
	Cantvocales(palabra);
