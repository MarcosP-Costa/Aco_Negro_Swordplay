<div align="center">
  <img src="99_Recursos/Imagem.jpg" alt="Aço Negro Escudo" width="400"/>

  <br><br>

  <!-- Badges Visuais (Paleta Aço Negro) -->
  <a href="#"><img src="https://img.shields.io/badge/Status-Active_Development-8B0000?style=for-the-badge&logo=github&logoColor=white" alt="Status"></a>
  <a href="#"><img src="https://img.shields.io/badge/Obsidian-Vault-1a1a1a?style=for-the-badge&logo=obsidian&logoColor=white" alt="Obsidian Vault"></a>
  <a href="https://MarcosP-Costa.github.io/Aco_Negro_Swordplay/"><img src="https://img.shields.io/badge/Deploy-GitHub_Pages-333333?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Pages"></a>
</div>

<br>

Este repositório adota a arquitetura de **Monorepo**, centralizando a base de conhecimento do grupo (Obsidian Vault), o código-fonte do site institucional e o desenvolvimento do futuro aplicativo mobile.

---

## 🛠️ Stack Tecnológica & Ferramentas

<div align="center">
  <img src="https://img.shields.io/badge/Obsidian-1a1a1a?style=for-the-badge&logo=obsidian&logoColor=white" alt="Obsidian" />
  <img src="https://img.shields.io/badge/HTML5-1a1a1a?style=for-the-badge&logo=html5&logoColor=E34F26" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1a1a1a?style=for-the-badge&logo=css3&logoColor=1572B6" alt="CSS3" />
  <img src="https://img.shields.io/badge/GitHub_Actions-1a1a1a?style=for-the-badge&logo=github-actions&logoColor=2088FF" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Python-1a1a1a?style=for-the-badge&logo=python&logoColor=3776AB" alt="Python" />
</div>

---

## 📊 Métricas e Atividade

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=MarcosP-Costa&repo=Aco_Negro_Swordplay&bg_color=0a0a0a&title_color=8b0000&text_color=e6d5b8&icon_color=cccccc&border_color=333333&v=1" alt="Aço Negro Swordplay Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MarcosP-Costa&repo=Aco_Negro_Swordplay&layout=compact&bg_color=0a0a0a&title_color=8b0000&text_color=e6d5b8&icon_color=cccccc&border_color=333333&v=1" alt="Top Languages" />
</div>

<br>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MarcosP-Costa/Aco_Negro_Swordplay/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/MarcosP-Costa/Aco_Negro_Swordplay/output/github-contribution-grid-snake.svg">
    <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/MarcosP-Costa/Aco_Negro_Swordplay/output/github-contribution-grid-snake.svg">
  </picture>
</div>

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

A identidade visual do projeto, baseada no brasão oficial (Anima Conformata), deve seguir estritamente o seguinte esquema de cores para garantir consistência entre o Site e o App:

*   **Primary Background (Fundo Principal):** Preto Profundo (`#000000` a `#0a0a0a`)
*   **Surface/Metals (Superfícies de Aço):** Grafite Texturizado (`#1f1f1f` a `#2c2c2c`)
*   **Accent Color (Brilho/Energia):** Vermelho Sangue / Escarlate Neon (`#ff0000`, `#cc0000`, `#8b0000`)
*   **Text/Parchment (Textos e Faixas):** Pergaminho / Bege Envelhecido (`#e6d5b8`) e Cinza Prata (`#cccccc`)

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