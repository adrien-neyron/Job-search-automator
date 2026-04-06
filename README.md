#Job Search Automator — Pipeline d'automatisation de recherche d'emploi end-to-end avec validation humaine.

Système complet qui scrape les offres d'emploi (Playwright), les analyse et personnalise les candidatures via Claude API, stocke tout dans Airtable, et présente un dashboard React pour valider chaque envoi avant qu'il parte. Aucun email n'est envoyé sans approbation manuelle.
Stack : Node.js · Playwright · Claude API · Make.com · Airtable · React
Fonctionnalités :
Scraping automatisé des offres ciblées
Scoring et matching des offres via Claude API
Génération de messages de candidature personnalisés
Workflow human-in-the-loop : validation avant envoi
Dashboard React de suivi du pipeline (statuts, métriques, historique)
Orchestration des scénarios via Make.com