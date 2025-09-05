## 📝 Descrição das Alterações

Forneça um resumo claro sobre a motivação e o impacto deste Pull Request.

---

## 🚩 Verificação de Feature Flags (Se aplicável)

- [ ] A nova chave segue a taxonomia obrigatória (`release_`, `experiment_` ou `ops_`)?
- [ ] O nome da chave segue o padrão `snake_case` (`[categoria]_[dominio]_[nome]`)?
- [ ] A chave foi registrada centralizadamente no `enum FeatureFlags`?
- [ ] Foi configurado um valor de **Fallback estático (Fail-Safe)** no `DEFAULT_FLAG_VALUES`?
- [ ] O acesso à flag é feito exclusivamente via Hook/Provider oficial (`useFeatureFlag`)?
- [ ] Se for uma **Release Flag** ou **Experiment Flag**, o card Jira de limpeza/remoção em até 30 dias foi criado?

---

## 🧪 Cobertura de Testes

- [ ] Testes unitários atualizados/criados cobrindo os cenários `true` e `false`.
- [ ] Nenhum teste existente foi quebrado ou silenciado.

---

## 📋 Checklist de Qualidade

- [ ] A documentação foi atualizada (se este PR alterar padrões de arquitetura).
- [ ] Código escrito em alinhamento com as diretrizes de [Arquitetura Frontend](../docs/architecture-overview.md).
