# 🏗️ Construtor Master — O Jogo da Obra

## Sobre o Projeto
Plataforma web interativa e educativa com um jogo de múltipla escolha sobre construção civil. O jogador, guiado pelo **Mestre André** (assistente virtual de manutenção), precisa escolher os equipamentos e materiais corretos em cada fase de uma obra, até construir uma casa completa.

---

## ✅ Funcionalidades Implementadas

- **Tela inicial** com apresentação do Mestre André e prévia das 10 fases
- **10 fases sequenciais** cobrindo todo o ciclo de construção de uma casa
- **Perguntas de múltipla escolha** com 3 opções por pergunta (embaralhadas a cada partida)
- **Mestre André** orientando o jogador com dica antes de cada pergunta
- **3 vidas** — o jogador perde vida a cada erro
- **Sistema de pontuação** (+100 pts por acerto)
- **Feedback imediato** (correto/errado) com explicação técnica
- **Progressão visual da casa** em SVG no painel lateral
- **Barra de progresso** da obra
- **Ranking final**: S / A / B / C com título correspondente
- **Confetti** ao acertar as respostas
- **Tela de Game Over** se perder todas as vidas
- **Tela de conclusão** com estatísticas (pontuação, acertos, vidas restantes)
- **Design responsivo** para desktop e mobile

---

## 🏠 Fases do Jogo (LocExpress)

Sequência baseada no infográfico oficial **Fases da Obra – LocExpress**:

| # | Fase | Equipamento Correto |
|---|------|-------------------|
| 1 | 🏕️ Canteiro de Obras | Gerador de Energia |
| 2 | 🏗️ Fundação — Perfuração | Trado Motorizado (Perfuratriz) |
| 3 | 🏗️ Fundação — Concretagem | Betoneira |
| 4 | 💥 Demolição | Martelete Rompedor Elétrico |
| 5 | 🔩 Estrutura | Torre de Andaime |
| 6 | 🧱 Alvenaria | Serra Mármore (Cortadora) |
| 7 | ⚡ Instalações | Martelete / Furadeira de Impacto |
| 8 | 🪨 Piso de Concreto | Alisadora de Concreto (Helicóptero) |
| 9 | 🎨 Acabamento | Lixadeira / Politriz |
| 10 | 🌿 Jardinagem e Limpeza | Cortador de Grama / Roçadeira |

---

## 📂 Estrutura de Arquivos

```
index.html    → Arquivo principal com todo o jogo (HTML + CSS + JS integrados)
README.md     → Documentação do projeto
```

---

## 🚀 Como Acessar

- Arquivo principal: `index.html`
- Para publicar: use a aba **Publish** para gerar o link público

---

## 🔧 Próximos Passos Sugeridos

1. Adicionar mais fases (segurança do trabalho, EPI, manutenção predial)
2. Implementar níveis de dificuldade (Fácil / Médio / Difícil) com multiplicador de pontos
3. Adicionar banco de questões com rotação aleatória
4. Criar módulo de ranking com tabela de líderes (via API)
5. Personalizar com identidade visual da empresa
6. Adicionar efeitos sonoros e trilha sonora
7. Criar tela de login para rastrear progresso por usuário
8. Exportar certificado de conclusão em PDF
