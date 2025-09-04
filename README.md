<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&color=8A2BE2&reversal=false"/>

# ☕︎︎ Assistente de Jogos

Um projeto desenvolvido no evento NLW (Next Level Week) para criar um **assistente inteligente de jogos**, que responde perguntas sobre estratégias, builds e dicas para diversos games famosos usando a API Gemini.
<p align="center">
  <img src="https://github.com/user-attachments/assets/79e858ee-fa7e-480f-8ef2-9bb041cf09b3" alt="logo" width="250"/>
</p>

## ☕︎︎ Funcionalidades

- Escolha de jogo entre mais de 30 títulos (Zelda, Witcher, Elden Ring, Minecraft, League of Legends, etc.).
- Campo para digitar sua pergunta personalizada (ex: "Melhor build para ADC").
- Integração com a API Gemini para gerar respostas em markdown.
- Respostas otimizadas, atualizadas e objetivas (até 500 caracteres).
- Interface bonita, moderna e responsiva.

## ☕︎︎ Jogos suportados (exemplos)

- The Legend of Zelda: Breath of the Wild
- The Witcher III: Wild Hunt
- Elden Ring
- Minecraft
- Fortnite
- League of Legends
- Overwatch
- Dark Souls
- E muitos outros!

## ☕︎︎ Tecnologias utilizadas

- **HTML5** para a estrutura.
- **CSS3** (com Inter fonts e gradientes) para o estilo.
- **JavaScript** para interação e integração com a API Gemini.
- [Showdown.js](https://github.com/showdownjs/showdown) para conversão de markdown para HTML.
- API Gemini (Google Generative Language API).

> ☕︎︎ **Atenção!**
> Para que o assistente funcione corretamente, **é obrigatório criar uma API Key do Gemini (Google AI)**.  
> Sem a chave, o assistente **não conseguirá gerar respostas**.

## ☕︎︎ Como criar sua API Key do Gemini

Para usar o assistente, é necessário ter uma chave (API Key) da Google Gemini (Google AI). Veja o passo a passo completo:

### 1. Crie (ou acesse) sua conta Google Cloud

- Acesse [Google AI Studio (Gemini)](https://aistudio.google.com/app/apikey) ou [Google Cloud Console](https://console.cloud.google.com/).
- Se ainda não tiver um projeto, clique em **"Select a project"** → **"New Project"** → dê um nome (ex: `nlw-agents`) → clique em **"Create"**.

### 2. Ative a API Gemini

- No menu lateral, vá em **"APIs e serviços"** → **"Biblioteca"**.
- Pesquise por **"Gemini API"** ou **"Generative Language API"**.
- Clique em **"Ativar"**.

### 3. Crie suas credenciais

- Ainda em **"APIs e serviços"**, clique em **"Credenciais"**.
- Clique em **"Criar credenciais"** → **"Chave de API"**.
- O sistema vai gerar automaticamente sua **API Key** (um código longo, algo como `AIza...`).

### 4. Copie e armazene com segurança

- Copie sua chave e **não compartilhe publicamente**.
- Use essa chave apenas em ambientes controlados. Se vazar, outras pessoas poderão usar e consumir sua cota gratuita (ou gerar custos).

### 5. Use a chave no projeto

- Abra o site do assistente.
- Cole a chave no campo **"informe a API KEY do Gemini"**.
- Escolha seu jogo, faça a pergunta e clique em **"Perguntar"**.

---

☕︎︎ **Atenção**

- A chave possui um limite gratuito, mas dependendo do uso, pode gerar custos.
- Recomenda-se usar variáveis de ambiente ou um backend para proteger a chave em produção.

---

☕︎︎ Depois de seguir os passos, você já poderá aproveitar o assistente de jogos com respostas personalizadas e atualizadas!

## ☕︎︎ Como executar

1. Clone o repositório:

   ```bash
    git clone https://github.com/MariaCampanaP/Assistemte-de-Jogos.git
    ```

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&color=8A2BE2&reversal=false&section=footer"/>

