# 🪙 Monitor de Criptomoedas - Bitcoin (Jetpack Compose)

## 👥 Integrantes
- **Matheus Bailon** — RM: 98656  
- **Kaique Aleixo** — RM: 98627

---

## 📘 Descrição do Projeto
Este projeto é um aplicativo Android simples desenvolvido com **Jetpack Compose**, cujo objetivo é exibir em tempo real a **cotação atual do Bitcoin (BTC)**.  

A aplicação demonstra o uso de **tecnologias modernas do ecossistema Android**, com foco na construção de interfaces reativas e declarativas.  
Os dados são obtidos a partir da **API pública do [Mercado Bitcoin](https://www.mercadobitcoin.net/)**.

---

## 📱 Funcionalidades
- Consulta da **cotação mais recente** do Bitcoin (BTC).  
- Exibição do **valor da última transação** em Reais (BRL).  
- Mostra a **data e hora da última cotação**.  
- Botão **"Atualizar"** para realizar manualmente uma nova requisição à API.

---

## 🛠️ Tecnologias Utilizadas

- **[Kotlin](https://kotlinlang.org/):** Linguagem principal de desenvolvimento.  
- **[Jetpack Compose](https://developer.android.com/jetpack/compose):** Framework declarativo para criação da interface do usuário.  
- **[Material 3](https://m3.material.io/):** Biblioteca de componentes visuais (botões, barras de topo, etc.).  
- **[Retrofit](https://square.github.io/retrofit/):** Cliente HTTP usado para acessar a API do Mercado Bitcoin.  
- **[Kotlin Coroutines](https://github.com/Kotlin/kotlinx.coroutines):** Responsáveis pelo gerenciamento de operações assíncronas, como chamadas de rede.  
- **[Gestão de Estado do Compose](https://developer.android.com/jetpack/compose/state):** Utiliza `mutableStateOf` e `remember` para manter o estado da UI de forma reativa.

---

## 🔌 API Utilizada

O app faz uso da **API pública do Mercado Bitcoin**, acessando o seguinte endpoint:

https://www.mercadobitcoin.net/api/BTC/ticker/


---

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Abra o projeto no Android Studio

3. Aguarde até que o Gradle sincronize todas as dependências.

4. Execute o aplicativo em um emulador ou dispositivo físico.

