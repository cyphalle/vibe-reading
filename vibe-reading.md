# Vibe Reading Process

A structured approach for analyzing and extracting **actionable insights** from non-fiction business books, particularly for startup founders and product managers.

**Important: All analysis documents produced following this process should be written entirely in French.**

---

## Philosophy: "Le Livre + Le Guide d'Implémentation Que Tu Aurais Dû Avoir"

Le vibe reading assume que **tu n'as pas lu le livre** et remplit deux rôles simultanément :

### Rôle 1: Substitut au Livre (Compréhension)
- ✅ **Comprendre le contenu** : L'histoire/narrative complète (si fable)
- ✅ **Comprendre le framework** : Le modèle théorique complet avec toutes ses nuances
- ✅ **Comprendre le contexte** : Pourquoi l'auteur a écrit ça, pour qui, quand
- ✅ **Comprendre les exemples** : Case studies et histoires qui illustrent les concepts

### Rôle 2: Guide d'Implémentation (Action)
- ✅ **80/20 Extraction** : Les 20% critiques qui génèrent 80% de la valeur
- ✅ **Templates + Scripts** : Mots exacts, formats copiables
- ✅ **Timelines** : Plans semaine par semaine
- ✅ **Troubleshooting** : Anti-patterns et recovery paths
- ✅ **Actionnable immédiatement** : Aujourd'hui, cette semaine, ce mois

**Principe fondamental** : "If everything is important, then nothing is."

**Balance** : Tu dois pouvoir lire SEULEMENT le vibe reading et :
1. Comprendre tous les concepts clés du livre (ne pas avoir besoin de le lire)
2. Savoir exactement quoi faire lundi matin (actions concrètes)
3. Reconnaître les pièges et savoir comment les éviter

---

## Repository Structure

```
vibe-reading/
├── epub/                          # EPUB source files (gitignored)
│   └── book-title.epub
├── md/                            # All analysis outputs
│   └── book-title/
│       └── book-title.md          # Single consolidated analysis
├── vibe-reading.md                # This process doc
└── .gitignore                     # Ignores /epub
```

**File Naming**:
- `md/five-dysfunctions/five-dysfunctions.md`
- `md/inspired/inspired.md`
- `md/radical-candor/radical-candor.md`

**Single File Per Book**: Tous les insights consolidés dans UN fichier markdown pour faciliter la navigation et la recherche.

---

## 5-Phase Process Overview

```
ANALYZE → DISTILL → OPERATIONALIZE → TROUBLESHOOT → INTEGRATE
```

### Phase 1: **ANALYZE** (Extract & Structure)
→ Comprendre structure du livre, extraire concepts clés, raconter l'histoire complète
→ Output: Full analysis narrative + Insights organisés
→ **Rôle** : Substitut au livre (tu n'as pas besoin de le lire après)

### Phase 2: **DISTILL** (80/20 Extraction)
→ Identifier les 20% critiques qui génèrent 80% de la valeur
→ Output: Essential Digest (5 pages max)
→ **Rôle** : Quick access si tu as 30 minutes

### Phase 3: **OPERATIONALIZE** (Make Actionable)
→ Transformer insights en actions concrètes
→ Output: Implementation Playbook + Templates + Scripts
→ **Rôle** : Savoir exactement quoi faire lundi matin

### Phase 4: **TROUBLESHOOT** (Anticipate Failure)
→ Cataloguer anti-patterns et recovery paths
→ Output: Failure Patterns + Decision Protocols
→ **Rôle** : Reconnaître les pièges et savoir comment les éviter

### Phase 5: **INTEGRATE** (Connect Ecosystem)
→ Liens avec autres frameworks/books, persona-specific guidance
→ Output: Integration guides + Persona quick guides
→ **Rôle** : Adapter au contexte spécifique (CEO vs PM vs IC)

---

## Detailed Process

### **PHASE 1: ANALYZE**

#### Step 1.1: Book Structure Extraction

**Actions**:
1. Read metadata (author, publication date, publisher, context)
2. Extract complete table of contents from EPUB
3. Identify main parts/sections and chapter breakdown
4. Understand target audience and book's scope
5. Map the book's argument structure

**Template**:
```markdown
# [Book Title] - Structure Analysis

**Author**: [Name]
**Published**: [Year]
**Publisher**: [Name]
**Target Audience**: [Who]

## Table of Contents
[Full TOC extracted]

## Book Structure
- Part 1: [Theme]
- Part 2: [Theme]
[etc.]

## Core Argument
[1 paragraph: What is this book trying to prove/teach?]
```

#### Step 1.2: Content Extraction

**CRITIQUE** : Cette phase doit être suffisamment complète pour que le lecteur n'ait PAS besoin de lire le livre original.

Pour chaque section majeure (pas nécessairement chaque chapitre) :

**A. Summary**
- 2-3 phrases capturant l'argument principal (en français)
- Contexte dans le framework global du livre
- **IMPORTANT** : Si fable/narrative, raconter l'histoire complète avec :
  - Les personnages et leurs arcs de transformation
  - Les scènes clés et leur progression
  - Les dialogues importants qui illustrent les concepts
  - La résolution et les outcomes

**B. Key Quotes**
- 3-5 quotes les plus impactantes
- Self-contained et powerful
- Actionable ou mémorable
- Avec contexte si nécessaire pour comprendre

**C. Key Takeaways**
- 5-10 concepts principaux
- Focus sur principes applicables
- Distiller les idées complexes en points simples
- **Explication complète** : Ne pas assumer que le lecteur connaît le contexte

**D. Application Context**
- **Immediate Actions**: Ce que tu peux faire maintenant
- **Strategic Considerations**: Implications long-terme
- **Context-Specific Applications**: Comment ça s'applique à ton industrie/stage
- **Questions to Consider**: Questions provocatrices pour réflexion profonde

**Template**:
```markdown
## Partie X: [Titre]

### Summary
[2-3 phrases en français]

### Key Quotes
> **"[Quote 1]"**
> **"[Quote 2]"**

### Key Takeaways
1. **[Concept]**: Explication brève
2. **[Concept]**: Explication brève
[...]

### Application au Contexte Startup/Product Management

#### **Immediate Actions:**
- [ ] Action 1
- [ ] Action 2

#### **Strategic Considerations:**
- Considération 1
- Considération 2

#### **Applications Spécifiques:**
- Application 1
- Application 2

#### **Questions to Consider:**
- Question 1 ?
- Question 2 ?
```

---

### **PHASE 2: DISTILL** (Essential Digest)

**Goal**: Créer un digest de 5 pages max pour quelqu'un qui a 30 minutes.

**Structure**:

```markdown
# [Book Title] - Essential Digest (30 min read)

## Si tu ne lis qu'UNE chose :
[Le principe #1 le plus important en 1 paragraphe]

## Les 3-5 Insights Qui Changent Tout
1. **[Insight]**
   → Action immédiate : [Template/link]

2. **[Insight]**
   → Action immédiate : [Template/link]

[etc.]

## Ta Prochaine Heure
- [ ] [Action concrète avec temps estimé]
- [ ] [Action concrète avec temps estimé]
- [ ] [Action concrète avec temps estimé]

## Pour Aller Plus Loin
→ [Liens vers sections approfondies]
```

**Critères de sélection des insights** :
- ✅ Contre-intuitif (challenge les assumptions)
- ✅ High-ROI (petit effort, grand impact)
- ✅ Immediately actionable (peut être fait cette semaine)
- ✅ Validated (exemples concrets du livre)
- ❌ Generic advice ("work hard", "communicate better")
- ❌ Nécessite contexte extensif pour comprendre

---

### **PHASE 3: OPERATIONALIZE** (Implementation)

#### 3.1: Implementation Playbook

**Structure suggérée** : 12-Week Timeline (ajuster selon le livre)

```markdown
# [Book Title] - 12-Week Implementation Playbook

## Week 1: [Objectif]
**Goal**: [Résultat mesurable]

**Monday**:
- [ ] [Action spécifique avec timing]
- [ ] [Template à utiliser]

**Wednesday**:
- [ ] [Action spécifique]
- [ ] [Script de facilitation]

**Friday**:
- [ ] [Checkpoint/Review]

**FAILURE MODE**: [Symptôme que ça échoue]
**IF THIS HAPPENS**: [Remediation exacte]

**SUCCESS METRIC**: [Comment savoir que ça marche]

---

## Week 2: [Objectif]
[Same structure]
```

**Principes** :
- Chaque semaine = 1 objectif clair et mesurable
- Actions spécifiques avec timings ("30 min", "2h", etc.)
- Failure modes anticipés avec recovery paths
- Success metrics objectifs

#### 3.2: Exercise Templates

Pour chaque exercice pratique mentionné dans le livre, créer :

```markdown
## Exercise: [Nom]

**Purpose**: [Pourquoi faire ça]
**Time Required**: [Durée]
**Participants**: [Qui]
**Materials**: [Ce dont tu as besoin]

### Preparation
1. [Step]
2. [Step]

### Facilitation Script
YOU: "[Exact words to introduce exercise]"

[Step-by-step avec scripts exacts]

### Troubleshooting
**If [Problem]**: [Solution]
**If [Problem]**: [Solution]

### Success Looks Like
- [Observable behavior 1]
- [Observable behavior 2]

### Template
[Downloadable/copyable template]
```

**Exemples d'exercices** :
- Personal Histories (Five Dysfunctions)
- Sprint Planning Template (Scrum)
- 1:1 Framework (Manager guides)

#### 3.3: Conversation Scripts

Pour les conversations difficiles mentionnées :

```markdown
## Script: [Situation]

**Context**: Quand utiliser ce script
**Goal**: Ce que tu veux accomplir

---

YOU: "[Opening exact words]"

THEM: [Réaction probable]

YOU: "[Response + probing question]"

[If they deflect]
YOU: "[Alternative angle]"

[If they engage]
YOU: "[Next step]"

---

**Don'ts**:
- ❌ [Ce qu'il ne faut PAS dire]
- ❌ [Erreur commune]

**Key Phrases**:
- ✅ "[Phrase qui marche]"
- ✅ "[Phrase alternative]"
```

---

### **PHASE 4: TROUBLESHOOT** (Failure Patterns)

#### 4.1: Failure Patterns Library

Cataloguer les anti-patterns du livre avec reconnaissance + remediation :

```markdown
## Pattern: "[Nom de l'Anti-Pattern]"

### How to Recognize
- ✅ [Symptôme observable 1]
- ✅ [Symptôme observable 2]
- ✅ [Symptôme observable 3]

### Why It Persists
- [Raison psychologique/organisationnelle]
- [Raison secondaire]

### Cost to Team/Organization
- [Impact quantifiable si possible]
- [Case study du livre]

### Remediation Path
**Week 1**: [Action]
**Week 2**: [Action]
**Week 3**: [Decision point]
**Week 4**: [Final action]

### Red Flag You're The Problem
[Comment savoir si TU es la cause, pas juste la victime]

### Key Lesson
> **"[Quote du livre qui capture la leçon]"**
```

#### 4.2: Decision Protocols

Guides de "dans cette situation, fais ça" :

```markdown
## Decision Protocol: [Situation]

**Symptom**: [Ce que tu observes]

**Root Cause Diagnostic**:

Question 1: [Diagnostic question]
- YES → [Potential cause A]
- NO → [Potential cause B]

Question 2: [Follow-up diagnostic]
- YES → [Confirmed cause]
- NO → [Alternative cause]

---

### If Cause A:
1. [Immediate action]
2. [Follow-up action]
3. [Escalation if persists]

### If Cause B:
1. [Different immediate action]
2. [Follow-up action]
3. [Escalation if persists]

---

**Script to Use**: [Link to conversation script]
**Template to Use**: [Link to template]
```

---

### **PHASE 5: INTEGRATE** (Ecosystem)

#### 5.1: Persona-Specific Quick Guides

Créer des guides ultra-ciblés (2 pages max) par persona :

```markdown
# [Book Title] - Guide pour [Founder-CEOs / Product Managers / ICs / etc.]

## Focus Areas for You
- [Concept 1 le plus pertinent]
- [Concept 2 le plus pertinent]
- [Concept 3 le plus pertinent]

## Your Top 3 Actions
1. [Action spécifique au rôle]
2. [Action spécifique au rôle]
3. [Action spécifique au rôle]

## Red Flags Specific to Your Role
- 🚩 [Signe de danger 1]
- 🚩 [Signe de danger 2]
- 🚩 [Signe de danger 3]

## Case Study from Book
[Personnage du livre le plus relatable pour cette persona]
[Key lesson de son arc]

## Further Reading
→ [Sections approfondies pertinentes]
```

**Personas standards** :
- Founder-CEOs
- Product Managers
- Engineering Managers
- Individual Contributors
- Board Members / Investors

#### 5.2: Metrics Dashboard

Pour les livres avec KPIs/métriques :

```markdown
# [Book Title] - Transformation Dashboard

## Leading Indicators (Behavioral)

| Metric | How to Measure | Target | Week 1 | Week 4 | Week 8 | Week 12 |
|--------|---------------|--------|--------|--------|--------|---------|
| [Behavior 1] | [Method] | [Goal] | _ | _ | _ | _ |
| [Behavior 2] | [Method] | [Goal] | _ | _ | _ | _ |

## Lagging Indicators (Business)

| Metric | Baseline | Week 4 | Week 8 | Week 12 | Target |
|--------|----------|--------|--------|---------|--------|
| [Business KPI 1] | _ | _ | _ | _ | [Goal] |
| [Business KPI 2] | _ | _ | _ | _ | [Goal] |

## How to Use
- Update: [Frequency]
- Red flag: [Threshold]
- Green flag: [Threshold]
- Review cadence: [When]
```

---

## Output Structure (Single Consolidated File)

**Un seul fichier `md/book-title/book-title.md` contenant toutes les phases** :

**PRINCIPE** : Le lecteur n'a PAS lu le livre. La structure doit permettre deux parcours :
- **Parcours Quick (30-60 min)** : Essential Digest + Quick Guides
- **Parcours Complet (3-4h)** : Full Analysis + tout le reste

```markdown
# [Book Title] - Complete Vibe Reading Analysis

**Author**: [Name]
**Year**: [Year]
**Context**: [Brief context - qui, pourquoi, pour qui]

---

## Navigation

**Si tu as 30 min** :
→ [Essential Digest](#essential-digest) + [Ton Persona Guide](#persona-guides)

**Si tu veux tout comprendre** :
→ [Full Analysis (substitut au livre)](#full-analysis)

**Si tu veux implémenter** :
→ [12-Week Playbook](#implementation-playbook) + [Templates](#exercise-templates) + [Scripts](#conversation-scripts)

**Si tu galères** :
→ [Failure Patterns](#failure-patterns) + [Decision Protocols](#decision-protocols)

---

## Essential Digest (30 min read)

**BUT** : Comprendre les 20% critiques + avoir 3 actions immédiates

[Phase 2 content]

---

## Full Analysis - SUBSTITUT AU LIVRE (3-4h read)

**BUT** : Tu n'as pas besoin de lire le livre après avoir lu cette section.
Tout est là : l'histoire complète, tous les concepts, tous les exemples.

### Book Structure & Context
[Phase 1 content - Structure complète]

### Part 1: [Title]
**Ce qui se passe** : [Narrative complète si fable, ou progression argumentative]
**Les concepts** : [Framework détaillé]
**Les exemples** : [Case studies complets]

[Phase 1 content - Detailed analysis]

### Part 2: [Title]
[Phase 1 content - Detailed analysis]

[etc. - TOUT le contenu du livre de manière exhaustive]

---

## 12-Week Implementation Playbook

**BUT** : Savoir exactement quoi faire lundi matin, puis chaque semaine pendant 12 semaines

[Phase 3 content - Playbook]

---

## Exercise Templates

**BUT** : Templates copiables pour chaque exercice mentionné

[Phase 3 content - Templates]

---

## Conversation Scripts

**BUT** : Mots exacts pour conversations difficiles

[Phase 3 content - Scripts]

---

## Persona-Specific Quick Guides

**BUT** : Navigation rapide pour ton rôle spécifique

### For Founder-CEOs (2 pages)
[Phase 5 content]

### For Product Managers (2 pages)
[Phase 5 content]

### For Individual Contributors (2 pages)
[Phase 5 content]

---

## Failure Patterns Library

**BUT** : Reconnaître les pièges avant de tomber dedans

[Phase 4 content - Patterns]

---

## Decision Protocols

**BUT** : "Si je vois X, je fais Y"

[Phase 4 content - Protocols]

---

## Metrics Dashboard

**BUT** : Tracker la transformation sur 12 semaines

[Phase 5 content - Dashboard]

---

## Resources

### Templates
- [ ] [Template name with description]
- [ ] [Template name with description]

### Scripts
- [ ] [Script name with description]
- [ ] [Script name with description]

### Further Reading
- [Related book/article]
- [Related framework]
```

---

## Best Practices

### For Analysis:
- ✅ **Actionability First**: Tout doit conduire à une action concrète
- ✅ **Specificity Over Generality**: "Faites Personal Histories mercredi 10h" > "Build trust"
- ✅ **Anti-Patterns Explicit**: Montrer ce qu'il NE faut PAS faire
- ✅ **Metrics-Driven**: Comment savoir si ça marche ?
- ✅ **Time-Bounded**: Donner des timings réalistes
- ✅ **Scripts & Templates**: Mots exacts, formats copiables

### For Quote Selection:
- ✅ Counter-intuitive ou surprising
- ✅ Self-contained (pas besoin de contexte lourd)
- ✅ Actionable ou mémorable
- ✅ Tweetable (150-280 chars idéal)
- ❌ Generic platitudes
- ❌ Nécessite 3 paragraphes d'explication

### For Implementation Guidance:
- ✅ **Week-by-week roadmap**: Pas juste "do this eventually"
- ✅ **Failure modes anticipés**: "Si X arrive, fais Y"
- ✅ **Observable success criteria**: Pas "tu te sentiras mieux"
- ✅ **Estimated time**: "30 min", "2h", "ongoing"
- ✅ **Prerequisite explicit**: "Avant de faire X, assure-toi Y"

### For Troubleshooting:
- ✅ **Pattern Recognition**: Comment identifier le problème
- ✅ **Root Cause Analysis**: Pourquoi ça arrive (pas juste symptômes)
- ✅ **Recovery Paths**: Steps séquentiels pour corriger
- ✅ **Prevention**: Comment éviter à l'avenir
- ✅ **Self-Diagnosis**: "Red flag you're the problem" sections

---

## Common Pitfalls to Avoid

### Analysis Pitfalls:
- ❌ **Everything is important** : Violates "If everything is important, then nothing is"
- ❌ **Theory without practice** : Insights sans templates/scripts/timelines
- ❌ **Assume book was read** : Références obscures, contexte manquant, personnages non introduits
- ❌ **Incomplete narrative** : Raconter 60% de l'histoire et dire "pour la fin, lis le livre"
- ❌ **Linear only** : Pas de navigation pour quick access vs. deep dive
- ❌ **Generic advice** : "Communicate better" sans dire exactement comment
- ❌ **No failure modes** : Assume tout va marcher du premier coup
- ❌ **Persona-agnostic** : CEO et IC ont des besoins différents

### Implementation Pitfalls:
- ❌ **No time estimates** : "Do this" sans dire combien de temps
- ❌ **Missing prerequisites** : Step 5 before Step 1
- ❌ **Vague metrics** : "Improve team health" sans mesure
- ❌ **One-size-fits-all** : Même guidance pour startup 5 personnes et corp 500
- ❌ **No troubleshooting** : Quand ça échoue (et ça échouera), puis quoi ?

---

## Quality Checklist

Avant de considérer l'analyse complète, vérifier :

### Essential Digest (Phase 2)
- [ ] ≤ 5 pages pour 30 min de lecture
- [ ] Top 3-5 insights counter-intuitifs identifiés
- [ ] Chaque insight a une action immédiate (aujourd'hui/cette semaine)
- [ ] "Ta prochaine heure" section avec 3 checkboxes clairs

### Implementation (Phase 3)
- [ ] 12-week playbook (ou timeline adaptée) existe
- [ ] Chaque semaine a goal mesurable + failure mode + success metric
- [ ] Au moins 3 exercise templates avec scripts de facilitation
- [ ] Au moins 3 conversation scripts pour situations difficiles
- [ ] Tous les timings spécifiés ("30 min", "2h", etc.)

### Troubleshooting (Phase 4)
- [ ] Au moins 5 failure patterns catalogués du livre
- [ ] Chaque pattern a : Recognition + Why + Cost + Remediation + Self-diagnosis
- [ ] Au moins 3 decision protocols pour situations communes
- [ ] Flowchart/decision tree clair (if X then Y, else Z)

### Integration (Phase 5)
- [ ] Quick guides pour 3+ personas (CEO/PM/IC minimum)
- [ ] Chaque quick guide ≤ 2 pages
- [ ] Metrics dashboard si applicable au livre
- [ ] Leading (behavioral) ET lagging (business) indicators

### Full Analysis (Phase 1) - SUBSTITUT AU LIVRE
- [ ] Book structure complète extraite
- [ ] Chaque section majeure analysée (Summary/Quotes/Takeaways/Application)
- [ ] **Si fable** : Histoire complète racontée avec personnages, arcs, scènes clés, dialogues
- [ ] **Si framework** : Tous les concepts expliqués en détail avec contexte complet
- [ ] **Tous les exemples/case studies** du livre inclus et expliqués
- [ ] Application section a toujours : Immediate Actions + Strategic + Context-Specific + Questions
- [ ] Tout est en français comme spécifié
- [ ] **TEST CRITIQUE** : Un lecteur qui ne lit QUE cette section doit pouvoir avoir une conversation intelligente sur le livre sans l'avoir lu

### Consolidation
- [ ] UN SEUL fichier markdown par livre
- [ ] Navigation claire en haut (anchors vers sections)
- [ ] Ordre logique : Digest → Playbook → Guides → Patterns → Full Analysis
- [ ] Templates/Scripts extractables (copyable)
- [ ] Liens internes fonctionnent

---

## Workflow Recommendations

### Suggested Order of Execution:

**Week 1** : Phase 1 (Analyze)
- Jours 1-2 : Structure extraction
- Jours 3-5 : Content analysis (all sections)
- Output : Insights bruts organisés

**Week 2** : Phase 2 + 3 (Distill + Operationalize)
- Jours 1-2 : Essential Digest (force 80/20)
- Jours 3-4 : Implementation Playbook (12-week timeline)
- Jour 5 : Templates & Scripts
- Output : Actionable guidance

**Week 3** : Phase 4 + 5 (Troubleshoot + Integrate)
- Jours 1-2 : Failure Patterns Library
- Jour 3 : Decision Protocols
- Jour 4 : Persona Guides
- Jour 5 : Metrics Dashboard + Consolidation
- Output : Complete single file

**Total : 3 weeks pour une analyse complète**

### Tools & Setup:
- Store EPUBs dans `/epub` (gitignored)
- Outputs dans `/md/book-title/book-title.md`
- Use EPUB extraction tools
- Use Claude/AI for content analysis
- Human curation pour 80/20 et quality control

---

## Examples

### Good Essential Digest:
```markdown
## Si tu ne lis qu'UNE chose :
Vulnerability-based trust (admettre faiblesses) ≠ predictability trust (faire ce que tu dis).
Sans le premier, impossible d'avoir conflit productif, commitment, accountability, ou results focus.

## Top 3 Insights
1. **Tolérer dysfunction > dysfunction elle-même**
   → Action : Identifie ton "brilliant jerk" aujourd'hui

2. **"A decision is better than no decision"**
   → Action : Set deadline pour ta top décision pending (cette semaine)

3. **Consensus est dangereux, buy-in ≠ consensus**
   → Action : Prochain débat, force "disagree and commit"

## Ta Prochaine Heure
- [ ] 15-min team assessment (15 questions)
- [ ] Planifie Personal Histories exercise (30 min meeting)
- [ ] Bloque premier off-site date dans calendar
```

### Good Week Structure:
```markdown
## Week 3: Practice Micro-Vulnerability

**Goal**: Chaque team member admet 1 weakness en meeting sans fear

**Monday 9am** (30 min):
- [ ] Send meeting invite : "Team Health Check"
- [ ] Use template: [link]
- [ ] Prep YOUR vulnerability to share first

**Wednesday 10am** (60 min):
- [ ] Facilitate using script below
- [ ] Start with YOUR weakness (model vulnerability)
- [ ] Go around table, each person shares 1 weakness
- [ ] No cross-talk, just listening

**Script**:
YOU: "I'm going to share something I'm not great at.
      [YOUR WEAKNESS].
      Who wants to go next?"

**Friday 4pm** (15 min):
- [ ] Quick debrief 1:1s : "How did Wednesday feel?"
- [ ] Note who didn't share authentically

**FAILURE MODE**: People give surface answers ("I work too hard")
**IF THIS HAPPENS**: You didn't model deep enough. Next week, share something harder.

**SUCCESS METRIC**: ≥80% shared something they wouldn't have said 2 weeks ago
```

### Good Failure Pattern:
```markdown
## Pattern: "The Brilliant Jerk" (Mikey/Fred)

### How to Recognize
- ✅ Excellent solo output, deliverables on time
- ✅ Eye-rolling, sarcastic comments in meetings
- ✅ Team members avoid engaging with them
- ✅ Takes solo credit, dismissive of others

### Why It Persists
Leader values their output over team health ("too good to lose")

### Cost
50% team performance drop when tolerated (Fred case study)

### Remediation (4-Week Path)
Week 1: Private convo - specific behaviors + consequences
Week 2: Public address if continues (script p.X)
Week 3: Choice - change radically or leave
Week 4: If no change, exit

### Red Flag You're The Problem
If you've tolerated >3 months, YOU are destroying team, not just them.

### Key Lesson
> "It's not Fred's behavior that hurt production 50%.
> It's my TOLERANCE of his behavior." - Kathryn
```

---

## Version History

**v2.0** (Current) - 5-Phase Process
- Added DISTILL phase (Essential Digest)
- Added OPERATIONALIZE phase (Playbooks + Templates + Scripts)
- Added TROUBLESHOOT phase (Failure Patterns + Decision Protocols)
- Added INTEGRATE phase (Persona Guides + Metrics)
- Single consolidated file per book
- EPUB in `/epub` (gitignored), outputs in `/md/book-title/`

**v1.0** (Original) - Basic Chapter Analysis
- Simple chapter-by-chapter summaries
- Key quotes and takeaways
- Basic application sections

---

*This process transforms passive reading into active implementation, ensuring you extract maximum value from business books and convert insights into measurable action.*
