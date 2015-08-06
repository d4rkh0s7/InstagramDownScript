# InstagramDownScript
##Script para guardar imagenes de Instagram

Para hacer nuestro script mas accesible crearemos un marcador en nuestra barra de favoritos de chrome/firefox con esta url (Tiene que estar todo seguido)
`javascript:javascript:str = document.getElementsByClassName("-cx-PRIVATE-Photo__placeholder")[0].getAttribute("data-reactid");for(i=0;i<10;i++){ str = str.replace("=2",":");str = str.replace("=1",".");str = str.replace(".0","");str = str.replace(".1","");str = str.replace(".2","");str = str.replace(".$","");str = str.replace(":0","");}window.open(str,"_blank");window.focus();
