---
description: Retrouvez ici toutes les informations concernant la création de ville
---

# 🏠 Les villes

{% embed url="https://www.youtube.com/watch?index=1&list=PL1QLnkRl9WVyR0eGUtFoTo8a9MBJHBFwa&v=DQan4FHVdeM" %}
**Tuto : Créer et gérer votre propre ville sur Evolucraft**
{% endembed %}

**Les villes sont l'une des parties centrales du serveur. C'est à l'intérieur de celles-ci que vous pourrez stocker votre stuff, créer vos builds selon votre imagination ou encore installer vos fermes pour monter vos métiers ! À vous d'y créer le RP qui vous convient, selon ce que vous avez imaginé !**

## <mark style="color:green;">**💠 Comment être dans une ville ? 🏙️**</mark>

**Nous vous invitons à consulter ce petit tuto pour savoir comment : [<mark style="color:green;">Être dans une ville 🏙️</mark>](https://wiki.evolucraft.fr/le-gameplay/tuto-et-astuce/creer-une-ville)**

## <mark style="color:green;">**💠 Comment agrandir ma ville ? 📈**</mark>

**Agrandir votre ville vous permet d'étendre votre territoire afin de réaliser des constructions de plus en plus impressionnantes. C'est aussi un moyen, dans une quête secondaire, d'augmenter le niveau de votre ville.**

Pour l'agrandir, vous devez déposer de l'argent dans la banque de votre ville avec la commande <mark style="color:green;">**`/v bank deposit [montant]`**</mark>. À noter que le coût d'un claim dépend du niveau de votre ville.

Ensuite, en étant sur un chunk adjacent à votre ville, effectuez la commande <mark style="color:green;">**`/v claim`**</mark>. L'argent requis sera retiré de la banque de votre ville.

{% hint style="info" %}
🔎 <mark style="color:green;">**Remarque**</mark> : Pour visualiser les différents chunks, vous pouvez utiliser le raccourci clavier F3+G, ou, pour connaître la bordure de votre ville, la commande <mark style="color:green;">**`/v view`**</mark> vous permettra de mieux visualiser votre territoire !
{% endhint %}

Si vous vous **êtes trompé de chunk à claim** et souhaitez **retirer un claim précis**, vous pouvez **utiliser la commande <mark style="color:green;">`/v unclaim`**</mark> en étant **à l'intérieur du chunk concerné**. 

**Et voilà, vous avez un chunk de plus dans votre ville ! 🎉**

## <mark style="color:green;">**💠 Comment ajouter un membre dans ma ville ? 👩🏻‍🤝‍🧑🏽**</mark>

**Invitez vos amis à rejoindre la ville afin de vous aider à agencer votre ville ou même conquérir le monde d'Évolucraft !**

Pour cela, il vous suffit d'utiliser la commande <mark style="color:green;">**`/v invite [Pseudo]`**</mark>

L'autre joueur devra, quant à lui, utiliser la commande <mark style="color:green;">**`/v accept [Nom de votre ville]`**</mark> pour accepter l'invitation. Si le joueur a crashé ou s'est déconnecté durant l'action, il pourra toujours réaliser l'action par la suite.

Si vous vous êtes trompé dans l'invitation du joueur, vous pouvez supprimer l'invitation dans le <mark style="color:green;">**`/v`, divers, invitation puis appuyez sur votre touche de jet d'item en ayant votre souris sur la tête du joueur**</mark>

**Et voilà, vous savez comment faire rejoindre vos amis dans votre ville ! 😎**

## <mark style="color:green;">**💠 Comment supprimer ma ville ? ❌**</mark>

**Vous avez besoin de supprimer votre ville afin de rejoindre une autre ou pour une autre raison ? Voici un petit tuto ! Mais attention, cette action est irréversible 🚨!**

**Avant de supprimer votre ville, nous vous recommandons de <mark style="color:green;">reprendre l'argent de la banque de votre ville</mark> avec la commande <mark style="color:green;">`/v bank withdraw [montant]`</mark> ainsi que de récupérer le stuff dans <mark style="color:green;">vos coffres et vos items précieux</mark> ✨.**

{% hint style="warning" %}
Après la suppression de votre ville, il ne restera que les blocs posés ainsi que les coffres qui resteront inaccessibles jusqu'à ce qu'une personne claim par-dessus. Pensez également à faire supprimer les coffres privés afin de limiter les tickets en cas de surclaim 🤗.
{% endhint %}

**Une fois cela fait, vous pouvez utiliser la commande <mark style="color:green;">`/v disband`</mark> puis <mark style="color:green;">`/v disband --confirm`</mark> et votre ville sera automatiquement supprimée ! 😧**

## <mark style="color:green;">**💠 Les commandes diverses des villes 🕹️**</mark>

{% hint style="warning" %}
`[...]` Signifie que le paramètre est obligatoire

`<...>` Signifie que vous pouvez mettre une chaîne de caractères avec des espaces

`{...}` Signifie que le paramètre est optionnel
{% endhint %}

Voici les commandes à connaître pour gérer votre ville :

### 🔸`-`Globales 🌏

* <mark style="color:green;">**`/v create <nom de votre ville>`**</mark> : Crée votre ville.
* <mark style="color:green;">**`/v`**</mark> : Ouvre le menu de votre ville.
* <mark style="color:green;">**`/v sethome /v setspawn`**</mark> : Crée le point de téléportation de votre ville.
* <mark style="color:green;">**`/v home /v spawn`**</mark> : Se téléporte au home de votre ville.
* <mark style="color:green;">**`/v leave <nom de votre ville>`**</mark> : Quitte la ville choisie.
* <mark style="color:green;">**`/v info [nom de la ville]`**</mark> : Accède aux informations de la ville.
* <mark style="color:green;">**`/v select`**</mark> : Permet de choisir sa ville principale.
* <mark style="color:green;">**`/v pinfo [joueur]`**</mark> : Donne des informations concernant la ville du joueur.
* <mark style="color:green;">**`/v list`**</mark> : Donne la liste de toutes les villes présentes sur le serveur.
* <mark style="color:green;">**`/v player [joueur]`**</mark> : Donne les informations d'un joueur : ville, statut dans la ville, dernière connexion.
* <mark style="color:green;">**`/v disband --confirm`**</mark> : Supprime votre ville.

{% hint style="warning" %}
**Important 🚨**
Avant de confirmer la suppression de votre ville, pensez à récupérer l’argent de votre ville avec la commande `/v bank withdraw [montant]` et à récupérer le stuff qui s’y trouve dans votre ville !
{% endhint %}

### 🔸`-`Gestion des joueurs 👩🏻‍🤝‍🧑🏽

* <mark style="color:green;">**`/v add [joueur] /v invite [joueur]`**</mark> : Invite un joueur dans votre ville.
* <mark style="color:green;">**`/v accept [joueur]`**</mark> : Accepte la demande d'adhésion d'un joueur à votre ville.
* <mark style="color:green;">**`/v kick [joueur]`**</mark> : Retire un joueur de votre ville.
* <mark style="color:green;">**`/v ban [joueur]`**</mark> : Bannit un joueur de votre ville.
* <mark style="color:green;">**`/v unban [joueur]`**</mark> : Retire le ban du joueur visé.
* <mark style="color:green;">**`/v setrole [joueur] [rôle]`**</mark> : Modifie le rôle des joueurs présents dans votre ville.
* <mark style="color:green;">**`/v setowner [joueur]`**</mark> : Donne le rôle de maire au joueur désigné.

### 🔸`-`Gestion des claims 🗺️

* <mark style="color:green;">**`/v map`**</mark> : Donne la topographie des villes à l'endroit où vous vous situez.
* <mark style="color:green;">**`/v claim`**</mark> : Réclame le chunk sur lequel vous vous situez.
* <mark style="color:green;">**`/v unclaim`**</mark> : Retire le claim du chunk sur lequel vous vous situez.
* <mark style="color:green;">**`/v autoclaim`**</mark> : Réclame automatiquement les chunks sur lesquels vous marchez.
* <mark style="color:green;">**`/v view`**</mark> : Affiche la délimitation de votre ville avec des particules vertes.

### 🔸`-`Chat de ville 💬

* <mark style="color:green;">**`/v chat`**</mark> : Active le chat de votre ville.
* <mark style="color:green;">**`/v chat message`**</mark> : Écrit dans le chat de la ville sans l'activer.

{% hint style="success" %}
Votre futur royaume est à vos pieds !
{% endhint %}
