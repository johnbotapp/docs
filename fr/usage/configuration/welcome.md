---
description: >-
  Ici, vous trouverez des informations relatives à la configuration du système d'arrivées et de départs de John-Bot.
---

**Tutoriel vidéo lié à cette page :** [Configurer les actions d'arrivée et de départ de John-Bot - Tutoriel #3](https://youtu.be/XjmHGtcgMwU)

## :rocket: Introduction
Le système d'arrivées et de départs de John-Bot permet d'annoncer lorsqu'un membre rejoint ou quitte le serveur et de lui attribuer certains rôles automatiquement à son arrivée.

## :tools: Accéder à la configuration

### Accéder au tableau de bord

Tout d'abord, rendez vous sur le tableau de bord de John-Bot par le moyen de votre choix. Découvrez comment faire : [Comment accéder au tableau de bord](../../guide/base.md#pushpin-accéder-au-tableau-de-bord)

### Accéder aux paramètres

Ensuite, cherchez `Arrivées et départs` sur la colonne de droite, sous le logo et la bannière de votre serveur. Vous arrivez à présent sur une page où vous pouvez accéder à tous les paramètres relatifs au système d'arrivées et de départs.

## :inbox_tray: Message d'arrivée

Les messages d'arrivée sont des messages qui seront automatiquement envoyés lorsqu'un nouveau membre rejoint le serveur. Ils permettent d'annoncer l'arrivée d'un nouveau membre et sont entièrement personnalisables pour permettre d'inclure notamment le nombre de membres présents sur le serveur, la mention de l'utilisateur et bien plus.

![Exemple d'un message d'arrivée](../../.gitbook/assets/welcome_message%20d'arrivée_example.png)

### Configuration

#### Salon d'envoi

Dans ce champ, sélectionnez le salon qui recevra les messages d'arrivée à l'aide du menu déroulant associé.

#### Mise en forme

Dans cette catégorie, vous pouvez personnaliser le message qui sera envoyé lorsque un nouvel utilisateur rejoindra le serveur.

{% hint style="info" %}
Pour ajouter des éléments changeants tel que le nombre de membres présents sur le serveur, la mention de l'utilisateur et bien plus, vous pouvez utiliser les variables : [comment utiliser les variables](../../ressources/variables.md)
{% endhint %}

**Message texte**

Le message texte est le texte qui sera affiché hors de l'embed, comme un utilisateur Discord classique. Vous pouvez utiliser les emojis et le markdown¹ pour personnaliser votre texte. Pour désactiver le message texte, laissez le champ vide.

![Exemple de message d'ouverture avec le message texte mis en évidence](<../../.gitbook/assets/ticket\_message d'ouverture\_partie texte.png>)

**Embed**

L'embed est la partie du message qui peut comporter plusieurs éléments personnalisables et qui sera affichée sous le message texte. Il est impossible à envoyer pour un utilisateur Discord classique. Vous pouvez utiliser les champs disponibles pour personnaliser votre embed.

![Exemple de message d'ouverture avec l'embed mis en évidence](<../../.gitbook/assets/ticket\_message d'ouverture\_partie embed.png>)

* **Activer l'embed d'arrivée :** Vous pouvez cocher cette case si vous souhaitez activer l'embed dans votre message d'arrivée. Si vous souhaitez désactiver l'embed, décochez cette case.
* **Icône de l'auteur de l'embed** :gem: **:** Vous pouvez illustrer votre embed en ajoutant une image (qui peut être animée) à votre auteur, uniquement visible lorsque l'auteur a un nom.
* **Nom de l'auteur de l'embed** :gem: **:** Vous pouvez personnaliser votre embed en ajoutant un auteur, que vous pouvez nommer comme bon vous semble.
* **Lien de l'auteur de l'embed** :gem: **:** Vous pouvez personnaliser votre embed en ajoutant un lien vers un site externe à l'auteur.
* **Titre de l'embed :** Vous pouvez personnaliser votre embed en y ajoutant un titre.
* **Description de l'embed :** Vous pouvez personnaliser votre embed en y ajoutant une description.
* **Couleur de l'embed :** Vous pouvez choisir une couleur pour personnaliser votre embed à l'aide du sélécteur.
* **Lien de la vignette de l'embed :** Vous pouvez illustrer votre embed en y ajoutant une vignette.
* **Lien de l'image de l'embed :** Vous pouvez illustrer votre embed en y ajoutant une image.
* **Icône du footer de l'embed** :gem: **:** Vous pouvez compléter votre embed à l'aide d'une image de footer.
* **Texte du footer de l'embed** :gem: **:** Vous pouvez compléter votre embed à l'aide du footer.

## :outbox_tray: Message de départ

Les messages de départ sont des messages qui seront automatiquement envoyés lorsqu'un membre quitte le serveur. Ils permettent d'annoncer le départ d'un membre et sont entièrement personnalisables pour permettre d'inclure notamment le nombre de membres présents sur le serveur, la mention de l'utilisateur et bien plus.

![Exemple d'un message de départ](../../.gitbook/assets/welcome_message%20de%20départ_example.png)

### Configuration

#### Salon d'envoi

Dans ce champ, sélectionnez le salon qui recevra les messages de départ à l'aide du menu déroulant associé.

#### Mise en forme

Dans cette catégorie, vous pouvez personnaliser le message qui sera envoyé lorsque un nouveau membre quittera le serveur.

{% hint style="info" %}
Pour ajouter des éléments changeants tel que le nombre de membres présents sur le serveur, la mention de l'utilisateur et bien plus, vous pouvez utiliser les variables : [comment utiliser les variables](../../ressources/variables.md)
{% endhint %}


**Message texte**

Le message texte est le texte qui sera affiché hors de l'embed, comme un utilisateur Discord classique. Vous pouvez utiliser les emojis et le markdown¹ pour personnaliser votre texte. Pour désactiver le message texte, laissez le champ vide.

**Embed**

L'embed est la partie du message qui peut comporter plusieurs éléments personnalisables et qui sera affichée sous le message texte. Il est impossible à envoyer pour un utilisateur Discord classique. Vous pouvez utiliser les champs disponibles pour personnaliser votre embed.

* **Activer l'embed de départ :** Vous pouvez cocher cette case si vous souhaitez activer l'embed dans votre message de départ. Si vous souhaitez désactiver l'embed, décochez cette case.
* **Icône de l'auteur de l'embed** :gem: **:** Vous pouvez illustrer votre embed en ajoutant une image (qui peut être animée) à votre auteur, uniquement visible lorsque l'auteur a un nom.
* **Nom de l'auteur de l'embed** :gem: **:** Vous pouvez personnaliser votre embed en ajoutant un auteur, que vous pouvez nommer comme bon vous semble.
* **Lien de l'auteur de l'embed** :gem: **:** Vous pouvez personnaliser votre embed en ajoutant un lien vers un site externe à l'auteur.
* **Titre de l'embed :** Vous pouvez personnaliser votre embed en y ajoutant un titre.
* **Description de l'embed :** Vous pouvez personnaliser votre embed en y ajoutant une description.
* **Couleur de l'embed :** Vous pouvez choisir une couleur pour personnaliser votre embed à l'aide du sélécteur.
* **Lien de la vignette de l'embed :** Vous pouvez illustrer votre embed en y ajoutant une vignette.
* **Lien de l'image de l'embed :** Vous pouvez illustrer votre embed en y ajoutant une image.
* **Icône du footer de l'embed** :gem: **:** Vous pouvez compléter votre embed à l'aide d'une image de footer.
* **Texte du footer de l'embed** :gem: **:** Vous pouvez compléter votre embed à l'aide du footer.

## :robot: Rôles d'arrivée

Les rôles d'arrivée sont des rôles sélectionnés au préalable par les administrateurs qui seront attribués instantanément à un nouveau membre qui rejoint le serveur.

### Configuration

Pour définir les rôles qui seront attribués, choisissez ceux que vous souhaitez à l'aide du menu déroulant correspondant.

---
1 : Découvrir ce qu'est le Markdown : [Markdown de Texte 101 (Formatage du chat : gras, italique, souligné)](https://support.discord.com/hc/fr/articles/210298617-Markdown-de-Texte-101-Formatage-du-chat-gras-italique-soulign%C3%A9)