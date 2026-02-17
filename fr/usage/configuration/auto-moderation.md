---
description: >-
  Découvrez ici comment configurer le système de modération automatique de John-Bot !
---

# Auto-moderation

**Tutoriel vidéo lié à cette page :** [Modérer efficacement son serveur avec John-Bot - Tutoriel #5](https://jnbt.xyz/fr/tutorials/moderation)

### :rocket: Introduction

Un système d’auto-modération sur Discord est un outil indispensable pour maintenir un environnement sain et sécurisé sans nécessiter une surveillance humaine constante. Il permet de définir des règles précises que John-Bot appliquera automatiquement en fonction des comportements détectés sur le serveur.

Le système d’automodération de John-Bot s’articule autour de trois catégories principales : les auto sanctions ; les signalements et les logs de modération.

Vous pourrez également personnaliser de nombreux paramètres pour adapter le système à vos besoins : choix des sanctions, configuration des seuils de détection (par exemple, nombre de messages répétés en un temps limité), salons exclus, ou encore la présentation des signalements et logs.

### :tools: Accéder aux paramètres du système

Pour commencer, accédez au tableau de bord de John-Bot en utilisant la méthode de votre choix. Pour savoir comment faire, consultez ce guide : [Comment accéder au tableau de bord](../../guide/guide.md#pushpin-acc%C3%A9der-au-tableau-de-bord).

Ensuite, cherchez `Modération` sur la colonne de droite, sous le logo et la bannière de votre serveur. Vous arrivez à présent sur une page où vous pouvez accéder à tous les paramètres relatifs au système de modération automatique.

### :hammer: Les sanctions automatiques

Pour créer votre première sanction automatique, vous devez en définir les différents paramètres. Lorsqu’un membre atteint un certain nombre d’avertissements, John-Bot appliquera automatiquement la sanction prévue à son encontre.

#### Choix de la sanction

Vous devez d’abord choisir une sanction qui sera appliquée automatiquement par John-Bot lorsqu’un membre aura atteint un certain seuil d’avertissements. Pour cela, sélectionnez celle que vous souhaitez dans la liste et complétez éventuellement avec une durée si nécessaire.

Une sanction peut prendre plusieurs formes et nécessiter une précision de durée. Voici la liste exhaustive des sanctions que John-Bot peut appliquer :

* Avertir : le membre reçoit un message privé l’informant de son avertissement. John-Bot conserve une trace de cet avertissement, accessible via la commande `/warnings list` ou dans les logs.

* Réduire au silence : le membre est totalement censuré sur le serveur pendant une durée déterminée (maximum 28 jours consécutifs). Il ne pourra ni envoyer de messages, ni rejoindre les salons vocaux, ni réagir, ni interagir d’aucune manière. Toutefois, il pourra toujours consulter les messages du serveur.

* Expulser : le membre est éjecté du serveur, mais pas définitivement. Il peut le rejoindre à nouveau à tout moment s’il dispose d’une invitation ou si le serveur est public.

* Bannir : le membre est éjecté du serveur de façon définitive et ne peut plus le rejoindre, sauf si un modérateur choisit de lever le bannissement avec la commande `/unban`.

* Bannir temporairement : identique à un bannissement classique, mais limité dans le temps. Après une durée définie (maximum 365 jours consécutifs), l’utilisateur peut rejoindre à nouveau le serveur s’il possède une invitation ou si le serveur est public.

#### Choix des conditions

Pour que la sanction sélectionnée précédemment s’applique, un membre du serveur devra avoir accumulé un certain nombre d’avertissements, qu’ils soient appliqués automatiquement par John-Bot ou manuellement par des modérateurs.

Vous pouvez définir le nombre d’avertissements à accumuler sur une période donnée pour déclencher la sanction automatique.

### 🚨 Signalements

Le salon de réception global des logs permet d'accueillir un grand nombre d'événements au même endroit. Vous devez d'abord définir le salon de réception global dans le champ correspondant. Vous pouvez ensuite choisir les événements qui seront envoyés dans ce salon en cochant les cases associées dans la liste sous la `configuration globale de la couleur des embeds du système`. Si vous souhaitez activer tous les événements, cachez simplement la case `Activer ou désactiver tous les événements`.

### Salon⸱s ignoré⸱s

Toutes les actions effectuées dans les salons ignorés ne seront pas répertoriées dans les logs, tous les événements confondus. Pour définir un ou plusieurs salons ignorés, sélectionnez-en parmi la liste dans le champ correspondant.

### Couleur globale :gem:

Cette option vous permet de définir la couleur des embeds de logs qui seront envoyés sur le serveur. Pour ce faire, sélectionnez la couleur souhaitée parmi les 6 propositions ou à l'aide du sélecteur de couleurs.



### Salons spécialisés

Pour chaque événement du système, vous pouvez définir un salon spécifique. Pour cela, choisissez l'événement que vous souhaitez et définissez un salon à l'aide du menu déroulant correspondant.

{% hint style="warning" %}
Si le salon de réception global est configuré sur le même salon qu'un ou plusieurs événements spécifiques, les messages de logs seront envoyés en double.
{% endhint %}
