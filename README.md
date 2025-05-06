# 🗺️ Mapty - Planejador de Corridas e Ciclismo

<p align="center">
  <img src="https://img.shields.io/badge/Projeto-Mapty%20App-yellow?style=for-the-badge&logo=javascript&logoColor=white" />
  <img src="https://img.shields.io/badge/Certificado-Incompleto-orange?style=for-the-badge&logo=graduation-cap&logoColor=white" alt="Certificado do Curso" />
  <a href="https://www.udemy.com/course/the-complete-javascript-course/">
    <img src="https://img.shields.io/badge/Curso%20Udemy-Javascript%202025-blueviolet?style=for-the-badge&logo=udemy&logoColor=white" alt="Curso Udemy" />
  </a>
</p>

Este é o projeto **Mapty**, um app de mapeamento interativo que permite registrar treinos de corrida e ciclismo diretamente sobre o mapa. Foi desenvolvido durante o curso **The Complete JavaScript Course 2025** como prática dos conceitos mais avançados de JavaScript, OOP, arquitetura de projeto e armazenamento local.

## 🚀 Sobre o Projeto

O Mapty utiliza a biblioteca **[Leaflet.js](https://leafletjs.com/)** para renderização de mapas, captura a geolocalização do usuário e permite registrar treinos físicos com informações como distância, duração, ritmo ou velocidade.

### 🧩 Funcionalidades Principais

- 📍 Geolocalização automática e renderização do mapa.
- 🏃‍♂️ Registro de treinos de **corrida** com _cadência_ e cálculo automático de _pace_.
- 🚴‍♀️ Registro de treinos de **ciclismo** com _elevação_ e cálculo automático de _velocidade_.
- 💾 Armazenamento dos treinos no **Local Storage** do navegador.
- 🔁 Renderização automática dos treinos salvos ao recarregar a página.
- 🗺️ Marcadores personalizados no mapa com popups descritivos.
- 🧭 Navegação até o local do treino ao clicar no item da lista.

## 🧱 Arquitetura do Código

O código segue o paradigma de **Programação Orientada a Objetos**, com ênfase em reutilização e encapsulamento:

- `Workout` (classe base): Define os atributos e métodos comuns.
- `Running` e `Cycling`: Herdam de `Workout` e implementam métodos específicos.
- `App`: Classe principal responsável por controlar todo o fluxo da aplicação, desde o carregamento do mapa até a manipulação de eventos e dados persistidos.

### 💡 Bibliotecas Utilizadas

- **Leaflet.js** - Biblioteca JavaScript moderna de código aberto para mapas interativos. Utilizada para renderizar o mapa e os marcadores personalizados dos treinos.

## 🔧 Instruções para Resetar os Dados

Caso deseje **apagar todos os treinos salvos**, abra o console do navegador (F12) e execute:

```js
app.reset();
```

Isso irá **limpar o Local Storage** e recarregar a página.

## 📚 Conceitos e Técnicas Utilizadas

Este projeto consolida diversos conhecimentos práticos em JavaScript moderno:

- 📦 **Classes e Herança ES6**
- 📍 **Geolocalização via `navigator.geolocation`**
- 💡 **Encapsulamento com campos privados (ES2022)**
- 🏗️ **Arquitetura baseada em OOP**
- 🗃️ **Persistência com `localStorage`**
- 📌 **Manipulação de DOM com Event Listeners**
- 🌍 **Integração com Leaflet.js**
- 🔃 **Conversão de dados (serialização/deserialização)**

Este projeto foi uma excelente prática para consolidar habilidades de **JavaScript moderno**, **design de arquitetura de software** e **trabalho com APIs externas**. Ele representa um marco importante no meu aprendizado, especialmente no que diz respeito ao domínio da **OOP na prática**.
