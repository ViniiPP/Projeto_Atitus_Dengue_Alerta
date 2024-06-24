
# Projeto Dengue Alerta - API

Este projeto que tem por objetivo registrar e armazenar denúncias de focos de mosquitos da Dengue.

Este projeto foi desenvolvido em sala de aula.


## Tecnologias Usadas

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) 

![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)

![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

![Eclipse](https://img.shields.io/badge/Eclipse-FE7A16.svg?style=for-the-badge&logo=Eclipse&logoColor=white)

![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)


## **Instruções para rodar localmente**

**→ No PostgreSQL:**
- Criar um database chamado 'denguealerta';
> -  No seu código em `package src/main/resources/application.properties`:
    - Inserir a url do seu DataBase;
    - Inserir o username;
    - Inserir a senha do seu PgAdmin;

_OBS: Nesse código essa parte está comentada!_


## **Instruções para rodar na Nuvem**

Antes de tudo, esse código deve estar no seu repositório GitHub.


- **[Link do site da nuvem Railway](https://railway.app)**

### 1º Clicar em New Project:
    - 1º Passo: Clicar em Deploy PostgreSQL;
    - 2º Passo: Acessar Variables;
    - 3º Passo: Procurar por PGPORT;
    - 4º Passo: Em seu diretório "package src/main/resources/application.properties", no código "URL=Jdbc", substituir a parte: ...rlwy.net:"cola o seu PGPORT"/railway;
    - 5º Passo: Procurar por POSTGRES_PASSWORD em Variables, e substituir a senha da mesma tela acima (application.properties).


### 2º Clicar em Create:
    - 1º Acessar GitHub Repo;
    - 2º Localizar o repositório do seu projeto;
    - 3º Clicar em Deploy.

## **Minhas Redes Sociais**

- [Linkedin](https://www.linkedin.com/in/vinicius-pereira-polli17)
- [Instagram](https://www.instagram.com/eu_viniipp/)
- [Site Pessoal](https://viniipp.github.io/New-Portifolio/)





