# Skills du cours « IA : Claude Coding M1/M2 »

Marketplace de skills Claude utilisée pendant le cours (IAE, octobre 2026).

## Installer les skills (étudiants)

1. Ouvrir Claude (claude.ai) avec votre compte **Pro**.
2. **Settings → Capabilities** : vérifier que **Code execution** est activé.
3. Menu de gauche **Customize → Plugins → Add → Add marketplace → Add from a repository**.
4. Coller l'adresse de ce dépôt : `meriem-oss/iae-claude-skills`
5. Ouvrir le plugin **handsonai** et cliquer sur **Add / Install**.
6. Test : dans une nouvelle conversation, taper `/` → les skills `analyze`, `deconstruct`, `design`… doivent apparaître.

Dans Claude Code :
```
/plugin marketplace add meriem-oss/iae-claude-skills
/plugin install handsonai@iae-claude-coding
```

## Skills utilisés par jour

| Jour | Skills |
|---|---|
| Lundi après-midi | `analyze` → `deconstruct` |
| Mardi | `design` → `build` |
| Mercredi | `build`, `test` |
| Jeudi | `test`, `run`, `improve` |

## Crédits et licence

Le plugin `handsonai` est une copie du plugin open source de James Gray
([jamesgray-ai/handsonai-plugins](https://github.com/jamesgray-ai/handsonai-plugins)),
distribué sous licence MIT. Le fichier `LICENSE` d'origine est conservé dans ce dépôt.
