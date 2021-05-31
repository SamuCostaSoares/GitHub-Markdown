### Lista de tarefa

- [x] Títulos (pelo menos 2 níveis)
- [x] Imgem (pelo menos uma imagem de banner)
- [x] Hiperlink
- [x] Listas ordenada e sem ordem
- [x] Formatação de texto em negrito e itálico
- [x] Marcar algum texto como código

# Empresa

_Vamos criar um **site** para empresa_

## Funcionalidades do site

**Tela de login, tela do produdo, catálogo**

### Linguagens do projeto:

* HTML
* CSS
* JavaScript
* MySQL

### Funcionalidades para adicionar:

1. Área de membros
    1. Login para cliente
    2. Desconto para cliente
3. Integração com outros pagamentos

### Imagem

![Logo site](https://www.hostinger.com.br/tutoriais/wp-content/uploads/sites/12/2019/08/O-que-e-site-1-768x444.png)

### Links:

[Google](https://www.google.com.br/)

[YouTube](https://www.youtube.com/?gl=BR&hl=pt)

## Código

```Javascript
function login(){
   var m = document.getElementById('caixa_email_login').value;
   var p = document.getElementById('caixa_password_login').value;
   if (m=="email" && p=="123"){
      login.style.display = "none";
   }
   else{
      window.alert("O utilizador ou a password encontram-se incorretos.");
   }
}
```





