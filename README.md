# Opiny Docs - Documentação Oficial

Este repositório contém os ficheiros de origem da documentação oficial da **Opiny**, construída utilizando o ecossistema [Mintlify](https://mintlify.com/).

## 🚀 Estrutura do Projeto

A documentação está organizada para cobrir todas as frentes da plataforma:

* `introduction.mdx`: Visão geral e conceitos básicos.
* `/platform`: Documentação completa de utilização da plataforma.
* `/integrations`: Manuais de instalação para o SDK React (NPM), Plugin WordPress e Script HTML.
* `/mcp`: Configuração do Servidor MCP para integração com o Claude Desktop e outros agentes de IA.
* `/api-reference`: Guia de autenticação e documentação técnica dos endpoints de Pesquisas e Respostas.

## 🛠️ Desenvolvimento Local

Para pré-visualizar as alterações localmente antes de as enviar para produção, siga estes passos:

### 1. Instale a CLI do Mintlify

```bash
npm i -g mintlify
```

### 2. Inicie o servidor de desenvolvimento

Navegue até à pasta raiz do projeto e execute:

```bash
mintlify dev
```

A documentação ficará disponível em http://localhost:3000. O Mintlify atualizará a página automaticamente sempre que gravar um ficheiro.

## ⚙️ Configuração
O ficheiro central de configuração é o mint.json. Nele pode ajustar:

- A estrutura de navegação lateral.

- A paleta de cores (Primária, Light e Dark).

- Os logótipos e favicons.

- As definições da API (Base URL e método de autenticação).

## 📄 Notas de Edição
Todos os ficheiros de conteúdo devem utilizar a extensão .mdx.

Utilize os componentes do Mintlify como <CardGroup />, <Tip /> e <ParamField /> para manter a consistência visual.

Garanta que qualquer alteração na estrutura de ficheiros seja refletida no array de navegação do mint.json.

***Opiny***