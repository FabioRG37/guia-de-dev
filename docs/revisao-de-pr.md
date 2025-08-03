# 🔍 Checklist de Revisão de Pull Request (Code Review)

Este checklist deve ser seguido antes de aprovar ou fazer merge de uma Pull Request (PR).

---

## ✅ Checklist Geral

### 📋 Organização
- [ ] A PR está associada a uma Issue (ex: Closes #10)?
- [ ] O nome da branch segue o padrão correto? (ex: feat/nome-feature, fix/nome-bug)
- [ ] O título da PR está descritivo e no formato padrão? (ex: feat(perfil): adicionar edição de nome)
- [ ] O template de PR foi preenchido corretamente?

---

### 📝 Qualidade do Código
- [ ] O código está seguindo as boas práticas (legibilidade, nomeação clara)?
- [ ] Há comentários explicativos apenas onde necessário?
- [ ] O código não possui console.logs ou trechos de debug?
- [ ] As funcionalidades foram testadas manualmente?

---

### 🧪 Testes e Funcionamento
- [ ] Todas as funcionalidades descritas foram validadas?
- [ ] Correções de bugs realmente corrigem o problema sem quebrar outras partes?
- [ ] Se houve mudanças no design, está visualmente coerente com o restante do app?

---

### 📦 Organização de Arquivos
- [ ] Pastas e arquivos novos estão no local correto da estrutura?
- [ ] Não há arquivos desnecessários (ex: arquivos temporários, configs locais)?
- [ ] Assets (imagens, icons) estão otimizados e nomeados adequadamente?

---

### 🔖 Documentação
- [ ] Documentação ou arquivos relacionados (README, CHANGELOG, docs/) foram atualizados, se necessário?
- [ ] Versionamento foi considerado (atualizar tag ou changelog, se for uma versão nova)?

---

## 🚦 Observações Finais
- Somente aprove uma PR se você se sentir confiante sobre as mudanças.
- Se encontrar algo para melhorar, comente e solicite ajustes antes do merge.
- Para mudanças críticas, valide em múltiplos cenários de uso.

---
