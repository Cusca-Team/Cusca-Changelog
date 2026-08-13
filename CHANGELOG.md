# Changelog

Toutes les évolutions notables de Cusca sont documentées ici.
Format inspiré de [Keep a Changelog](https://keepachangelog.com/fr/1.0.0/).

## [1.0.0] — 2026-08-13

Première version complète du bot — 42 commandes, panel web complet.

### Ajouté

**Modération & sécurité**
- Modération de base : `/ban` `/kick` `/mute` `/unmute` `/unban` `/warn` `/warnings` (avec escalade automatique)
- Modération avancée : `/purge` `/lock` `/unlock` `/slowmode` `/role`
- Auto-Modération native Discord (anti-invite, anti-spam de mentions, anti-injures)
- Logs détaillés par catégorie (messages, membres, modération, rôles, vocal)
- **Vérification anti-raid par captcha** — image générée, rôle restreint le temps de la résolution

**Niveaux**
- XP par message, bonus messages longs
- Multiplicateurs d'XP par rôle et par salon
- Filtres avec/sans gain d'XP (rôles et salons)
- Gestion fine du gain d'XP en vocal, threads et forums
- Récompenses de rôle par niveau
- Classement en ligne (page publique) + `/classement` Discord
- Carte de rang visuelle générée (Tier 3)
- `/xp` `/niveau` (staff)

**Économie**
- `/balance` `/daily` `/work` `/pay` `/classement-argent`
- **Boutique** : rôles achetables avec ses pièces (`/boutique`)

**Automatisations & personnalisation**
- Rôles automatiques à l'arrivée
- Messages de bienvenue / départ personnalisables (texte, mention réelle, carte image Tier 3)
- Annonce de boost serveur
- **Rôles-Réactions** (paires multiples par message, mode exclusif)
- Messages récurrents
- Commandes personnalisées
- Réactions de mots automatiques
- Notifications sociales (YouTube)
- Anniversaires (`/anniversaire`)
- Signalements de membres (`/signaler`)
- Tickets de support (panneau à bouton)
- Giveaways (`/giveaway`)
- Suggestions (`/suggestion`)

**Fun & utilitaire**
- `/8ball` `/blague` `/morpion` `/pfc` `/ship` `/sondage` `/avatar`
- `/serverinfo` `/userinfo` `/botinfo` `/ping` `/help` `/rappel`

**Panel web**
- Rail de navigation façon Discord (bascule rapide entre serveurs)
- Sélecteurs de salon/rôle réels (plus de saisie d'ID à la main)
- Aperçu en direct des messages (bienvenue, départ, niveaux, boost)
- Nouvelle section Sécurité (anti-raid)

**Premium**
- 3 paliers (Tier 1/2/3) avec des avantages dédiés à chaque niveau — voir `/premium`
