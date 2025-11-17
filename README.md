
# Nexus Bot 🎮🤖


Nexus Bot est un **bot Discord fun et personnalisable**, conçu pour ajouter des commandes interactives et ludiques à votre serveur. Que vous soyez un administrateur à la recherche d’outils pour animer votre communauté ou un développeur souhaitant contribuer, Nexus Bot est peut-être fait pour vous !

---

## ⚠️ Informations importantes

> ⚠️ **Note sur le code** :
> Une grande partie du code a été générée avec l’aide d’une IA. Cela peut entraîner la présence de bugs ou de code redondant. **Vos contributions sont les bienvenues** pour améliorer la qualité et la stabilité du projet !

- **Maintenance** : Les mises à jour sont occasionnelles. N’hésitez pas à forker le projet pour ajouter de nouvelles fonctionnalités !
- **Licence** : Ce projet est sous [LICENSE](LICENSE). Merci de prendre connaissance du fichier avant fork.

---

## 🚀 Installation

### Prérequis

Vous pouvez utiliser l'instance offerte [ici](https://discord.com/oauth2/authorize?client_id=1361669045463548034) (plus de détails à propos de l'instance dans la partie FAQ) ou l'installer vous-même.

- Un **token Discord** pour le bot (à créer sur le [Portail Développeur Discord](https://discord.com/developers/applications)).
- **Python** installé.
- Et une machine pour faire tourner le bot.

### Étapes
1. **Clonez le dépôt** :
   ```bash
   git clone https://github.com/Creatif-France-Games/nexus-bot.git
   cd nexus-bot
   ```

2. **Installez les dépendances** :
   ```bash
   pip install -r requirements.txt
   ```

3. **Configurez votre environnement** :
   - Créez un fichier `.env` à la racine du projet.
   - Ajoutez votre token Discord :
     ```
     DISCORD_TOKEN=votre_token_ici
     ```

4. **Lancez le bot** :
   ```bash
   python bot.py
   ```

🎉 **Félicitations** ! Nexus Bot est maintenant en ligne !

---

## 🛠️ Fonctionnalités

Notez que toutes les commandes ne sont pas listées ici.

| Catégorie                     | Commande                     | Description                                                                                     |
|-------------------------------|------------------------------|-------------------------------------------------------------------------------------------------|
| **Utilitaires et Fun**        | `/de`                        | Lance un dé avec un nombre de faces de votre choix (par défaut 6).                            |
|                               | `/compliment`                | Envoie un compliment aléatoire à un utilisateur.                                               |
|                               | `/ping`                      | Affiche la latence du bot.                                                                      |
|                               | `/statusbot`                 | Change le statut du bot avec un message personnalisé.                                           |
|                               | `/blague`                    | Obtient une blague aléatoire.                                                                   |
|                               | `/8ball`                     | Posez une question, la boule magique répond.                                                   |
|                               | `/devine`                    | Devinez un nombre entre 1 et 10.                                                                |
|                               | `/pileface`                  | Lance pile ou face.                                                                             |
|                               | `/chifoumi`                  | Pierre, feuille ou ciseaux contre le bot.                                                      |
|                               | `/bombe`                     | Effectue un compte à rebours avant une explosion.                                               |
|                               | `/respiration_exercice`      | Lance un exercice de respiration guidée (1 minute).                                            |
|                               | `/qr`                        | Génère un code QR à partir d’un texte ou d’une URL.                                            |
|                               | `/temperature`               | Affiche la température d’une ville.                                                            |
|                               | `/rickroll`                  | Envoie un Rickroll en message privé à un membre.                                                |
| **Modération**                | `/clear`                     | Supprime un nombre spécifique de messages *(réservé aux modérateurs)*.                         |
|                               | `/bannir`                    | Bannit un utilisateur avec une raison *(réservé aux administrateurs)*.                         |
|                               | `/kick`                      | Expulse un utilisateur du serveur avec une raison *(réservé aux administrateurs)*.             |
|                               | `/mute`                      | Rend un membre muet pour une durée spécifiée *(réservé aux administrateurs)*.                  |
|                               | `/spam`                      | Spamme 50 fois un message pour tester les protections anti-spam *(réservé aux administrateurs)*. |
| **Gestion des Salons**       | `/salon_prive_temporaire`    | Crée un salon textuel privé temporaire *(effacé après 1 heure)*.                                |
|                               | `/ajouter_membre_salon`      | Ajoute un membre à votre salon privé temporaire.                                               |
|                               | `/dire`                      | Envoie un message personnalisé dans le canal *(réservé aux administrateurs)*.                  |
|                               | `/embed`                     | Envoie un message sous forme d’embed avec une couleur bleue *(réservé aux administrateurs)*.     |
| **Informations**              | `/infobot`                   | Affiche les informations du bot.                                                                |
|                               | `/infoserveur`               | Affiche des informations détaillées sur le serveur.                                            |
|                               | `/infomembre`                | Affiche des informations sur un membre du serveur.                                             |
|                               | `/avatar`                    | Affiche l’avatar d’un membre.                                                                   |
|                               | `/serveurs`                  | Affiche les serveurs MultiCraft de CF Games.                                                     |
|                               | `/pubcoolos`                 | Affiche des informations sur Cool OS.                                                           |
|                               | `/contact`                   | Affiche le salon de contact.                                                                    |
|                               | `/reglement`                 | Affiche le règlement du serveur.                                                                 |
| **Outils Administratifs**     | `/envoyer_news`              | Envoie une annonce dans le salon dédié *(réservé aux administrateurs)*.                       |
|                               | `/securisation`              | Active la sécurisation temporaire du serveur *(réservé aux administrateurs)*.                  |
|                               | `/securisation_fin`          | Désactive la sécurisation du serveur *(réservé aux administrateurs)*.                          |
|                               | `/maintenance`               | Active le mode maintenance pour une durée et une raison données *(réservé aux administrateurs)*. |
|                               | `/nouvel_article`            | Annonce un nouvel article sur le site *(réservé aux administrateurs)*.                         |
| **Multimédia**                | `/radio`                     | Joue une station de radio dans votre salon vocal.                                               |
| **Minuteur**                  | `/minuteur`                  | Lance un minuteur avec un nom personnalisé.                                                     |
|                               | `/annule_minuteur`           | Annule votre minuteur en cours.                                                                 |

---

## 🤝 Contribuer

Si vous savez un peu coder, c'est très gentil à vous de contribuer. Voici les règles à respecter :

- À chaque ajout ou modification que vous faites, faites un commentaire afin de voir que c'est vous.
- Testez vos modifications avant de soumettre.

---

## 💬 Communauté

- **Besoin d’aide** ? Ouvrez une [issue](https://github.com/Creatif-France-Games/nexus-bot/issues) sur GitHub.
- **Envie de discuter** ? Rejoignez notre [serveur Discord](discord.gg/Zzcb9j8BTJ).

---

## 📜 Licence

Consultez le fichier [LICENSE](LICENSE).

---

## 🙋 FAQ

### Puis-je installer Nexus Bot sur mon serveur ?
✅ **Oui** ! Deux solutions sont disponibles actuellement :
- Utiliser l'instance offerte : cette instance peut être non stable et avoir quelques bugs, le bot n'ayant pas été développé par des professionnels. Voici le lien : [Inviter Nexus Bot](https://discord.com/oauth2/authorize?client_id=1361669045463548034).
- L'héberger vous-même : c'est la meilleure solution. De plus, vous avez un contrôle total.

### Une fonctionnalité manque ?
Ouvrez une [issue](https://github.com/Creatif-France-Games/nexus-bot/issues) ou proposez une Pull Request !

---

**Merci d’utiliser Nexus Bot** ! N’hésitez pas à ajouter une étoile pour nous soutenir !