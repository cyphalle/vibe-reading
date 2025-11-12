# Vibe Reading

**Guide d'implémentation pratique pour livres business non-fiction**

Un processus structuré pour extraire les 20% d'insights critiques qui génèrent 80% de la valeur, et les transformer en actions concrètes.

---

## Philosophy

> **"Le Livre + Le Guide d'Implémentation Que Tu Aurais Dû Avoir"**

Le vibe reading **assume que tu n'as PAS lu le livre** et remplit deux rôles :

### 1. Substitut au Livre (Compréhension)
Tu dois pouvoir comprendre tous les concepts du livre sans avoir à le lire :
- ✅ L'histoire complète (si fable/narrative)
- ✅ Le framework théorique au complet
- ✅ Tous les exemples et case studies
- ✅ Le contexte (qui, pourquoi, pour qui)

### 2. Guide d'Implémentation (Action)
Tu dois savoir exactement quoi faire lundi matin :
- ✅ **Templates & Scripts** : Mots exacts, formats copiables
- ✅ **Timelines** : Plans semaine par semaine
- ✅ **Troubleshooting** : Anti-patterns et recovery paths
- ✅ **Metrics** : Leading et lagging indicators

**Principe fondamental** : *"If everything is important, then nothing is."*

**Test qualité** : Un lecteur qui lit SEULEMENT le vibe reading doit pouvoir :
1. Avoir une conversation intelligente sur le livre
2. Savoir exactement quoi faire lundi matin
3. Reconnaître et éviter les pièges

---

## Repository Structure

```
vibe-reading/
├── epub/                          # EPUB source files (gitignored)
│   └── *.epub
├── md/                            # Analysis outputs
│   ├── five-dysfunctions/
│   │   └── five-dysfunctions.md   # Single consolidated analysis
│   ├── inspired/
│   │   └── inspired.md
│   └── [other-books]/
├── vibe-reading.md                # Complete process documentation
├── .gitignore                     # Ignores /epub
└── README.md                      # This file
```

**Key Points**:
- 📚 EPUBs dans `/epub` (non-trackés par git)
- 📝 Un seul fichier `.md` par livre
- 🇫🇷 Toutes les analyses en français
- 🎯 Focus sur l'actionnable, pas la théorie pure

---

## Process Overview (5 Phases)

```
ANALYZE → DISTILL → OPERATIONALIZE → TROUBLESHOOT → INTEGRATE
```

**Détails complets** : Voir `vibe-reading.md`

---

## Books Analyzed

### ✅ The Five Dysfunctions of a Team (Patrick Lencioni)
**File** : `md/five-dysfunctions/five-dysfunctions.md`
**Size** : 125KB, 1488 lines

**Essential Insights** :
- Vulnerability-based trust ≠ predictability trust
- "A decision is better than no decision"
- Tolérer dysfunction > dysfunction elle-même
- Consensus est dangereux, buy-in ≠ consensus

---

**Get Started** : See `vibe-reading.md` for complete process documentation.
