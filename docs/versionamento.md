
# 📦 Guia de Versionamento e Releases

Este documento explica como versionar e lançar releases oficiais no projeto.

---

## 🎯 Versionamento Semântico (SemVer)

O formato padrão é:
```

vMAJOR.MINOR.PATCH

````

### Regras:
| Tipo  | Quando atualizar                                   |
|-------|----------------------------------------------------|
| MAJOR | Mudanças que quebram compatibilidade ou grandes refatores |
| MINOR | Novas funcionalidades sem quebrar o funcionamento atual |
| PATCH | Correções de bugs ou ajustes pequenos |

---

## 🚀 Processo de Release no GitHub

1. Finalize as alterações na branch.
2. Suba para a main.
3. Crie uma tag:
   ```bash
   git tag v1.0.0
   git push origin v1.0.0
   ````

4. Acesse a aba **Releases** no GitHub.
5. Crie uma nova Release e associe à tag.
6. Escreva o **Changelog** (resumo das mudanças).
7. (Opcional) Anexe arquivos (ex: APK do app).

---

## 📝 Exemplo de Changelog (Release Notes)

### v1.1.0 — Perfil de Usuário

* feat: Implementar edição de perfil (nome e senha)
* fix: Corrigir redirecionamento no AuthGuard
* chore: Adicionar template de Pull Request

---

## 📋 Boas Práticas

* Não lance Release direto de uma branch de feature.
* Teste tudo antes de criar uma Release.
* Mantenha um **CHANGELOG.md** atualizado (opcional).

---
