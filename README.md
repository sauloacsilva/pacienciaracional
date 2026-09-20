# 🃏 Paciência Racional - Paciência das Equivalências

Um jogo educativo e dinâmico de paciência (Solitaire) focado em **equivalências de números racionais** (frações, decimais, porcentagens e representações visuais em figuras geométricas).

Construído em HTML5, JavaScript puro (Vanilla JS), Tailwind CSS e Web Audio API (sem dependências externas pesadas ou necessidade de servidor backend).

---

## 🚀 Funcionalidades

- **4 Níveis de Dificuldade**:
  - 🟢 **Fácil (Iniciante)**: 6 famílias (24 cartas), 4 colunas no tabuleiro com todas as cartas abertas e auxílio decimal em todas as cartas.
  - 🔵 **Médio (Clássico)**: 8 famílias (32 cartas), 5 colunas de cartas com distribuição clássica e reciclagem livre do monte.
  - 🟠 **Difícil (Desafio)**: 8 famílias (32 cartas), limite de 2 reciclagens do monte e sem decimais de apoio nas cartas de figura e porcentagem.
  - 🔴 **Insano (Mestre)**: 10 famílias (40 cartas), incluindo frações impróprias e números mistos ($1\frac{1}{4}$, $\frac{3}{2}$), 6 colunas e apenas 1 reciclagem do monte.
- **⏱️ Temporizador Progressivo & Multiplicador Dinâmico**:
  - Cronômetro crescente que incentiva agilidade mental.
  - Multiplicador de tempo em tempo real: até **3.0x** para conclusões rápidas!
  - Função de Pausa (`⏸️` ou tecla `P`) com desfoque de tela.
- **📊 Painel de Estatísticas & Recordes**:
  - Salva histórico, vitórias, melhor tempo, menor número de jogadas e recorde de pontos por dificuldade no `localStorage`.
- **⚡ Auto-Completar Inteligente**:
  - Surge automaticamente quando todas as cartas restantes na mesa já estão descobertas.
- **🎨 Personalização Visual**:
  - 4 temas de feltro de mesa (Verde Cassino, Azul Oceano, Púrpura Real e Obsidiana Negra).
  - 3 opções de verso para as cartas (Azul Safira, Dourado Real e Rubi Imperial).
- **📖 Guia Educativo**:
  - Tabela completa de equivalências com frações, decimais, porcentagens e gráficos SVG.
- **⌨️ Atalhos de Teclado**:
  - `Espaço`: Comprar carta do Monte.
  - `Ctrl + Z` ou `U`: Desfazer jogada.
  - `H`: Pedir Dica pedagógica.
  - `P`: Pausar / Despausar.
  - `M`: Ligar / Desligar som sintetizado.
  - `N`: Iniciar Novo Jogo.

---

## 🎮 Como Jogar

1. Basta abrir o arquivo `paciencia.html` em qualquer navegador web moderno (Chrome, Edge, Firefox, Safari).
2. Não requer instalação ou compilação.
