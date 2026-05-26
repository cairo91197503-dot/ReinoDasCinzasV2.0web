# Reino das Cinzas 🗡️

> "Quando os reinos queimam... apenas as cinzas permanecem."

RPG de ação top-down pixel art estilo Zelda SNES, jogável no browser mobile.

---

## 🎮 Como jogar

- **Joystick** (esquerda) — mover Kael
- **⚔ ATK** — espada (combo x3 = dano bônus)
- **🔥 FOGO** — bola de fogo (3 MP)
- **⚡ RAIO** — raio instantâneo no inimigo mais próximo (5 MP)
- **Teclado:** WASD/setas = mover | Z = espada | X = fogo | C = raio

---

## 🕹️ Como testar online (GitHub Pages)

1. Crie um repositório no GitHub
2. Suba o arquivo `index.html`
3. Vá em **Settings → Pages → Branch: main → Save**
4. Acesse: `https://SEU_USUARIO.github.io/NOME_DO_REPO`

---

## 🧩 Sistemas implementados

- Cinemática de abertura (8 fases)
- Mapa tile-based pixel art 32×20 (Vale Cinzento)
- Kael Ashborn com sprite detalhado, animação e marca de fogo
- Combate: espada (combo x3), bola de fogo, raio
- Inimigos: Slime, Cavaleiro das Cinzas, Arqueiro Sombrio (IA com StateMachine)
- HUD: corações HP, barra mana, ouro, nível, XP, mini-mapa
- Save automático (localStorage)
- Telas: Menu, Game Over, Vitória
- Controles touch nativos + teclado

---

## 📁 Estrutura

```
/
└── index.html   ← jogo completo em arquivo único
└── README.md
```

---

## 🛠️ Tecnologias

- HTML5 Canvas API pura
- JavaScript vanilla
- CSS mínimo
- Sem dependências externas
- 100% offline após carregado

---

## 🗺️ Roteiro (lore)

**Eldoria** está em colapso. Cinco reinos em guerra. O dragão ancestral
**Vharok** desperta sob o gelo do norte.

**Kael Ashborn**, órfão marcado por fogo negro, descobre ser descendente
dos antigos Senhores dos Dragões — o único capaz de destruir, libertar
ou controlar Vharok.

---

## 📜 Licença

MIT — livre para usar, modificar e distribuir.
