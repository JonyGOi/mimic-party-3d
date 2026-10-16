# 🎤 MIMIC PARTY 3D ONLINE 🔥
> Jogo de festa musical para navegador, inspirado em *Mimic Party* (FoliesAPP), com gráficos 3D (Three.js), personagens animados, multiplayer online P2P (WebRTC via PeerJS) e síntese de áudio pura no navegador.

---

## 🚀 Como Hospedar no seu GitHub Gratuitamente (GitHub Pages)

Você pode publicar o jogo no **GitHub Pages** em menos de 2 minutos sem precisar de servidor ou hospedagem paga!

### Passo 1: Crie um repositório no seu GitHub
1. Acesse [github.com/new](https://github.com/new).
2. Dê um nome ao repositório (por exemplo: `mimic-party-3d`).
3. Mantenha como **Público (Public)** e clique em **Create repository**.

### Passo 2: Envie os arquivos do seu computador para o GitHub
No seu terminal (na pasta deste projeto `C:\Users\Jony\.gemini\antigravity\scratch\mimic-party-br`), execute:

```bash
git add .
git commit -m "Mimic Party 3D Online: Release Inicial"
git remote add origin https://github.com/SEU-USUARIO/mimic-party-3d.git
git branch -M main
git push -u origin main
```
*(Substitua `SEU-USUARIO` pelo seu nome de usuário no GitHub).*

### Passo 3: Ative o GitHub Pages
1. No seu repositório no GitHub, clique na aba **Settings** (Configurações).
2. No menu lateral esquerdo, clique em **Pages**.
3. Em **Build and deployment** -> **Branch**, selecione `main` e a pasta `/ (root)`.
4. Clique em **Save**.

🎉 **Pronto!** Em cerca de 1 a 2 minutos, seu jogo estará online no link:
`https://SEU-USUARIO.github.io/mimic-party-3d/`

---

## 🎮 Como Jogar Online com seus Amigos

1. **Criar Sala:**
   - O anfitrião clica em **CRIAR SALA**.
   - O jogo gera um código de 5 letras (ex: `MP842`) e um link direto.
   - Clique em **COPIAR LINK DE CONVITE** e envie no WhatsApp ou Discord dos seus amigos!

2. **Entrar na Sala:**
   - Seus amigos podem clicar diretamente no link enviado ou clicar em **ENTRAR EM SALA** e digitar o código.
   - O multiplayer funciona via **WebRTC P2P (PeerJS)** diretamente entre os navegadores de todos, sem delay e sem custo de servidor!

3. **Solo contra Bots:**
   - Se estiver jogando sozinho, clique em **JOGAR SOLO (BOTS)** para disputar com 4 personagens com IA (Cap, Sangras, MrFall e Gaga).

---

## 🎭 Recursos do Jogo

- **Palco e Personagens em 3D:** Construídos com **Three.js** com iluminação de palco aconchegante, microfone cromado no centro, caixas de som e sofás.
- **Animações Procedurais:** Os personagens respiram, caminham até o microfone na sua vez de cantar, gesticulam e mexem a boca sincronizados com a voz!
- **Gravação Crua (Sem Filtros):** Utiliza `getUserMedia` com cancelamento de eco, supressão de ruído e ganho automático desligados, captando o som real.
- **Análise Vocal YIN + DTW:** A pontuação compara a melodia em semitons relativos à mediana, garantindo que vozes graves e agudas tenham a mesma chance de vitória.
- **Roleta da Discórdia:** Bônus (+20 pontos, Multiplicadores x2 e x3) e sabotagens em tempo real (Áudio com distorção, eco, voz de esquilo e **substituição do take por um som de pum sintetizado**).
- **Trilha e Efeitos 100% Sintetizados:** Toda a música e efeitos (Vine Boom, Airhorn, Trombone Triste) são gerados via Web Audio API, sem nenhum arquivo de áudio pesado para baixar.
- **Card do Campeão em PNG:** Baixe o certificado do campeão com um clique ao final da partida.
