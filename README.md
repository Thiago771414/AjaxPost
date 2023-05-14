# AjaxPost

Gerenciamento Assíncrono Simplificado para Requisições POST

# Sobre o projeto

 O projeto Ajax Post é uma implementação prática do conceito de Async Await aplicado a requisições POST utilizando o Ajax (Asynchronous JavaScript and XML). O objetivo principal é simplificar o gerenciamento de código assíncrono para envio de dados para um servidor.

Neste projeto, é demonstrado como utilizar o Async Await em conjunto com o método POST do Ajax para enviar dados assincronamente para um servidor. No código fornecido, o evento de clique em um botão dispara a função ajax(), responsável por realizar a requisição POST.

Dentro da função ajax(), é utilizado o objeto XMLHttpRequest para estabelecer a comunicação assíncrona com o servidor. O método open() configura a requisição POST para o endpoint "https://reqres.in/api/users". Em seguida, o método send() envia a requisição ao servidor.

O evento onreadystatechange é usado para monitorar o estado da requisição. Quando o valor de readyState é 4, indica que a requisição foi concluída e a resposta está pronta para ser processada. A resposta é convertida em um objeto JavaScript usando JSON.parse() e exibida no console.

Antes de enviar a requisição, o código coleta os dados inseridos nos campos de formulário nome e email e os agrupa em um objeto chamado usuario. Esse objeto é convertido em uma string JSON usando JSON.stringify() e enviado junto com a requisição POST.

Se a requisição for bem-sucedida, a resposta do servidor é exibida no console, mostrando os dados do usuário que foram enviados.

Caso ocorra algum erro durante a comunicação com o servidor, um alerta é exibido para informar o usuário sobre a falha.

Ao explorar este projeto, você terá a oportunidade de aprender como o Async Await pode simplificar o código assíncrono para requisições POST. Além disso, poderá compreender o uso do Ajax para enviar dados de forma assíncrona a um servidor e manipular as respostas retornadas.

Aproveite essa abordagem simplificada para aprimorar suas habilidades no desenvolvimento de aplicações que envolvem envio de dados assíncrono e ofereça aos usuários uma experiência mais fluída e interativa.

## Layout D3Js
![Ajax Post](https://github.com/Thiago771414/imagensProjetos/blob/main/slices/mobile/ajaxPost.png)

## Vídeo de demonstração
[[Vídeo de demonstração]](https://youtu.be/xs9wMrp3gdw)

# Tecnologias utilizadas

## Front end
- Java Script, HTML

# Sobre o Projeto
https://reqres.in/

# Autor

Thiago Reis Lima

https://www.linkedin.com/in/thiago-lima-2a5896166/
