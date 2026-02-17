---
description: >-
  Découvrez tout ce qu'il faut savoir sur le système de créateur de messages de John-Bot. Apprenez à le configurer et comprenez son fonctionnement.
---

# Créateur de Messages

**Tutoriel vidéo lié à cette page :** [Créer et envoyer un embed modifiable sur Discord - Tutoriel #10](https://jnbt.xyz/fr/tutorials/embeds)

### :rocket: Introduction

Le système de créateur de messages vous permet d'envoyer des messages au nom de John-Bot. Ces messages pourront être modifiés ultérieurement et enrichis avec diverses options qui ne sont pas disponibles directement dans l'application Discord pour un utilisateur classique.

### :tools: Accéder au Créateur de Messages

Pour commencer, accédez au tableau de bord de John-Bot en utilisant la méthode de votre choix. Pour savoir comment faire, consultez ce guide : [Comment accéder au tableau de bord](../../guide/guide.md#pushpin-accéder-au-tableau-de-bord).

Ensuite, cherchez l'option `Messages` dans la colonne de droite, située sous le logo et la bannière de votre serveur. Vous arriverez alors sur une page où vous pourrez accéder à tous les paramètres nécessaires pour la création de votre premier message.

### :pencil: Paramètres d'un messsage

#### Créer un message

Pour créer un nouveau message, utilisez le bouton situé au bas de la liste des messages déjà existants, ou en haut de la page si c'est votre premier.

#### Dupliquer un embed

Vous pouvez aussi créer un message à partir d'un message existant pour conserver les mêmes paramètres et le personnaliser en le dupliquant (aussi appelé le "copier-coller") . Cela vous évite de devoir reconfigurer tous les paramètres pour une différence minime entre les deux messages. Pour ce faire, il vous suffit de cliquer sur le bouton `Dupliquer` correspondant à l'embed souhaité et de valider votre choix via la fenêtre qui s'affiche.

#### Modifier un message

Pour ajuster les paramètres d'un message déjà existant, il vous suffit de cliquer sur le bouton `Modifier` associé au message de votre choix dans la liste. Vous accéderez ainsi directement aux paramètres du message sélectionné pour effectuer vos modifications.

#### Supprimer un message

Pour supprimer un messsage existant, cliquez simplement sur le bouton `Supprimer` correspondant au message souhaité et validez votre choix via la fenêtre qui apparaît.

#### Modifier un message

Une fois dans les paramètres d'un message, vous pouvez modifier de nombreuses options pour le personnaliser selon vos besoins.

Une fois les configurations terminées, il vous suffit de cliquer sur le bouton vert `Enregistrer & modifier` situé en haut à droite de la fenêtre de configuration. Si vous ne souhaitez pas conserver vos modifications, cliquez simplement sur `Annuler`.&#x20;

#### Enregistrer et envoyer un embed

Une fois vos modifications terminées, si votre message n'a jamais été envoyé, vous devez créer l'embed correspondant dans le salon défini au préalable. Pour ce fairen utilisez le bouton vert `Créer` situé en haut à droite. Vous devrez ensuite l'envoyer dans le salon défini au préalable avec le bouton `Envoyer`.

#### Configuration d'un message

**Nom du message**

Le nom du message permet aux administrateurs du serveur de s'organiser dans le tableau de bord de John-Bot. Il ne sera pas visible par les membres. Pour le définir, écrivez-le dans le champ correspondant.

**Salon d'envoi**

Le salon d'envoi est le salon du serveur dans lequel sera envoyé le message. Pour le définir, choisissez le salon souhaité à l'aide du menu de sélection correspondant.

**Type d'envoi**

Vous avez le choix quant à la manière dont votre message sera envoyé. Sélectionnez simplement l'option qui correspond le mieux à vos besoins :

* **Message à envoi unique** : Ce message ne sera envoyé qu'une seule fois et sera progressivement noyé parmi les autres messages du salon.
* **Message persistant** : À chaque nouveau message posté dans le salon, John-Bot renverra votre message pour qu'il reste toujours visible et soit le dernier du salon. Si le message a déjà été envoyé auparavant, seule la version la plus récente sera conservée afin d'éviter de saturer le salon.

**Message texte**

Le message texte est le texte qui sera affiché hors de l'embed, comme un utilisateur Discord classique. Vous pouvez utiliser les emojis et le markdown¹ pour personnaliser votre texte. Pour désactiver le message texte, laissez le champ vide.

![Exemple de message avec le message texte mis en évidence](<../../.gitbook/assets/embed_message_partie texte.png>)

**Embed**

L'embed est la partie du message qui peut comporter plusieurs éléments personnalisables et qui sera affichée sous le message texte. Il est impossible à envoyer pour un utilisateur Discord classique. Vous pouvez utiliser les champs disponibles pour personnaliser votre embed.

![Exemple de message avec le message texte mis en évidence](<../../.gitbook/assets/embed_message_partie embed.png>)

* **Icône de l'auteur de l'embed :** Vous pouvez illustrer votre embed en ajoutant une image (qui peut être animée) à votre auteur, uniquement visible lorsque l'auteur a un nom.
* **Nom de l'auteur de l'embed :** Vous pouvez personnaliser votre embed en ajoutant un auteur, que vous pouvez nommer comme bon vous semble.
* **Lien de l'auteur de l'embed :** Vous pouvez personnaliser votre embed en ajoutant un lien vers un site externe à l'auteur.
* **Titre de l'embed :** Vous pouvez personnaliser votre embed en y ajoutant un titre.
* **Description de l'embed :** Vous pouvez personnaliser votre embed en y ajoutant une description.
* **Couleur de l'embed :** Vous pouvez choisir une couleur pour personnaliser votre embed à l'aide du sélecteur.
* **Lien de la vignette de l'embed :** Vous pouvez illustrer votre embed en y ajoutant une vignette.
* **Lien de l'image de l'embed :** Vous pouvez illustrer votre embed en y ajoutant une image.
* **Icône du footer de l'embed :** Vous pouvez compléter votre embed à l'aide d'une image de footer.
* **Texte du footer de l'embed :** Vous pouvez compléter votre embed à l'aide du footer.

***

1 : Découvrir ce qu'est le Markdown : [Markdown de Texte 101 (Formatage du chat : gras, italique, souligné)](https://support.discord.com/hc/fr/articles/210298617-Markdown-de-Texte-101-Formatage-du-chat-gras-italique-soulign%C3%A9)
