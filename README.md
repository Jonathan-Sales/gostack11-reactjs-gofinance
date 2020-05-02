<h1 align="center">Desafio 07 - GoFinances Web</h1>

## 🚀 Sobre o desafio

Essa será uma aplicação que se conecta ao backend do [Desafio 06](https://github.com/Jonathan-Sales/gostack11-nodejs-typeorm-e-upload), e exibe as transações criadas e permite a importação de um arquivo CSV para gerar novos registros no banco de dados.

### 🖥 Instalação

```shell
  /* Clonar o repositório */
  git clone https://github.com/Jonathan-Sales/gostack11-reactjs-gofinance.git

  /* Instalar as dependências */
  yarn install

  /* Iniciar a aplicação */
  yarn start
```

- Para rodar os testes execute o comando abaixo:

```shell
  yarn test
```

### Layout da aplicação

As telas de layout estão dentro da pasta layout

### Funcionalidades da aplicação

- **`Listar as transações da API`**: A página `Dashboard` exibe uma listagem através de uma tabela, mostrando os campos `title`, `value`, `type` e `category` de todas as transações que estão cadastradas na a API.

- **`Exibir o balance da sua API`**: A página `Dashboard` exibe o `balance` que é retornado do backend, contendo o total geral, junto ao total de entradas e saídas.

- **`Importar arquivos CSV`**: A página `Import` permite o envio de um arquivo no formato `csv` para o backend, que irá fazer a importação das transações para o banco de dados. O arquivo `csv` deve seguir o seguinte [modelo](https://github.com/Rocketseat/bootcamp-gostack-desafios/blob/master/desafio-database-upload/assets/file.csv).

### 📝 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/Rocketseat/bootcamp-gostack-desafios/blob/master/LICENSE) para mais detalhes.
