<<img src="https://komarev.com/ghpvc/?username=robsonmt2018&label=PROFILE+VIEWS&color=00D9FF&style=for-the-badge" alt="Profile Views"/><img src="https://img.shields.io/github/followers/robsonmt2018?label=FOLLOWERS&style=for-the-badge&color=0066FF&labelColor=080B18" alt="GitHub Followers"/>
---

# Buscador de Endereços

Este é um projeto simples de uma aplicação web que permite a busca de endereços completos e suas coordenadas geográficas a partir de um número de CEP. A aplicação exibe o resultado em um formulário e também em um mapa interativo, facilitando a visualização da localização.

## Funcionalidades

* **Busca por CEP:** Insira um CEP válido para preencher automaticamente os campos de endereço (logradouro, bairro, cidade, UF).
* **Geolocalização:** Usa uma API de geocodificação para encontrar as coordenadas (latitude e longitude) do endereço e exibi-las no mapa.
* **Mapa Interativo:** O mapa é centralizado na localização do endereço buscado, com um marcador personalizado.
* **Validação de Entrada:** Verifica se o CEP inserido é válido antes de realizar a busca.

## Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias:

* **React**
* **React-Bootstrap**
* **React-Leaflet**
* **Leaflet** - utilizado para renderizar e manipular mapas interativos em aplicações web
* **API ViaCEP** - Para consulta de endereços.
* **API Nominatim (OpenStreetMap)** - Para geocodificação de endereços em coordenadas.



## Pré-requisitos

Para rodar este projeto localmente, você precisará ter o **Node.js** e o **npm** (ou yarn) instalados em seu computador.

* **Bootstrap é um kit de ferramentas front-end poderoso e repleto de recursos.**

  - https://getbootstrap.com/docs/5.3/getting-started/introduction/
 
* **Leaflet é a principal biblioteca JavaScript de código aberto para mapas interativos compatíveis com dispositivos móveis**
  - https://leafletjs.com/reference.html
    


## Install

Bootstrap
```
npm install react-bootstrap bootstrap

```
API Nominatim
```
npm install --save leaflet
```

## Como Rodar o Projeto

Siga os passos abaixo para ter uma cópia do projeto rodando em sua máquina local para fins de desenvolvimento e teste.

### 1. Clonar o Repositório

```bash
git clone [URL_DO_SEU_REPOSITORIO]
cd [NOME_DO_SEU_REPOSITORIO]
```


## Imagens

* **Quando insira CEP Invalido**
  <img width="1847" height="982" alt="image" src="https://github.com/user-attachments/assets/e1b6a021-8073-4bfc-95d0-fe1a3f2be023" />

* **Pagina Inicial do APP**
  <img width="983" height="685" alt="image" src="https://github.com/user-attachments/assets/77a36007-8f8c-4e09-89cb-e3541048b1d5" />

* **Apos Localização do CEP**
  <img width="1469" height="867" alt="image" src="https://github.com/user-attachments/assets/6dfbfdf3-a46a-4415-8c09-7ddf97ab38f7" />




