# 🏥 Filipov Health Mobile — Cálculo de IMC

> Proof of Concept · Aplicativo móvel para cálculo do Índice de Massa Corporal (IMC)

[![License: MIT](https://img.shields.io/github/license/marcelofilipov/filipov-health-mobile)](https://github.com/marcelofilipov/filipov-health-mobile/blob/master/LICENSE)
[![Top Language](https://img.shields.io/github/languages/top/marcelofilipov/filipov-health-mobile)](https://github.com/marcelofilipov/filipov-health-mobile)
[![Repo Size](https://img.shields.io/github/repo-size/marcelofilipov/filipov-health-mobile)](https://github.com/marcelofilipov/filipov-health-mobile)

---

## 📋 Sumário

- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias](#tecnologias)
- [Pré-requisitos](#pré-requisitos)
- [Instalação e Execução](#instalação-e-execução)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Tabela de Classificação IMC](#tabela-de-classificação-imc)
- [Contribuindo](#contribuindo)
- [Licença](#licença)

---

## Sobre o Projeto

O **Filipov Health Mobile** é uma aplicação móvel desenvolvida como Prova de Conceito (PoC) com **React Native** e **Expo**. O objetivo é demonstrar o desenvolvimento de um app funcional para cálculo e classificação do Índice de Massa Corporal (IMC), com interface simples e responsiva para Android e iOS.

---

## Funcionalidades

- Entrada de peso (kg) e altura (cm/m)
- Cálculo automático do IMC
- Classificação do resultado conforme tabela da OMS
- Interface responsiva para Android e iOS

---

## Tecnologias

- **React Native** — framework para desenvolvimento mobile multiplataforma
- **Expo** — plataforma e toolchain para React Native
- **JavaScript** — linguagem principal do projeto

---

## Pré-requisitos

Antes de iniciar, certifique-se de ter instalado:

- **Node.js** 14 ou superior (recomendado LTS)
- **npm** ou **yarn**
- **Expo CLI**

```bash
npm install -g expo-cli
```

- Emulador Android/iOS **ou** o aplicativo **Expo Go** instalado no dispositivo físico

---

## Instalação e Execução

**1. Clone o repositório**

```bash
git clone https://github.com/marcelofilipov/filipov-health-mobile.git
cd filipov-health-mobile
```

**2. Instale as dependências**

```bash
npm install
# ou
yarn install
```

**3. Inicie o projeto**

```bash
expo start
# ou
npx expo start
```

**4. Execute no dispositivo ou emulador**

- Escaneie o QR Code com o aplicativo **Expo Go** (Android/iOS)
- Pressione `a` para abrir no emulador Android
- Pressione `i` para abrir no simulador iOS (apenas macOS)

---

## Estrutura do Projeto

```
filipov-health-mobile/
├── .expo-shared/          # Configurações locais do Expo
├── assets/                # Imagens e recursos estáticos
├── src/
│   └── components/        # Componentes React Native reutilizáveis
├── App.js                 # Ponto de entrada da aplicação
├── app.json               # Configuração do Expo (nome, ícone, splash, etc.)
├── babel.config.js        # Configuração do Babel
├── package.json           # Dependências e scripts npm
└── package-lock.json
```

---

## Tabela de Classificação IMC

A classificação segue o padrão da Organização Mundial da Saúde (OMS):

| IMC (kg/m²)       | Classificação             |
|-------------------|---------------------------|
| Abaixo de 18,5    | Abaixo do peso            |
| 18,5 – 24,9       | Peso normal               |
| 25,0 – 29,9       | Sobrepeso                 |
| 30,0 – 34,9       | Obesidade Grau I          |
| 35,0 – 39,9       | Obesidade Grau II         |
| 40,0 ou mais      | Obesidade Grau III (mórbida) |

---

## Contribuindo

Contribuições são bem-vindas. Para mudanças significativas, abra uma *issue* primeiro para discutir o que deseja alterar.

1. Faça um **fork** do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/minha-feature`)
3. Faça commit das alterações (`git commit -m 'feat: adiciona minha feature'`)
4. Faça push para a branch (`git push origin feature/minha-feature`)
5. Abra um **Pull Request**

> Por favor, certifique-se de atualizar ou adicionar testes quando aplicável.

---

## Licença

Distribuído sob a licença **MIT**. Veja [`LICENSE`](https://github.com/marcelofilipov/filipov-health-mobile/blob/master/LICENSE) para mais informações.

---

<p align="center">Desenvolvido por <a href="https://github.com/marcelofilipov">marcelofilipov</a></p>
