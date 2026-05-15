#  Nome do Jogo

> Jogo desenvolvido para a Game Jam 2026 com o tema:
> **Bioparque Pantanal — Campo Grande/MS**

---

#  Sobre o Projeto

Este projeto está sendo desenvolvido durante uma Game Jam utilizando a Unreal Engine 5.

O jogo será focado em:
- Multiplayer local cooperativo
- Gameplay casual e rápido
- Temática inspirada no Bioparque Pantanal
- Cooperação entre jogadores
- Experiência divertida e acessível

---

#  Gênero

- Coop Local
- Multiplayer Couch Co-op

---

#  Conceito

Os jogadores devem trabalhar juntos para resolver desafios inspirados no ecossistema do Pantanal e do Bioparque Pantanal.

O foco principal é:
- cooperação
- comunicação
- resolução de puzzles
- interação ambiental

---

#  Engine

- Unreal Engine 5

---

#  Equipe

| Integrante | Função |
|---|---|
| João | Líder /  |
| Integrante 2 |  |
| Integrante 3 |  |
| Integrante 4 |  |

---

#  Cronograma

## Sprint 1 — Protótipo
 14/05 → 20/05

Objetivos:
- Estrutura do projeto
- Multiplayer local
- Mecânica principal
- Primeira arena jogável

---

## Sprint 2 — Conteúdo
 21/05 → 25/05

Objetivos:
- Fases
- UI
- Áudio
- Feedback visual
- Melhorias de gameplay

---

## Sprint 3 — Polish & Build Final
 26/05 → 30/05

Objetivos:
- Correção de bugs
- Otimização
- Build final
- Entrega da Game Jam

---

#  MVP (Minimum Viable Product)

## O jogo PRECISA ter:
- Multiplayer local funcional
- Dois jogadores
- Mecânica cooperativa principal
- Objetivo de fase
- Vitória/Derrota
- HUD simples
- Menu inicial
- Build jogável

---

#  Fora de Escopo

Para evitar problemas de tempo, NÃO teremos:
- Multiplayer online
- Mundo aberto
- Sistema complexo de inventário
- IA avançada
- História longa
- Progressão RPG

---

#  Estrutura de Pastas

```txt
Content/
├── Blueprints/
├── Characters/
├── Maps/
├── UI/
├── Audio/
├── Materials/
├── Props/
└── FX/
```

---

#  Direção Visual

Estilo visual:
- Inspirado no Pantanal

---

#  Gameplay Principal

Loop principal:
1. Entrar na fase
2. Completar desafio
3. Avançar para próxima área

---

#  Mecânicas Planejadas

- Cooperação entre jogadores
- Interações compartilhadas
- Objetivos cooperativos
- Obstáculos ambientais
- Feedback visual e sonoro

---

#  Organização do Projeto

Utilizamos:
- GitHub Projects
- Issues
- Milestones
- Sprint semanal

---

#  Estrutura do GitHub Projects

## Colunas

- Backlog
- To Do
- Doing
- Testing
- Done

---

#  Labels Utilizadas

- Gameplay
- Multiplayer
- UI
- Audio
- Art
- Bug
- Optimization
- Urgent

---

#  Estrutura de Branches

```txt
main
 └── dev
      └── feature/*
```

Exemplos:
- feature/menu
- feature/movement
- feature/audio

---

#  Fluxo Git

1. Pull da branch dev
2. Criar branch feature
3. Desenvolver tarefa
4. Commit
5. Push
6. Pull Request para dev

---

#  Regras Importantes

## NÃO editar o mesmo mapa simultaneamente
Arquivos `.umap` geram muitos conflitos.

---

## Sempre fazer pull antes de começar

```bash
git pull origin dev
```

---

## Commits pequenos e organizados

Exemplo:
```bash
git commit -m "Implementa movimentação Player 2"
```

---

#  Git LFS

Este projeto utiliza Git LFS para arquivos da Unreal Engine.

## Instalação

Baixar:
https://git-lfs.com/

---

## Configuração

```bash
git lfs install
git lfs track "*.uasset"
git lfs track "*.umap"
```

---

#  Como Clonar o Projeto

## 1. Instalar
- Git
- Git LFS
- Unreal Engine 5

---

## 2. Clonar repositório

```bash
git clone URL_DO_REPOSITORIO
```

---

## 3. Entrar na pasta

```bash
cd NOME_DO_PROJETO
```

---

## 4. Abrir no Unreal Engine 5

---

#  Build e Testes

Toda sprint deve gerar:
- build jogável
- teste local
- validação multiplayer

---

#  Estado Atual do Projeto

## Sprint Atual
 Estrutura inicial

## Em desenvolvimento
- Multiplayer local
- Movimento dos jogadores
- Mecânica principal

---

#  Ferramentas Utilizadas

- Unreal Engine 5
- GitHub
- GitHub Projects
- Git LFS
- Discord

---

#  Licença

Este projeto utiliza a licença MIT.

---

#  Agradecimentos

- EXPOGEEKMS
- Bioparque Pantanal
- Game Jam 2026
- Epic Games
- Comunidade Unreal Engine
