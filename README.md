
# 🍽️ ONDE VAMOS HOJE?

**ONDE VAMOS HOJE?** é um aplicativo mobile criado para acabar com a indecisão na hora de sair para comer ou se divertir.

A ideia é simples: você informa alguns critérios básicos, clica em um botão e o app escolhe **por você** um lugar aberto, próximo e bem avaliado.

Sem perder tempo pesquisando.  
Sem discussão no grupo.  
Só abrir, clicar e ir.

---

## 🚀 Visão Geral

Muitas vezes a maior dificuldade não é sair, mas **decidir para onde ir**.  
O ONDE VAMOS HOJE? resolve essa dor usando dados públicos do Google Places e Google Maps para sugerir, de forma aleatória e inteligente, estabelecimentos próximos ao usuário.

O foco do projeto é:
- Simplicidade
- Rapidez
- Experiência sem fricção

---

## 🎯 Objetivo do MVP

- Ajudar o usuário a escolher um lugar **na hora**
- Funcionar sem login
- Android e iOS com um único código
- Utilizar localização em tempo real
- Retornar apenas **1 sugestão por vez**

---

## 🧠 Como funciona

1. O usuário permite o acesso à localização
2. Define preferências rápidas:
   - Cidade (Vitória, Serra, Vila Velha)
   - Tipo de local (restaurante, lanchonete, café, almoço)
   - Distância máxima
   - Quantidade de pessoas
3. Clica no botão **ONDE VAMOS HOJE?**
4. O app:
   - Busca locais abertos usando Google Places API
   - Filtra por avaliação e distância
   - Aplica uma lógica de escolha aleatória
5. Retorna um local com:
   - Nome
   - Avaliação
   - Distância
   - Horário de funcionamento
   - Link direto para o Google Maps

---

## 🛠️ Tecnologias Utilizadas

### Frontend
- React Native
- Expo

### Backend
- Node.js
- Express

### APIs
- Google Places API
- Google Maps API
- Google Geolocation API
- Distance Matrix API

---

## 📱 Plataformas

- Android
- iOS

---

## 🗺️ Funcionalidades do MVP

- 📍 Localização em tempo real
- 🍽️ Filtro por tipo de estabelecimento
- 📏 Filtro por distância
- 🕒 Apenas locais abertos
- 🎲 Escolha aleatória inteligente
- 🗺️ Abrir rota direto no Google Maps

---

## ❌ Fora do escopo do MVP

- Login e cadastro
- Favoritos
- Avaliações internas
- Cardápios detalhados
- Promoções
- Pagamentos

Essas funcionalidades estão previstas para versões futuras.

---

## 💡 Roadmap (ideias futuras)

- Painel para pequenos comerciantes
- Destaque patrocinado no modo aleatório
- Promoções do dia
- Histórico de escolhas
- Modo grupo (decisão coletiva)
- Expansão para outras cidades

---

## 💰 Monetização (planejada)

- Destaque pago para estabelecimentos
- Planos para pequenos negócios
- Parcerias locais

---

## 📦 Como rodar o projeto (em breve)

```bash
# instalar dependências
npm install

# rodar o app
npx expo start
