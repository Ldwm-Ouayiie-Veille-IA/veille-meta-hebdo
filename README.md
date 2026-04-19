# Veille IA × Méta-synthèse hebdomadaire

Dépôt de la **synthèse globale** du dimanche soir, qui agrège et filtre les 8 synthèses sectorielles produites le même jour par les autres repos de l'organisation.

## Rythme de publication

- **Dimanche 23h Paris** (21h UTC) : une seule synthèse transversale, agrégée à partir des 8 hebdos sectoriels produits entre 20h et 22h.

## 📂 Accéder aux synthèses globales

➡️ **[Ouvrir le dossier des synthèses globales](meta/2026/)**

Depuis `meta/2026/` : choisir le mois (ex: `04-Avril/`), puis ouvrir le fichier `AAAA-MM-JJ_synthese-globale.md` du dimanche voulu.

```
meta/
└── 2026/                                ← tu arrives ici
    └── 04-Avril/
        ├── 2026-04-26_synthese-globale.md
        └── 2026-05-03_synthese-globale.md
```

## Les 8 repos sectoriels en entrée

Cette méta lit les 8 synthèses hebdomadaires produites dans les repos suivants (sibling de celui-ci) :

| Thème | Repo |
|---|---|
| 🎵 Musique | [veille-musique-ia](https://github.com/Ldwm-Ouayiie-Veille-IA/veille-musique-ia) |
| 🎨 Art (cinéma, TV, vidéo, image) | [veille-art-ia](https://github.com/Ldwm-Ouayiie-Veille-IA/veille-art-ia) |
| 💼 Travail | [veille-travail-ia](https://github.com/Ldwm-Ouayiie-Veille-IA/veille-travail-ia) |
| ⚽ Sport | [veille-sport-ia](https://github.com/Ldwm-Ouayiie-Veille-IA/veille-sport-ia) |
| 📺 Médias & élections | [veille-medias-elections-ia](https://github.com/Ldwm-Ouayiie-Veille-IA/veille-medias-elections-ia) |
| 🎥 Créateurs & contenu | [veille-createurs-contenu-ia](https://github.com/Ldwm-Ouayiie-Veille-IA/veille-createurs-contenu-ia) |
| 🔐 Cybersécurité | [veille-cybersecurite-ia](https://github.com/Ldwm-Ouayiie-Veille-IA/veille-cybersecurite-ia) |
| ⚔️ Défense & guerre | [veille-defense-guerre-ia](https://github.com/Ldwm-Ouayiie-Veille-IA/veille-defense-guerre-ia) |

## Ce que fait la méta

Pour chaque dimanche :

1. **Lit** les 8 synthèses sectorielles du jour.
2. **Filtre au 2e ordre** : retient 1 à 3 histoires par thème (parfois 0 si la semaine est vide), uniquement celles qui ont un vrai potentiel podcast.
3. **Détecte les ponts transversaux** : quand un même événement touche plusieurs thèmes (ex: procès Anthropic = Musique + Créateurs + Cyber).
4. **Liste les signaux à surveiller** la semaine suivante.
5. **Rend un seul document** lisible en 10-15 minutes le dimanche soir avant le lancement de la semaine de production.

## Cadre éditorial

Voir [CLAUDE.md](CLAUDE.md) pour le filtre de sélection, la méthodologie, la structure obligatoire du livrable et les règles anti-hallucination.

## Pull requests

Chaque méta-synthèse arrive sous forme de **pull request** sur une branche `claude/synthese-globale-*`. Relire, merger pour archiver dans `main`.
