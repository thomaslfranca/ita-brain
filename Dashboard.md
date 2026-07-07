---
type: dashboard
---

# ITA Brain — Dashboard

> Última atualização: `date(now)` — marque progresso no site ou aqui

## Links rápidos

- 🌐 **Site de questões**: [questoes/index.html](questoes/index.html)
- 📖 **Roteiro Iezzi**: [roteiro-iezzi/index.html](roteiro-iezzi/index.html)
- Exportar/importar progresso: use os botões no roteiro (site)

## Territórios — Status

> ⚠️ Requer plugin **Dataview**. Instale em Settings → Community Plugins → Dataview.

```dataview
TABLE status, target_date, questions_right + "/" + questions_total AS "acertei", fme_volumes
FROM "learning-records"
WHERE status
SORT choice(status = "dominado", 1, choice(status = "fronteira", 2, 3)) ASC
```

## Territórios por status

### Dominados 🟢

```dataview
LIST
FROM "learning-records"
WHERE status = "dominado"
```

### Fronteira 🟡

```dataview
LIST
FROM "learning-records"
WHERE status = "fronteira"
```

### Desconhecido 🔴

```dataview
LIST
FROM "learning-records"
WHERE status = "desconhecido"
```

## Sessões de estudo recentes

```dataview
TABLE date, territory, time_spent, questions_right + "/" + questions_attempted AS "acertei"
FROM "learning-records"
WHERE date
SORT date DESC
LIMIT 10
```

## Como usar

1. **No site** (`roteiro-iezzi/index.html`): clique nos círculos ao lado de cada questão para marcar se acertou/errou. Clique no status do território para mudar entre desconhecido/fronteira/dominado.
2. **No Obsidian**: abra a nota do território em `learning-records/` e atualize o frontmatter (`status`, `target_date`, etc.)
3. **Exportar/Importar**: o site salva progresso em localStorage. Use o botão "Exportar JSON" para backup e "Importar JSON" para restaurar.
4. **Sessões de estudo**: crie uma nota usando o template "Sessão de Estudo" para registrar o que estudou erros e próximos passos.