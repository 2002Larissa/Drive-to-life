# 🏎️ Drive-To-Life: Blog Automotivo Responsivo

![Status](https://img.shields.io/badge/Status-Finalizado-success?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

Uma página web de página única (Single Page Application - SPA) desenvolvida do zero com foco exclusivo em praticar e aprimorar habilidades avançadas de estilização, layout e responsividade utilizando **HTML5** e **CSS3 puros (Vanilla)**.

## 🎯 Objetivo do Projeto

O **Drive-To-Life** é um projeto de estudo simulando um blog moderno focado em esportes automobilísticos. O desafio principal foi criar uma interface atraente, elegante e totalmente responsiva, sem a utilização de frameworks (como Bootstrap ou Tailwind CSS) ou bibliotecas pré-prontas.

## 🎨 Guia de Estilização e Design

A interface foi construída para evocar velocidade, potência e modernidade, características inerentes ao mundo automotivo.

### Paleta de Cores (Tema Racing)
* ⬛ **Preto Asfalto (`#121212`):** Cor de fundo predominante, proporcionando elegância e conforto visual.
* 🟥 **Vermelho Racing (`#E63946`):** Cor de destaque utilizada para Call-to-Actions (CTAs), botões, ícones, divisores e *hover effects*. Remete à alta rotação e esportividade.
* 🔘 **Cinza Carbono (`#1E1E1E`):** Utilizado para diferenciar os *cards* do fundo, criando profundidade visual e hierarquia de leitura.

### Tipografia
Foi utilizado o Google Fonts para garantir uma apresentação limpa e legível:
* **Títulos e Destaques:** `Montserrat` (Pesos 700 e 900) - Fonte sem serifa, robusta e impactante.
* **Corpo de Texto:** `Open Sans` (Pesos 400 e 600) - Fonte projetada para excelente leiturabilidade em telas de todos os tamanhos.

## 🚀 Conceitos Técnicos Aplicados

Este projeto serviu como um laboratório prático para os seguintes conceitos:

* **CSS Flexbox e Grid Layout:**
    * Uso intensivo de `display: flex` para alinhamento da Navbar e seções de leitura profunda (Artigos).
    * Uso de `display: grid` aliado a `repeat(auto-fit, minmax())` para criar a seção de Notícias perfeitamente adaptável sem *Media Queries* complexas.
* **Mobile-First e Media Queries:** Adaptação estrutural dos componentes (como a conversão de *cards* horizontais para verticais) garantindo navegação fluida em smartphones e tablets.
* **Design System Básico:** Uso de CSS Variables (`:root`) para padronização e facilidade de manutenção das cores e fontes de todo o projeto.
* **CSS Transitions e Hover Effects:** Implementação de micro-interações, como elevação de *cards* e botões (`transform: translateY()`) e mudanças de cor suaves.
* **Imagens Placeholder Dinâmicas:** Criação de padrões de fundo via `linear-gradient` diretamente no CSS para simular o espaço das imagens durante o desenvolvimento.

## 📁 Estrutura de Pastas

```text
DRIVE-TO-LIFE/
├── CSS/
│   └── estilo.css           # Folha de estilos principal
├── index.html               # Estrutura e marcação semântica
├── main.js                  # Lógica para interações futuras
└── README.md                # Documentação