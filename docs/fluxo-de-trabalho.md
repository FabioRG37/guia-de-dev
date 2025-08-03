# 🔄 Fluxo de Trabalho (Git Flow Simplificado)

Este documento descreve o fluxo de trabalho utilizado nos meus projetos, baseado em **Git Flow simplificado com Conventional Commits e Pull Requests**.

---

## 🎯 Etapas do Workflow

### 1. 📋 Abrir uma Issue (Bug ou Feature)
- Descreva o problema ou funcionalidade usando os **templates de Issue**.
- Classifique como:
  - 🐛 Bug
  - ✨ Nova Funcionalidade

### 2. 🔀 Criar uma branch a partir da main
- Use a nomenclatura adequada:
  - **feat/nome-da-feature**
  - **fix/nome-do-bug**
  - **chore/tarefa-de-manutencao**
- Exemplo:
  ```bash
  git checkout -b feat/perfil-edicao


### 3. 💻 Desenvolver e commitar seguindo Conventional Commits
* Exemplo de commit:
   ```bash
   git commit -m "feat(perfil): adicionar edição de nome e senha"


### 4. ⬆️ Push da branch para o GitHub
   ```bash
   git push origin feat/perfil-edicao
   ```

### 5. 📤 Abrir uma Pull Request (PR)
  * Utilize o template de Pull Request.

  * Relacione a PR com a Issue (ex: Closes #10).

### 6. 👀 Revisar e Aprovar a PR
* Faça uma auto-revisão antes de aprovar.

* Confirme que o checklist da PR foi seguido.

### 7. 🔀 Merge para main
* Após a aprovação, faça o merge da branch para a main.

* Utilize squash merge (se aplicável) para manter o histórico limpo.

### 8. 🏷️ Criar uma Release (se aplicável)
* Caso seja uma entrega importante, crie uma release no GitHub.

* Exemplo: v1.0.0, v1.1.0

### 9. 🚀 Deploy / Build
* Execute os comandos de build/deploy conforme a necessidade do projeto.

```css
   📋 ISSUE aberta
      ↳ 🐛 Bug → fix/
      ↳ ✨ Feature → feat/
         ↓
   🔀 Criar branch a partir da main
         ↓
   💻 Desenvolver e commitar (Conventional Commits)
         ↓
   ⬆️ Push da branch para o GitHub
         ↓
   📤 Abrir Pull Request (PR)
         ↓
   📝 Revisar e Aprovar PR
         ↓
   🔀 Merge para main
         ↓
   🏷️ Criar Release (se aplicável)
         ↓
   🚀 Deploy
```
🚀 Benefícios do Fluxo
* Mantém o histórico organizado e rastreável.

* Facilita colaboração em equipe.

* Permite identificar facilmente a origem de cada alteração.

* Fluxo simples e ágil, ideal para projetos solo e pequenas equipes.

## Observações
* Nuncatrabalhe direto na main.
* Use nomenclatura de branches consistente.
* Use templates de Pull Request e Issues para organizar.
