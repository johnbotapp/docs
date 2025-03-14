---
description: >-
  Liste des variables disponibles à utiliser à travers la configuration des
  différents systèmes de John-Bot
---

# Variables

### Variables de Date

| Variable    | Description                                         | Exemple    |
| ----------- | --------------------------------------------------- | ---------- |
| {date}      | Affiche la date actuelle sous forme : `JJ/MM/AAAA`. | 04/03/2024 |
| {date.time} | Affiche le temps actuelle sous forme : `HH:MM`.     | 09:22      |
| {timestamp} | Affiche l'horodatage actuel.                        | 1741098205 |

### Variables de l'Utilisateur

| Variable            | Description                                                   | Exemple                                                                                     |
| ------------------- | ------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| {user}              | Affiche la mention de l'utilisateur.                          | @Utilisateur                                                                                |
| {user.id}           | Affiche l'identifiant de l'utilisateur.                       | 982054684481167410                                                                          |
| {user.username}     | Affiche le nom unique (ou le nom et le tag) de l'utilisateur. | exempleutilisateur (ou Utilisateur#0001)                                                    |
| {user.global\_name} | Affiche le nom d'affichage de l'utilisateur.                  | Utilisateur                                                                                 |
| {user.nickname}     | Affiche le surnom de l'utilisateur sur le serveur.            | Modérateur - Utilisateur                                                                    |
| {user.avatar\_url}  | Affiche le lien de l'avatar de l'utilisateur.                 | https://cdn.discordapp.com/avatars/958547309728256081/c83207e3ef95fb6c9198562d0d04714f.webp |
| {user.banner\_url}  | Affiche le lien de la bannière de l'utilisateur.              | https://cdn.discordapp.com/banners/958547309728256081/ebdcb6a0f0d8340a4c93549cc0925f9a.webp |

### Variables du Serveur

| Variable               | Description                                         | Exemple                                                                                   |
| ---------------------- | --------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| {server.name}          | Affiche le nom du serveur.                          | John-Bot                                                                                  |
| {server.id}            | Affiche l'identifiant du serveur.                   | 959269961572962314                                                                        |
| {server.icon\_url}     | Affiche l'icône du serveur.                         | https://cdn.discordapp.com/icons/959269961572962314/01f8699526e02fd34266e07835bd1de5.webp |
| {server.member\_count} | Affiche le nombre de membres que compte le serveur. | 100                                                                                       |

### Variables du Panneau

| Variable              | Description                                                   | Example               |
| --------------------- | ------------------------------------------------------------- | --------------------- |
| {panel.name}          | Affiche le nom du panneau.                                    | Support               |
| {panel.reopening\_at} | Affiche la date à laquelle le panneau sera de nouveau ouvert. | 20 janvier 2025 07:00 |

### Variables du Ticket

| Variable        | Description                      | Exemple            |
| --------------- | -------------------------------- | ------------------ |
| {ticket}        | Mentionne le ticket.             | #ticket            |
| {ticket.id}     | Affiche l'identifiant du ticket. | 959269961572962314 |
| {ticket.name}   | Affiche le nom du ticket.        | Ticket             |
| {ticket.number} | Affiche le numéro du ticket.     | 10                 |

### Variables de Niveaux

| Variable      | Description                                                                     | Exemple        |
| ------------- | ------------------------------------------------------------------------------- | -------------- |
| {level}       | Affiche le nouveau niveau du membre lors de son passe d'un niveau à l'autre.    | 5              |
| {reward.role} | Affiche le rôle débloqué par le membre lors de son passe d'un niveau à l'autre. | Super écrivain |

### Variables de la Chaîne (YouTube et Twitch)

| Variable            | Description                                  | Exemple                                                                                                                                                                                                                                |
| ------------------- | -------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| {channel.url}       | Affiche le lien de la chaîne YouTube/Twitch. | https://www.youtube.com/channel/UCZuEgzPq-NvOpd9NO0BGV5Q **OU** https://www.twitch.tv/minecraft                                                                                                                                        |
| {channel.name}      | Affiche le nom de la chaîne YouTube/Twitch.  | Les Cowboys Fringants                                                                                                                                                                                                                  |
| {channel.icon\_url} | Affiche l'icône de la chaîne YouTube/Twitch. | https://yt3.ggpht.com/ytc/AIdro\_kW\_w6T3kawT7TZh99MUbevUopZLNhe\_5Mxag3RwTOg8mE=s800-c-k-c0x00ffffff-no-rj-mo **OU** https://static-cdn.jtvnw.net/jtv\_user\_pictures/c6284d38-5148-424b-a6cc-be06d2fc4aec-profile\_image-300x300.png |

### Variables YouTube

| Variable            | Description                         | Exemple                                                  |
| ------------------- | ----------------------------------- | -------------------------------------------------------- |
| {video.title}       | Affiche le titre de la vidéo.       | Ma super vidéo YouTube                                   |
| {video.description} | Affiche la description de la vidéo. | Abonnez-vous à ma chaîne et suivez moi sur les réseaux ! |
| {video.id}          | Affiche l'identifiant de la vidéo.  | q5mUj4KBOb0                                              |
| {video.thumbnail}   | Affiche la miniature de la vidéo.   | https://img.youtube.com/vi/q5mUj4KBOb0/maxresdefault.jpg |
| {video.duration}    | Affiche la durée de la vidéo.       | 2:46                                                     |
| {video.url}         | Affiche le lien de la vidéo.        | https://www.youtube.com/watch?v=q5mUj4KBOb0              |

### Variables Twitch

| Variable                 | Description                                              | Exemple                                                                                                                                  |
| ------------------------ | -------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| {stream.title}           | Affiche le titre de la diffusion en direct.              | Mon super live Twitch                                                                                                                    |
| {stream.thumbnail}       | Affiche la prévisualisation de la diffusion en direct.   | https://static-cdn.jtvnw.net/cf\_vods/d2nvs31859zcd8/7598d62e16e0c582f970\_minecraft\_42915955291\_1697387135/thumb/thumb0-1920x1080.jpg |
| {stream.game}            | Affiche le nom du jeu de la diffusion en direct.         | Minecraft                                                                                                                                |
| {stream.game\_icon\_url} | Affiche la pochette du jeu de la diffusion en direct.    | https://www.youtube.com/watch?v=q5mUj4KBOb0                                                                                              |
| {stream.viewer\_count}   | Affiche le nombre de spectateurs de diffusion en direct. | 1000                                                                                                                                     |
| {stream.url}             | Affiche le lien de la diffusion en direct.               | https://www.twitch.tv/minecraft                                                                                                          |

### Variables Bluesky

| Variable            | Description                                     | Exemple                                                                                                                                 |
| ------------------- | ----------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| {profile.url}       | Affiche le lien du profil Bluesky.              | https://bsky.app/profile/bsky.app                                                                                                       |
| {profile.name}      | Affiche le nom d'affichage du profil Bluesky.   | Bluesky                                                                                                                                 |
| {profile.icon\_url} | Affiche l'icône du profil Bluesky.              | https://cdn.bsky.app/img/avatar/plain/did:plc:z72i7hdynmk6r22z27h6tvur/bafkreihagr2cmvl2jt4mgx3sppwe2it3fwolkrbtjrhcnwjk4jdijhsoze@jpeg |
| {profile.handle}    | Affiche le nom d'utilisateur du profil Bluesky. | bsky.app                                                                                                                                |
| {post.content}      | Affiche le contenu de la publication.           | Bienvenue sur mon compte Bluesky !                                                                                                      |
| {post.url}          | Affiche le lien de la publication.              | https://bsky.app/profile/bsky.app/post/3l6oveex3ii2l                                                                                    |
| {post.id}           | Affiche l'identifiant de la publication.        | 3l6oveex3ii2l                                                                                                                           |
