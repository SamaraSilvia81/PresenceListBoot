![PresenceListBootLogo]()
# Projeto Presence List - React JS + Spring Boot Web
![Badge Concluído](http://img.shields.io/static/v1?label=STATUS&message=CONCLUÍDO&color=EA4689&style=for-the-badge)

## Deploy do Projeto 
- **Deploy:** https://app-presence-list.vercel.app/

## Criando Projeto com Spring Boot
> Ao criar um projeto utilizando o Spring Boot podemos utilizar os seguintes boilerplates:

- Comandos no Terminal
- Spring initializr

❗Dica: Boilerplates se refere a seções de código que devem ser incluídas em muitos lugares. É um template, ou seja, uma forma padrão de se escrever algo que pode ser copiado.

- **Criando o primeiro projeto com o Spring.io:** `https://start.spring.io/;`

<img alt="Symbol-Code" height="400" weigth="400" style="border-radius:150px" src="https://user-images.githubusercontent.com/100232025/236635617-4df8183e-5f5b-44d6-9217-4ea4cdfe2a11.png"> 

- Após rodar o comando acima, será criado um projeto com todas as dependências instaladas e armazenadas em um zip, ao qual você ira descompactar.

- Após isso, caso use o VSCode instale a extenção "Spring Boot Extension Pack" para configurar um ambiente pro código.

<img alt="Symbol-Code" height="400" weigth="400" style="border-radius:150px" src="https://user-images.githubusercontent.com/100232025/236635756-6637b150-ea4e-481d-ad61-a928b76ec924.png"> 

⚠️ **Dica:** Se você for executar o código na sua máquina após dar um `git clone`, é só colocar no terminal `npm install`.

## Executando Projeto

Existem duas maneiras de navegar até a pasta do seu projeto, pelo próprio terminal, utilizando o comando cd ou arrastando a pasta do projeto para dentro do VS Code.

Em seguida, será necessário baixar as dependências necessárias para a execução do projeto. Podemos utilizar o npm quanto o yarn como gerenciador de pacotes.

Certifique-se que está na pasta do projeto e execute o comando desejado:
  - `yarn install`
  - `npm install`
    
Em seguida, é preciso criar um build do seu projeto em React JS, por meio desse comando:
  - `yarn run build`
  - `npm run build`

Após a instalação das dependências e o build, é preciso que você insira o build no seu projeto em Spring Boot da seguinte forma: 

<img alt="Symbol-Code" height="400" weigth="400" style="border-radius:150px" src="https://user-images.githubusercontent.com/100232025/236635973-a5dcf311-8a76-4603-b77e-1bb8fde00385.png">

❗Dica: Antes de seguir para o próximo passo você precisar ter o JDK e o Maven instalados e configurados como variáveis de ambiente na sua máquina. Caso tenha dúvidas veja esse vídeo:

[![Watch the video](https://i.imgur.com/vKb2F1B.png)](https://youtu.be/-ucX5w8Zm8s)

Após ter feito isso você estará pronto para rodar o seguinte comando no Prompt ou CMD:
  - `mvn spring-boot:run`
    
<img alt="Symbol-Code" height="400" weigth="400" style="border-radius:150px" src="https://user-images.githubusercontent.com/100232025/236636101-1064268c-f488-4dd2-bcaf-36fef7e5818b.png">

Após executar o comando acima, abra o seu navegador e acesse o endereço: `http://localhost:8080/`

<img alt="Symbol-Code" height="400" weigth="400" style="border-radius:150px" src=https://user-images.githubusercontent.com/100232025/236636394-8352af5a-6b7c-4052-a7c2-8cc5e1f72869.png">

## Referências 

- https://dev.to/lixeletto/vite-js-o-build-tool-que-vai-facilitar-a-sua-vida-15ho 
- https://www.flaticon.com/free-icon/code_1157109?term=code&page=1&position=33&origin=search&related_id=1157109 
- https://blog.rocketseat.com.br/como-fazer-um-bom-readme/ 
- https://luby.com.br/desenvolvimento/software/tutoriais/como-criar-um-projeto-com-vite/ 
- https://gabrieluizramos.com.br/entendendo-o-package-json
