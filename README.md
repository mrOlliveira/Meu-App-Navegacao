ao dar o commit a máquina estava logada no perfil de outro usuario do github, mas eu, murilo reis de oliveira "mrOlliveira" que desenvolvi o projeto 

# 📱 App de Navegação com Login - React Native

Este é um aplicativo React Native simples com foco em **navegação entre telas** e **login com autenticação local** usando `AsyncStorage`. O projeto inclui um fluxo de autenticação e navegação entre as telas: **Login**, **Home**, **Details** e **Profile**.

---

## ✅ Funcionalidades

* **Tela de Login:**

  * Login com usuário fixo (`admin`) e senha (`1234`).
  * Salva o estado de login usando `AsyncStorage`.
  * Redireciona automaticamente para a Home se já estiver logado.

* **Tela Home:**

  * Exibe botões para acessar as outras telas: **Details** e **Profile**.

* **Tela Details:**

  * Exibe uma mensagem.
  * Permite navegar para a tela de Profile ou voltar.

* **Tela Profile:**

  * Exibe uma mensagem.
  * Permite navegar para a tela de Details ou voltar.

---

## 💪 Tecnologias Utilizadas

* **React Native**
* **Expo**
* **React Navigation**
* **AsyncStorage** (`@react-native-async-storage/async-storage`)
* **expo-linear-gradient** (Para o fundo do Login)

---

## 🚀 Como Rodar o Projeto Localmente

### 1. Clone o repositório:

```bash
git clone https://github.com/mrOlliveira/Meu-App-Navegacao
cd Meu-App-Navegacao
```

---

### 2. Instale as dependências:

```bash
npm install
```

---
### 3. Execute o projeto:

```bash
npx expo start --tunnel
```
---

## ✅ Estrutura de Telas

```
/screens
├── LoginScreen.js
├── HomeScreen.js
├── DetailsScreen.js
└── ProfileScreen.js
```

---

## ✅ Exemplo de Fluxo de Uso:

1. **Abra o app → Tela de Login**
2. **Digite:**
   Usuário: `admin`
   Senha: `1234`
3. **Você será redirecionado para a Home**
4. **A partir da Home, navegue para Details ou Profile**

---
