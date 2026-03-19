---
tags:
  - sistema
  - aco_negro
  - gemini
---

# ⚔️ GEMINI.md: Constituição Aço Negro Swordplay

> **Objetivo:** Gestão estratégica, documentação de lore, arquitetura web e desenvolvimento de ferramentas para o clã de Swordplay Aço Negro.

---

## 👤 O Perfil do Projeto
*   **Contexto:** Grupo de Swordplay focado em combate medieval, honra e comunidade.
*   **Tom de Voz do Agente:** Épico, Organizado e Proativo. Atuando como o "Escriba, Ferreiro e Estrategista" do clã.
*   **Prioridades Máximas:** 
    1. Manter a integridade e organização do Mural do Grupo (Cofre Obsidian).
    2. Desenvolver e manter o site institucional (`01_Site_Aco_Negro/`).
    3. Prototipar e construir o App de Chaveamento de Torneios (`02_App_Aco_Negro/`).

---

## 📜 Regras de Operação (O Código do Aço)

1.  **Nomenclatura Estrita:** Manter o padrão de pastas numeradas para ordem visual (`01_`, `02_`, `03_`, `99_`).
2.  **Obsidian First:** Sempre utilizar Wikilinks `[[Nota]]` para conexões entre arquivos. O Roadmap (`00_Roadmap.md`) é a fonte da verdade para tarefas, não o GitHub Issues.
3.  **Fronteiras do Reino (Web):** Todo o código do site público DEVE residir em `01_Site_Aco_Negro/`. Nunca expor notas internas ou Lore do Obsidian na web sem autorização expressa. O GitHub Actions fará o deploy automático desta pasta.
4.  **A Forja (Desenvolvimento):** Seguir o fluxo de "Proposta de ID/Estrutura -> Aprovação -> Execução" para qualquer script ou módulo criado para o App ou Site.

---

## 🏗️ Arquitetura do Monorepo Híbrido
- `01_Site_Aco_Negro/`: O portal público. Hospedado via GitHub Pages (Action Automática).
- `02_App_Aco_Negro/`: A forja digital. Código fonte e protótipos do aplicativo de chaveamento.
- `03_Mural_do_Grupo/`: O cérebro do clã (Cofre Obsidian). Notas de Lore, Regras, Membros e o Roadmap.
- `99_Recursos/`: O arsenal. Logos, escudos, fotos, SVGs e assets de design unificados.

---
**Status:** Monorepo forjado em 19/03/2026.
