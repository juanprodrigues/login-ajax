# login-ajax
Para este proyecto se hace el uso de AJAX, con el objetivo que el una persona se pueda registar y Logear desde una pagina y que no lo redirecione.

Ademas de ello se realizan ajustes para que sea responsive.

Las lineas de codigo importantes son las que se muestran a continuacion.
```
<script type="text/javascript">
        $(document).ready(function() {

            $("#idContenedor a").click(function() {

                var url = $(this).attr("href");

                $("#idColocar").load(url);

                return false;
            });
        });
    </script>
```


El ***#idContenerdor*** es la etiqueta que contien a ***&lt;a&gt;***, por otro lado ***#idColocar*** es donde se va a colocar el contenido que se quiere incluir.
#### [Link para visitar el proyecto](https://librerialogin.netlify.app/)
