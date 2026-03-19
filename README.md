<div align="center">
  <img src="https://img.icons8.com/color/96/000000/sword.png" alt="Sword Icon" width="80"/>
  <h1>Aço Negro Swordplay</h1>
  <p><b>Repositório Oficial: Monorepo Híbrido (Web, Mobile & Docs)</b></p>

  <!-- Badges Visuais -->
  <a href="#"><img src="https://img.shields.io/badge/Status-Active_Development-orange?style=for-the-badge&logo=github" alt="Status"></a>
  <a href="#"><img src="https://img.shields.io/badge/Obsidian-Vault-7a3ee8?style=for-the-badge&logo=obsidian" alt="Obsidian Vault"></a>
  <a href="https://MarcosP-Costa.github.io/Aco_Negro_Swordplay/"><img src="https://img.shields.io/badge/Deploy-GitHub_Pages-success?style=for-the-badge&logo=github" alt="GitHub Pages"></a>
</div>

<br>

Este repositório adota a arquitetura de **Monorepo**, centralizando a base de conhecimento do grupo (Obsidian Vault), o código-fonte do site institucional e o desenvolvimento do futuro aplicativo mobile.

---

## 🏗️ Arquitetura do Monorepo

O repositório está estruturado para isolar contextos e evitar conflitos entre as equipes de conteúdo e desenvolvimento:

```text
📦 Aco_Negro_Swordplay
 ┣ 🌐 01_Site_Aco_Negro  --> Código-fonte estático do site institucional (HTML/CSS)
 ┣ 📱 02_App_Aco_Negro   --> (WIP) Base de código do aplicativo de chaveamento de torneios
 ┣ 🧠 03_Mural_do_Grupo  --> Obsidian Vault contendo documentação, regras e o Roadmap do projeto
 ┗ 🛡️ 99_Recursos        --> Assets compartilhados globais (SVGs, logos, paleta de cores)
```

---

## 🎨 Design System (Paleta de Cores)

A identidade visual do projeto, baseada no site original (Wix), deve seguir o seguinte esquema de cores para garantir consistência entre o Site e o App:

*   **Primary Background:** Preto (`#1a1a1a` a `#000000`)
*   **Secondary/Surface:** Cinza Chumbo / Aço (`#333333` a `#777777`)
*   **Text/Typography:** Branco e Prata Claro (`#e0e0e0` a `#ffffff`)
*   **Accent Color (Destaques/Avisos):** Vermelho Escuro / Sangue (`#b22222` ou `#8B0000`)

---

## 🚀 Setup do Ambiente e Deployment

### 1. Documentação (Obsidian)
Para visualizar ou editar a base de conhecimento:
1. Instale o [Obsidian](https://obsidian.md/).
2. Abra o aplicativo e selecione *`Open folder as vault`*.
3. Aponte para a raiz deste repositório clonado.
4. **Nota:** O arquivo de workspace pessoal (`.obsidian/workspace.json`) está no `.gitignore` e não deve ser commitado.

### 2. Deployment do Site (GitHub Pages)
O deploy do diretório `01_Site_Aco_Negro/` é automatizado via GitHub Actions. **A configuração inicial requer ativação manual no painel do GitHub:**
1. Acesse a aba **Settings** do repositório no GitHub.
2. Navegue até **Pages** no menu lateral esquerdo.
3. Na seção **Build and deployment**, altere o campo **Source** de *"Deploy from a branch"* para **"GitHub Actions"**.
4. A partir deste momento, qualquer push na branch `main` engatilhará o workflow de deploy automaticamente.

---

## 🔗 Links Úteis

- **[Site em Produção](https://MarcosP-Costa.github.io/Aco_Negro_Swordplay/)**
- **[Referência Legada (Site Wix)](https://ordemdoaconegro.wixsite.com/ordem-do-aco-negro)**

---

## 🤝 Diretrizes de Contribuição

1. **Separação de Contexto:** Arquivos Markdown relacionados a regras e lore devem permanecer estritamente em `03_Mural_do_Grupo`.
2. **Web Estático:** A pasta `01_Site_Aco_Negro` deve conter apenas assets públicos. Nenhuma documentação interna deve ser inserida neste diretório.
3. **Novos Módulos:** O desenvolvimento de novos scripts ou funcionalidades deve ser documentado e aprovado previamente pelos mantenedores antes da criação na raiz ou no módulo do App.