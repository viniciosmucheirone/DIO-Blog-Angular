# Criando um Blog com Angular
<h1 align="center">
    <img alt="Angular Blog" src="/img/home.png" width="300px" />
</h1>

## Descrição do Projeto

Este projeto é uma aplicação de **blog dinâmico** construída utilizando **Angular**. Foi gerado com o Angular CLI na versão 14.1.2. O objetivo principal foi criar uma plataforma simples de blog com funcionalidades essenciais como exibição de postagens, criação de novas postagens e navegação entre as páginas. A aplicação também foi projetada para ser responsiva, garantindo que o layout se ajuste a diferentes dispositivos.

### Desafios Enfrentados

Durante o desenvolvimento, enfrentei alguns desafios, incluindo:

- **Gerenciamento de estado**: Garantir que os dados das postagens estivessem atualizados e disponíveis de maneira reativa entre os componentes, o que foi feito utilizando **services** e **RxJS** para gerenciar o fluxo de dados.
  
- **Responsividade**: Implementar um design que fosse adaptável a dispositivos móveis e desktops. O uso do **Bootstrap** facilitou esse processo, mas ainda houve a necessidade de ajustes personalizados no CSS.

- **Roteamento entre páginas**: A aplicação exige uma navegação fluida entre as páginas. Configurar o roteamento de maneira eficiente para suportar múltiplas páginas de postagens foi um desafio, mas a utilização do **Angular Router** facilitou essa implementação.

O projeto é uma excelente base para quem deseja aprender mais sobre o **framework Angular** e suas práticas recomendadas.

---

## 🎯 Objetivos do Projeto

O principal objetivo deste projeto foi a criação de um **blog dinâmico** usando **Angular** para praticar e melhorar minhas habilidades com essa ferramenta. A aplicação foi estruturada com funcionalidades essenciais, como exibição de postagens, criação de novas postagens e navegação entre as páginas do blog.

Além disso, o projeto foi projetado para ser **responsivo** e fácil de usar, com um layout simples e intuitivo.

### Dificuldades Encontradas

- **Gerenciamento de estado**: Um dos maiores desafios foi garantir que os dados das postagens estivessem atualizados e corretamente sincronizados entre os componentes. Isso foi resolvido utilizando **services** e **RxJS**, que proporcionaram uma abordagem reativa e eficiente para o gerenciamento de estado.

- **Responsividade**: O design responsivo foi uma parte crítica do projeto. O uso do **Bootstrap** ajudou, mas ajustes adicionais foram necessários para garantir que o layout fosse adaptável a diferentes tamanhos de tela.

- **Roteamento entre páginas**: Configurar o roteamento de maneira fluida entre as páginas de postagens foi essencial para a navegação da aplicação. Isso envolveu o uso adequado do **Angular Router**, além de implementar links e navegação eficiente entre os componentes.

---

## 🛠️ Tecnologias utilizadas (Pré-requisitos):

- **Node.js**
- **Angular CLI**
- **Typescript**
- **HTML/CSS**
- **Bootstrap** (para o layout responsivo)

---

## 📁 Estrutura do Projeto

Aqui está uma visão geral da estrutura de diretórios do projeto:

angular-blog/ ├── src/ │ ├── app/ # Código-fonte da aplicação │ ├── assets/ # Arquivos estáticos (imagens, fontes, etc.) │ ├── environments/ # Configurações de ambiente │ ├── favicon.ico # Ícone do site │ ├── index.html # Página principal │ ├── main.ts # Arquivo principal para inicialização do Angular │ ├── polyfills.ts # Polyfills para suportar diferentes navegadores │ └── styles.css # Arquivo global de estilos CSS └── angular.json # Configurações do Angular CLI

---
 
## Funcionalidades Implementadas:

- **Exibição de postagens**: A aplicação exibe uma lista de postagens de forma dinâmica.
- **Formulários de criação de postagens**: Possibilidade de criar novas postagens através de um formulário simples.
- **Roteamento**: Navegação entre diferentes páginas de postagens e páginas do blog.
- **Responsividade**: O design da aplicação se adapta para diferentes dispositivos, garantindo uma boa experiência de uso em qualquer tela.

---

## 🖼️ Imagens do Blog

Aqui você pode adicionar capturas de tela ou imagens do seu blog em funcionamento. Exemplo:

#### 1. **Tela Principal do Blog**
<h1 align="center">
    <img alt="Tela Principal" src="img/tela_principal.png" width="600px"/>
</h1>

#### 2. **Página de Postagem**
<h1 align="center">
    <img alt="Página de Postagem" src="img/pagina_postagem.png" width="600px"/>
</h1>

#### 3. **Página de Criação de Postagem**
<h1 align="center">
    <img alt="Criação de Postagem" src="img/criacao_postagem.png" width="600px"/>
</h1>

---

## ⚙️ Como Gerar Componentes e Funcionalidades

Utilize o **Angular CLI** para gerar novos componentes, serviços ou outros artefatos:

- Para gerar um novo componente:
```bash
ng generate component nome-do-componente
```
- Para gerar um serviço:
ng generate service nome-do-serviço

- Para gerar um módulo:
ng generate module nome-do-modulo

## 🧪 Testes
Este projeto está configurado com testes unitários e de integração.

Testes Unitários
Para executar os testes unitários com Karma:
ng test

### Testes End-to-End
Para executar os testes end-to-end:
ng e2e

## 🛠️ Construção do Projeto
Para construir o projeto para produção, execute o seguinte comando:
ng build

## 🏁 Conclusão
Este projeto foi uma excelente oportunidade para praticar o uso do Angular e entender melhor sua arquitetura, incluindo como configurar rotas, criar componentes e gerenciar estado com RxJS. Embora tenha enfrentado desafios ao lidar com a responsividade e a integração do roteamento, o processo foi uma excelente forma de aprimorar minhas habilidades e aprender novas abordagens para problemas comuns em desenvolvimento web.

Com a implementação do blog, consegui integrar todos os conceitos de desenvolvimento front-end que são essenciais em muitas aplicações modernas, como design responsivo, interatividade com o usuário e boas práticas de codificação. Ao final, o projeto é uma boa base para evoluir para um sistema mais complexo no futuro.

