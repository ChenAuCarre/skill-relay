# Specs

```text
user-stories  ──►  requirements  ──►  capabilities
 (problème)          (quoi)             (comment)
```

Chaque niveau découle du précédent :

| Fichier | Rôle | Découle de |
|---|---|---|
| [user-stories.md](user-stories.md) | Le **problème** : scénarios utilisateurs (US1–US3) | – |
| [requirements.md](requirements.md) | Le **quoi** : exigences (C, M, R, F, K) | user stories |
| [capabilities.md](capabilities.md) | Le **comment** : capacités du moteur (CAP-A à CAP-C) | exigences |

Le lien est écrit une seule fois, dans l'exigence, qui cite sa source (`US2`) et sa capacité (`CAP-B`). Les user stories et les capacités ne citent jamais d'exigences : elles ne changent pas quand une exigence change.

`requirements.md` est donc la seule table de traçabilité. Pour retrouver les exigences liées à un élément : `grep "CAP-A" requirements.md`.
