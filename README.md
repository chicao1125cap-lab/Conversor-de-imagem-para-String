# Conversor de Imagem → Base64

Uma aplicação web simples e minimalista para converter imagens em **Base64** diretamente no navegador.

O projeto foi desenvolvido com **HTML, CSS e JavaScript**, sem necessidade de backend ou servidor para realizar a conversão.

## ✨ Funcionalidades

* Conversão de imagens para Base64
* Suporte aos formatos:

  * JPG
  * PNG
  * WEBP
  * GIF
  * BMP
  * Outros formatos de imagem suportados pelo navegador
* Conversão da imagem para **JPG ou PNG**
* Controle de qualidade da imagem no formato JPG
* Pré-visualização da imagem convertida
* Exibição da string Base64 gerada
* Botão para copiar o Base64
* Suporte a **arrastar e soltar (Drag & Drop)**
* Interface responsiva
* Processamento totalmente local

## 🔒 Privacidade

A conversão acontece **inteiramente no navegador**.

A imagem selecionada não é enviada para nenhum servidor ou API externa. O processamento utiliza recursos nativos do navegador, como `FileReader`, `Image` e `Canvas`.

> Seus arquivos permanecem no seu dispositivo durante todo o processo.

## 🛠️ Tecnologias utilizadas

* HTML5
* CSS3
* JavaScript
* Canvas API
* FileReader API
* Clipboard API

## ⚙️ Como funciona

O usuário pode selecionar uma imagem através do botão de upload ou arrastar o arquivo para a área indicada.

Depois disso, a aplicação:

1. Valida se o arquivo selecionado é uma imagem.
2. Carrega a imagem no navegador.
3. Cria um elemento `canvas` com as dimensões da imagem.
4. Desenha a imagem no canvas.
5. Converte o conteúdo para JPG ou PNG utilizando `canvas.toDataURL()`.
6. Exibe a imagem convertida e sua representação em Base64.
7. Permite copiar o resultado para a área de transferência.

No caso do JPG, também é possível controlar a qualidade da conversão.

## 📂 Estrutura

O projeto atualmente é composto por uma página HTML contendo:

```text
conversor-base64/
└── index.html
```

A aplicação possui HTML, CSS e JavaScript integrados no mesmo arquivo para manter o projeto simples e fácil de executar.

## 🚀 Como executar

Não é necessário instalar dependências.

Basta clonar o repositório:

```bash
git clone https://github.com/SEU-USUARIO/conversor-base64.git
```

Depois, abra o arquivo `index.html` no navegador.

Também é possível publicar o projeto utilizando **GitHub Pages**.

## 🎯 Objetivo do projeto

Este projeto foi desenvolvido como uma aplicação prática para trabalhar conceitos de desenvolvimento web, manipulação de arquivos no navegador, APIs nativas do JavaScript e conversão de dados utilizando Base64.

Além da funcionalidade principal, o projeto também busca apresentar uma interface simples, responsiva e agradável para utilização.

## 📌 Possíveis melhorias

Algumas funcionalidades que podem ser adicionadas futuramente:

* Conversão de Base64 para imagem
* Download automático da imagem convertida
* Suporte a múltiplas imagens
* Exibição do tamanho original e convertido
* Histórico de conversões
* Separação do HTML, CSS e JavaScript em arquivos independentes
* Melhor tratamento de erros
* Limite de tamanho dos arquivos

## 👨‍💻 Autor

**Francisco Gonçalves Machado**

Projeto desenvolvido para prática e demonstração de conhecimentos em desenvolvimento web.

---

⭐ Se este projeto foi útil para você, considere deixar uma estrela no repositório.
