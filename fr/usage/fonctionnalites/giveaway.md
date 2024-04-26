---
description: >-
  Ici, vous trouverez des informations sur la création et la configuration de
  giveaways ou concours.
---

# Giveaway

**Tutoriel vidéo lié à cette page :** [Organiser un giveaway sur son serveur avec John-Bot - Tutoriel #8](https://youtu.be/UsfRXtH8Rcg)

## :rocket: Introduction

Un giveaway est le moyen parfait pour récompenser vos membres en mettant en jeu un lot et en laissant le hasard décider. En effet, un giveaway est simplement un concours sous forme de loterie. Les participants peuvent s'inscrire via un simple bouton, et le tirage au sort est effectué au moment choisi.

Il existe deux façons de créer un giveaway : l'une est rapide mais moins personnalisable, tandis que l'autre est plus personnalisable mais nécessite plus de temps et de précision. Choisissez celle qui vous convient le mieux en les comparant, et découvrez comment les mettre en place.\
Découvrez également comment interagir avec un giveaway pour y participer, ainsi que les commandes de gestion d'un giveaway.

## :zap: Méthode rapide et simple

Si vous souhaitez créer un giveaway rapidement et efficacement, optez pour cette méthode.

Tout d'abord, accédez au serveur dans lequel vous souhaitez lancer le giveaway. Assurez vous d'avoir la permission administrateur.\
Ensuite, entrez la commande /giveaway create. Vous aurez accès à plusieurs options :

* Vous devez choisir la durée du giveaway, c'est-à-dire le laps de temps qui s'écoulera avant le tirage au sort automatique et l'annonce des résultats.\
  Pour ce faire, entrez le nombre de seconde·s, de minute·s, d'heure·s ou de jour·s, suivis de l'unité (s pour seconde, min pour minute, h pour heure et d pour jour).
* Vous devez choisir le nombre de gagnants qui seront sélectionnés pour recevoir la récompense mise en jeu. Entrez simplement un nombre entier supérieur à 0.
* Vous devez choisir le prix que vous souhaitez faire gagner aux gagnants. Le champ est totalement libre ; entrez simplement le nom du prix, qu'il soit matériel, virtuel ou autre.
* Enfin, vous pouvez choisir le salon dans lequel devra se dérouler le giveaway s'il diffère du salon dans lequel vous êtes en train d'entrer la commande pour paramétrer le giveaway. Cette option est donc facultative ; si vous la laissez vierge, le giveaway sera lancé directement dans le salon où la commande a été envoyée.

![Exemple d'une configuration avec la commande /giveaway create](../../.gitbook/assets/giveaway\_command\_create.png)

## :tools: Méthode plus complète et personnalisable

Si vous souhaitez créer un giveaway complexe et poussé en intégrant des éléments originaux, optez pour cette méthode.

### Accéder au tableau de bord

Tout d'abord, rendez vous sur le tableau de bord de John-Bot par le moyen de votre choix. Découvrez comment faire : [Comment accéder au tableau de bord](../../guide/base.md#pushpin-accéder-au-tableau-de-bord)

### Accéder aux paramètres

Ensuite, cherchez `Giveaways` sur la colonne de droite, sous le logo et la bannière de votre serveur. Vous arrivez à présent sur une page où vous pouvez visualiser tous les giveaways de votre serveur, qu'ils soient terminés ou en cours.

### Créer et configurer

Vous arrivez sur la page qui vous permettra de configurer votre giveaway. Voici comment configurer les différents paramètres :

#### Nom

Dans ce champ, choisissez le nom qui peut définir votre giveaway. Il sera affiché dans le titre du message envoyé ainsi que sur le tableau de bord pour pouvoir le repérer parmi les autres.

#### Salon d'envoi

Dans ce champ, choisissez où le giveaway sera envoyé et visible par les membres. Après l'envoi du giveaway, vous ne pourrez plus modifier le salon.

#### Récompense

Dans ce champ, choisissez le prix que vous souhaitez mettre en jeu. Le champ est totalement libre ; entrez simplement le nom du prix, qu'il soit matériel, virtuel ou autre. Il est impossible d'automatiser la distribution du gain, vous devrez vous en occuper manuellement.

#### Date de fin

Ce champ permet de définir la date et l'heure exacte du tirage au sort. À cette date, un message sera envoyé automatiquement en réponse au message originel du giveaway pour annoncer le ou les gagnant·s.

#### Nombre de gagants

Dans ce champ, définissez combien de membres pourront être déclarés vainqueurs de la récompense mise en jeu.

#### Nombre maximum de participants :gem:

Dans ce champ, vous pouvez choisir de limiter le nombre de membres qui peuvent s'inscrire au tirage au sort.

#### Affichage de la liste des participants

Vous pouvez désactiver l'affichage de la liste des participants en décochant la case associée.

{% hint style="info" %}
Découvrez comment fonctionne ce bouton dans la partie [interaction directe avec la giveaway]\(giveaway.md#interaction-directe-avec-le-giveaway).
{% endhint %}

#### Rôles autorisés & ignorés

Dans ces deux champs, vous pouvez restreindre le giveaway à certains rôles ou, au contraire, interdire certains rôles de participer au giveaway.\
Pour cela, sélectionnez les rôles souhaités dans le menu déroulant correspondant.

#### Embed

La partie `embed` permet de mettre en forme le message qui sera envoyé et visible par le membre dans le salon.\
Vous pouvez le personnaliser à votre guise à l'aide des nombreuses options proposées.

#### Bouton :gem:

La partie `bouton` permet de personnaliser le bouton qui sera joint au message du giveaway et qui permet aux membres de participer au giveaway.\
Vous pouvez le personnaliser à votre guise à l'aide des nombreuses options proposées tel que la couleur, le texte affiché ou encore l'emoji affiché.

### Finaliser et envoyer

Une fois votre giveaway entièrement configuré, vérifiez que tout est correct et cliquez sur le bouton vert situé en haut à gauche, `Créer & Envoyer`. Votre giveaway sera envoyé et démarré dans le salon précisé avec toutes ses personnalisations. Il est conseillé de rédiger un message d'annonce pour mentionner à vos membres si le giveaway est organisé en l'honneur d'un événement important.

## :gear: Fonctionnement du giveaway

### Informations sur le giveaway

Dans le message embed, vous retrouverez certaines informations relatives au giveaway. Voici des explications pour chaque information disponible sur le message.

* **Nom ou titre** : Vous pouvez retrouver le nom du giveaway en titre de l'embed (partie supérieure en gras titré).
* **Date et heure de fin** : Vous pouvez retrouver le temps restant ainsi que la date et l'heure auxquelles se terminera le giveaway. Le champ correspondant est `Se termine :`, situé sous le titre dans le corps de l'embed. Le champ se renomme `S'est terminé` dès lors que le giveaway est terminé.
* **Auteur du giveaway** : Vous pouvez prendre connaissance de l'utilisateur à l'origine du giveaway. Son compte Discord est directement identifié dans le champ `Lancé par :`.
* **Nombre de participants** : Vous pouvez connaître le nombre de membres qui sont inscrits au tirage au sort dans le champ `Participants :`.
* **Nombre de gagnants ou gagnant·s** : Vous pouvez connaître le nombre de membres qui seront déclarés vainqueurs du lot après le tirage au sort dans le champ `Gagnants`. Ce champ affiche ensuite le·s gagnant·s en mention.

### Interaction directe avec le giveaway

#### Bouton participer

Vous pouvez vous inscrire au tirage au sort avec le bouton personnalisable par l'auteur du giveaway situé sous l'embed du giveaway, à gauche du bouton `Participants`.

#### Bouton participants

Vous pouvez consulter la liste des personnes inscrites au tirage au sort en cliquant sur le bouton `Participants` situé sous l'embed du giveaway, à droite du bouton de participation.

{% hint style="info" %}
Découvrez comment configurer ce bouton dans la partie [créer et configurer](giveaway.md#creer-et-configurer) de cette page.
{% endhint %}

![Exemple d'un message classique de giveaway](../../.gitbook/assets/giveaway\_example.png)

### Commandes

| Commande         | Description                                   |
| ---------------- | --------------------------------------------- |
| /giveaway create | Lance un giveaway.                            |
| /giveaway delete | Supprime un giveaway.                         |
| /giveaway end    | Termine un giveaway.                          |
| /giveaway list   | Affiche la liste des giveaways du serveur.    |
| /giveaway reroll | Choisi de nouveaux gagnants pour un giveaway. |