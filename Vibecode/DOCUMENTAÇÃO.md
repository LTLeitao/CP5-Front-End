# Documentação do Projeto: Landing Page - Bloodborne (Vibecode)

## 1. Visão Geral e Conceito
Este projeto foi desenvolvido utilizando a metodologia de **Vibecoding**, onde a inteligência artificial (GitHub Copilot Pro) atuou como geradora de código a partir do direcionamento criativo, estrutural e técnico fornecido pelo desenvolvedor.

O tema escolhido foi uma landing page conceitual para o jogo **Bloodborne** (FromSoftware), explorando um design dark vitoriano e gótico.

---

## 2. Decisões de Identidade Visual (IDV)

### Paleta de Cores:
- **Obsidian Dark (`#0A0A0C`)**: Fundo principal para imersão na noite de Yharnam.
- **Card Dark (`#121217`)**: Tom ligeiramente mais claro para criação de profundidade em superfícies e containers.
- **Blood Red (`#8B0000`) & Crimson Glow (`#E63946`)**: Tons de vermelho fechado e sangrento para botões primários, destaques de texto e estados de hover.
- **Pale Bone (`#E2D9C8`)**: Tom pergaminho/osso para leitura confortável sobre o fundo escuro.
- **Gold Accent (`#C5A059`)**: Detalhes e bordas elegantes, remetendo a relicários vitorianos.

### Tipografia:
- **Títulos**: *Cinzel* (Serif) — Garante a atmosfera vitoriana, medieval e solene.
- **Corpo de Texto**: *Plus Jakarta Sans* (Sans-serif) — Garante alta legibilidade para informações de produtos, menus e formulários.

---

## 3. Registro de Prompts e Processo de Vibecode

### Prompt Inicial (Geração da Estrutura):
> *"Crie uma Landing Page completa em arquivo único HTML sobre a promoção do jogo 'Bloodborne' utilizando Tailwind CSS via CDN, fonte Cinzel para títulos, paleta dark vitoriana (#0A0A0C, #8B0000, #E2D9C8), hero section, 3 cards de destaques do jogo, grid de edições, depoimento em citação e modal de agendamento/compra funcional com JS nativo."*

### Ajustes Críticos e Refinamento (Iterações com a IA):
1. **Problema identificado na 1ª resposta**: O contraste entre o texto secundário e o fundo escuro ficou muito baixo.
   - **Correção aplicada via prompt**: *"Aumente a opacidade dos textos em cinza (`ash-grey`) de 40% para 80% usando utilitários do Tailwind para garantir acessibilidade visual (WCAG)."*
2. **Problema na funcionalidade do Modal**: O modal não fechava ao clicar fora dele.
   - **Correção aplicada via prompt**: *"Ajuste o Script nativo para que o evento de fechar ocorra tanto no botão 'X' quanto ao clicar no backdrop escuro do modal."*

---

## 4. Conclusão e Aprendizados
O uso do Vibecoding permitiu focar na **experiência visual, arquitetura da informação e direção de arte**, delegando a escrita de sintaxe repetitiva para a IA. O papel do desenvolvedor mudou de "digitador de código" para "diretor de tecnologia e design", validando a sintaxe e refinando o produto final com olhar crítico.