# Automation Python Web Scrapping IPV6

## Sobre o Projeto

Esta aplicação foi desenvolvida em **Python** utilizando o framework **Django** e a biblioteca **Playwright**. Seu objetivo é realizar **web scraping** em um site para obter **logs de conexão** a partir de um endereço **IPv6**. O projeto inclui uma interface de documentação **Swagger**, que facilita a interação com as rotas da API.

---

## Tecnologias Utilizadas

- **Python 3.12**
- **Django**: Framework para o desenvolvimento da aplicação web.
- **Playwright**: Biblioteca para automação de navegadores.
- **Swagger**: Interface para documentar e testar as rotas da API.
- **PostgreSQL**: Banco de dados para persistência.
- **Docker**: Ambiente isolado para execução da aplicação.

---

## Funcionalidades

- Extração de logs de conexão por meio de scraping utilizando Playwright.
- Endpoints expostos para consumir e gerenciar os dados:
  - **Consultar IPv6**: Busca logs de conexão associados a um endereço IPv6.
  - **Gerenciar Logs**: Adiciona, lista e manipula os dados extraídos.
- Documentação interativa disponível via Swagger.

---

## Requisitos

Antes de começar, certifique-se de ter:

- **Python 3.12+**
- **Docker** e **Docker Compose** instalados.
- Um navegador suportado pelo **Playwright**.
- Configuração do banco de dados PostgreSQL.

---

## Configuração e Execução

1. **Clone o Repositório**

   ```bash
   git clone https://github.com/jeffemart/automation-python-web-scrapping-ipv6.git
   cd automation-python-web-scrapping-ipv6
