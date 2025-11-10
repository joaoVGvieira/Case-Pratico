# AutoU - Case Prático: Classificador Inteligente de E-mails

Este projeto é a solução para o case prático do processo seletivo da AutoU. 

Trata-se de uma aplicação web que utiliza a API da Cohere para classificar e-mails como "Produtivos" ou "Improdutivos" e, em seguida, sugerir respostas automáticas e contextuais.

---

## Link da Aplicação

A aplicação está hospedada na Render e pode ser acessada diretamente pelo link abaixo:

**[https://case-pratico-b5zo.onrender.com/](https://case-pratico-b5zo.onrender.com/)**

---

##  Funcionalidades Principais

* **Classificação Inteligente:** Identifica e-mails como **Produtivo** (requer ação) ou **Improdutivo** (informativo, spam, etc.).
* **Respostas Sugeridas:** Gera sugestões de respostas profissionais e adequadas ao contexto do e-mail.
* **Múltiplas Entradas:** Permite ao usuário **colar o texto** do e-mail ou fazer **upload de arquivos .txt e .pdf**.
* **Interface Moderna:**
    * Componente de upload com suporte a "arrastar e soltar".
    * Botão para **copiar a resposta sugerida** com um clique.
    * Design limpo e responsivo feito com Tailwind CSS.

---

## Tecnologias Utilizadas

* **Backend:** Python com Flask
* **Inteligência Artificial:** API da Cohere
* **Frontend:** HTML5, Tailwind CSS e JavaScript
* **Extração de PDF:** Biblioteca `pdfplumber`
* **Hospedagem:** Render
