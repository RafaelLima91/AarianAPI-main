# 🚀 Projeto de Automação API com Ruby e Cucumber

Projeto de automação em API Post e Get utilizando Ruby e Cucumber.

## 📦 Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas antes de começar:

- [Ruby](https://www.ruby-lang.org/) 🧩
- [Bundler](https://bundler.io/) 📦
- [Cucumber](https://cucumber.io/) 🥒

## 🔧 Instalação 

1. Clone este repositório:

```shell
git https://github.com/RafaelLimaSilva91/AarinAPI
cd AarinAPI
```

2. Instale a gem do bundler e na sequencia as dependências Ruby:

```shell
gem install bundler
bundle install
```

## 📁 Estrutura de Diretórios 

- `features/` - Armazena os arquivos `.feature` com cenários de teste.
- `step_definitions/` - Contém os passos de teste implementados em Ruby.
- `support/` - Inclui configurações e utilitários para o projeto.
- `reports/` - Onde relatórios de execução são gerados (opcional).
- `Gemfile` - Lista de dependências Ruby.

## ⚙️ Configuração 

Certifique-se de configurar seu ambiente. Isso pode ser feito no arquivo `support/env.rb`.

## ▶️ Executando os Testes 

Para executar os todos os testes, simplesmente use o seguinte comando:

```shell
cucumber
```

Após a execução acessar o report html que foi gerado na pasta "reports"
