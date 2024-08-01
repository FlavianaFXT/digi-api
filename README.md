# digi-api - *Buscando digimons*

Projeto Javascript desenvolvido na Semana 11 do curso de Front End da {reprograma}, que consiste em buscar digimons utilizando requisição de API.

# Indice

- [APRESENTAÇÃO](#APRESENTAÇÃO)
- [DESCRIÇÃO DO PROJETO](#Descrição-Do-Projeto)
- [TECNOLOGIAS UTILIZADAS](#Tecnologias-Utilizadas)
- [PASSO A PASSO UTILIZADO](#Passo-A-Passo-Utilizado)
- [FUNCIONALIDADES IMPLEMENTADAS](#Funcionalidades-Implementadas)
- [IMPLEMENTAÇÕES FUTURAS](#Implementações-Futuras)
- [COMO RODAR O PROJETO](#Como-Rodar-O-Projeto)
- [CONFIRA O RESULTADO ](#Confira-O-Resultado)


# APRESENTAÇÃO

### Quem é Flaviana?

![image](https://github.com/FlavianaFXT/ProjetoFinal-reprograma/assets/113718720/1e13d5e7-b1b4-4701-a689-ec293ec77ea1)

Flaviana Ferraz é uma sertaneja de Pernambuco morando no sertão da Paraiba, formada em Gestão Ambiental e Mestre em Recursos Hídricos. Após mais de 10 anos de formada, aos 34 anos, decidiu fazer transição de carreira. Hoje trilhando persistentemente os caminhos que levam à carreira de FrontEnd Developer.

### Contatos

- [E-mail](flaviferraz@yahoo.com.br)
- [LinkedIn](https://www.linkedin.com/in/flaviana-ferraz-frontend)
- [GitHub](https://github.com/flavianafxt)

# DESCRIÇÃO DO PROJETO

## 🧠 Contexto

Utilizando o método fetch para consumir o endpoint da Digimon API [VER AQUI API DIGIMON](https://digimon-api.vercel.app/) que retorna um digimon pelo seu nome, deixando a usuária entrar com o nome de um digimon e ao clicar num botão, as informações do digimon são carregadas! A página mostra uma lista com os nomes dos digimons para a usuária, o que foi feito através do endpoint que retorna todos os digimons.

![image](https://github.com/FlavianaFXT/digi-api/assets/113718720/a2681fe5-7a88-4637-b6f3-cd7845e5010b)

![image](https://github.com/FlavianaFXT/digi-api/assets/113718720/2a61d9ea-7ac8-48a7-8bdc-8b5f9d52c109)


## 🧠 Estrutura do projeto

### Páginas do Projeto

O projeto é constituído de 1 página, que contém o cabeçalho, o campo de busca por nome, todos os nomes dos digimons e, ao clicar em um nome de digimon, o campo lateral em que aparece o card do digimon selecionado, com a imagem, Nome e Level.


### Estrutura de Pastas

![image](https://github.com/FlavianaFXT/digi-api/assets/113718720/a0681370-a14b-4284-a2e7-6677ff1beb0b)


# TECNOLOGIAS UTILIZADAS

| Ferramenta | Descrição |
| --- | --- |
| `Javascript` | linguagem de programação|
| `método fetch` | método utilizado na linguagem Javascript para consumo de API|
| `Git` | Gerenciador de vercionamento|
| `Github` | Hospedagem do código fonte integrado com gerenciador de versionamento|
| `Netlify` | deploy do projeto|

# PASSO A PASSO UTILIZADO

1️⃣ Criação de repositorio no github e clone na maquina em que trabalhei no projeto através do Git Bash
2️⃣ Criação da página, com seus elementos e estilização
3️⃣ Implementação dos eventos, mecanismos de busca e consumo a API, através de funções e métodos javascript
5️⃣ Adicionar todas as modificações a cada etapa e subir no GitHub

 ```bash
 git add .
 ```
 ```bash
 git commit -m "comentario"
```
 ```bash
 git push
```

6️⃣ Deploy do projeto no Netlify

# FUNCIONALIDADES IMPLEMENTADAS

✔️ Renderização dos nomes dos digimons na página, consumindo a API dos digimons.

✔️ Evento de clique no botão de cada nome de digimon

✔️ Consumo de APi e renderização do card com as informações do digimon escolhido pelo usuário


#  IMPLEMENTAÇÕES FUTURAS

-[ ✖️ ] Mecanismo de Busca de Digimon por nome


# COMO RODAR O PROJETO

Para rodar esse projeto em sua máquina, siga os passos a seguir:

1️⃣ Realize o fork desse repositorio

2️⃣ Clone na sua máquina

3️⃣ Entre no diretório do repositorio clonado, no arquivo index.html

4️⃣ Por fim rode o projeto:

clique com o direito do mouse no arquivo `index.html` e em:

```bash
                           Abrir com o Live Server
```

O navegador será aberto automaticamente.

  
# CONFIRA O RESULTADO [AQUI](https://digimons-list.netlify.app/)


