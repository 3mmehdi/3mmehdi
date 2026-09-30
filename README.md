# Mehdi Mezouar

Je construis des systèmes qui tournent sans moi, et des garde-fous qui les empêchent de mentir
quand ils tombent. Cinq ans de production (réseaux, VPN, Active Directory, gestion d'incidents),
puis mon agence, **Arkodis**, où je code tout moi-même, avec Claude Code tous les jours.

> *I build systems that run without me, and the guardrails that stop them lying when they break.
> Five years in production support, then my own agency. Most of my repositories are private
> because they are client work; what is public is my own tooling.*

---

### Ce qui est public ici

**[claude-code-guardrails](https://github.com/3mmehdi/claude-code-guardrails)** — sept garde-fous
qui empêchent un agent de coder de dériver : blocage de la création en série, vérification des
dates calculables, refus de laisser partir un secret, maintien d'invariants qu'une main perd.
Chacun existe parce qu'une consigne écrite n'a pas suffi, et le README donne l'incident daté qui
l'a produit.

**[research-pipeline](https://github.com/3mmehdi/research-pipeline)** — une skill Claude Code de
14 phases qui transforme un sujet en dossier sourcé et classé. Avec l'A/B qui a servi à mesurer sa
description, et la note honnête sur pourquoi les valeurs absolues de ce banc d'essai ne sont pas
exploitables.

**[apprendre-du-code](https://github.com/3mmehdi/apprendre-du-code)** — la skill qui ferme la boucle :
après un chantier, elle m'interroge sans me laisser rouvrir le diff, classe les réponses, puis range la
leçon et ne fabrique des cartes de révision que sur ce que j'ai raté. Son premier passage réel m'a montré
un angle mort que je n'avais pas vu.

### Ce qui ne l'est pas

Les sites et applications que je livre à mes clients, et l'agent de prospection qui tourne sur mon
serveur : recherche d'entreprise, audit PDF de leur site, rédaction, envoi automatique encadré par
des contrôles bloquants — jours d'envoi, plafond quotidien, anti-doublon, arrêt dès qu'un prospect
répond.

---

### Ce que je mesure plutôt que de le supposer

Je fais tourner une plateforme qui suit la visibilité d'une entreprise sur trois surfaces :
résultats Google classiques, aperçu IA de Google, et réponses de ChatGPT, Claude et Perplexity.
Python, PostgreSQL, quatre collecteurs planifiés, tables en ajout seul, 217 tests automatisés.

Sa revue hebdomadaire ne vérifie pas qu'aucune tâche n'a échoué. Elle vérifie que **les données
attendues sont arrivées**. C'est ce contrôle qui a attrapé une panne réseau ayant aussi fait taire
l'alerte censée la signaler.

> Un système de supervision qui ne peut pas échouer est pire que pas de supervision, parce qu'il
> fabrique de la confiance.

---

📍 Beauvais, France · télétravail · [LinkedIn](https://www.linkedin.com/in/mehdimezouar)
