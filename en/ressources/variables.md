---
description: >-
  List of available variables to use throughout the configuration of various
  systems in John-Bot.
---

# Variables

### User Variables

| Variable            | Description                                        | Example                                                                                     |
| ------------------- | -------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| {user}              | Displays the user's mention.                       | @User                                                                                       |
| {user.id}           | Displays the user's ID.                            | 982054684481167410                                                                          |
| {user.username}     | Displays the user's unique name (or name and tag). | exampleuser (or User#0001)                                                                  |
| {user.global\_name} | Displays the user's display name.                  | User                                                                                        |
| {user.avatar\_url}  | Displays the link to the user's avatar.            | https://cdn.discordapp.com/avatars/958547309728256081/c83207e3ef95fb6c9198562d0d04714f.webp |
| {user.banner\_url}  | Displays the link to the user's banner.            | https://cdn.discordapp.com/banners/958547309728256081/ebdcb6a0f0d8340a4c93549cc0925f9a.webp |

### Server Variables

| Variable               | Description                                   | Example                                                                                   |
| ---------------------- | --------------------------------------------- | ----------------------------------------------------------------------------------------- |
| {server.name}          | Displays the server name.                     | John-Bot                                                                                  |
| {server.id}            | Displays the server ID.                       | 959269961572962314                                                                        |
| {server.icon\_url}     | Displays the server's icon.                   | https://cdn.discordapp.com/icons/959269961572962314/01f8699526e02fd34266e07835bd1de5.webp |
| {server.member\_count} | Displays the number of members in the server. | 100                                                                                       |

### Panel Variables

| Variable     | Description              | Example |
| ------------ | ------------------------ | ------- |
| {panel.name} | Displays the panel name. | Support |

### Ticket Variables

| Variable        | Description                 | Example            |
| --------------- | --------------------------- | ------------------ |
| {ticket}        | Mentions the ticket.        | #ticket            |
| {ticket.id}     | Displays the ticket ID.     | 959269961572962314 |
| {ticket.name}   | Displays the ticket name.   | Ticket             |
| {ticket.number} | Displays the ticket number. | 10                 |

### Level Variabless

| Variable      | Description                                                  | Example      |
| ------------- | ------------------------------------------------------------ | ------------ |
| {level}       | Displays the member's new level when they level up.          | 5            |
| {reward.role} | Displays the role unlocked by the member when they level up. | Super Writer |

### Channel Variables (YouTube and Twitch)

| Variable            | Description                               | Example                                                                                                                                                                                                                                |
| ------------------- | ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| {channel.url}       | Displays the YouTube/Twitch channel link. | https://www.youtube.com/channel/UCZuEgzPq-NvOpd9NO0BGV5Q **OR** https://www.twitch.tv/minecraft                                                                                                                                        |
| {channel.name}      | Displays the YouTube/Twitch channel name. | Les Cowboys Fringants                                                                                                                                                                                                                  |
| {channel.icon\_url} | Displays the YouTube/Twitch channel icon. | https://yt3.ggpht.com/ytc/AIdro\_kW\_w6T3kawT7TZh99MUbevUopZLNhe\_5Mxag3RwTOg8mE=s800-c-k-c0x00ffffff-no-rj-mo **OR** https://static-cdn.jtvnw.net/jtv\_user\_pictures/c6284d38-5148-424b-a6cc-be06d2fc4aec-profile\_image-300x300.png |

### YouTube Variables

| Variable            | Description                     | Example                                                  |
| ------------------- | ------------------------------- | -------------------------------------------------------- |
| {video.title}       | Displays the video title.       | My Awesome YouTube Video                                 |
| {video.description} | Displays the video description. | Subscribe to my channel and follow me on social media!   |
| {video.id}          | Displays the video ID.          | q5mUj4KBOb0                                              |
| {video.thumbnail}   | Displays the video thumbnail.   | https://img.youtube.com/vi/q5mUj4KBOb0/maxresdefault.jpg |
| {video.duration}    | Displays the video duration.    | 2:46                                                     |
| {video.url}         | Displays the video link.        | https://www.youtube.com/watch?v=q5mUj4KBOb0              |

### Twitch Variables

| Variable                 | Description                                              | Example                                                                                                                                  |
| ------------------------ | -------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| {stream.title}           | Displays the stream title.                               | My Awesome Twitch Stream                                                                                                                 |
| {stream.thumbnail}       | Displays the stream preview thumbnail.                   | https://static-cdn.jtvnw.net/cf\_vods/d2nvs31859zcd8/7598d62e16e0c582f970\_minecraft\_42915955291\_1697387135/thumb/thumb0-1920x1080.jpg |
| {stream.game}            | Displays the game being streamed.                        | Minecraft                                                                                                                                |
| {stream.game\_icon\_url} | Displays the game cover of the stream.                   | https://www.youtube.com/watch?v=q5mUj4KBOb0                                                                                              |
| {stream.viewer\_count}   | Displays the number of viewers watching the stream live. | 1000                                                                                                                                     |
| {stream.url}             | Displays the stream link.                                | https://www.twitch.tv/minecraft                                                                                                          |

### Bluesky Variables

| Variable            | Description                                | Exemple                                                                                                                                 |
| ------------------- | ------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------- |
| {profile.url}       | Displays the Bluesky profile link.         | https://bsky.app/profile/bsky.app                                                                                                       |
| {profile.name}      | Displays the Bluesky profile display name. | Bluesky                                                                                                                                 |
| {profile.icon\_url} | Displays the Bluesky profile icon.         | https://cdn.bsky.app/img/avatar/plain/did:plc:z72i7hdynmk6r22z27h6tvur/bafkreihagr2cmvl2jt4mgx3sppwe2it3fwolkrbtjrhcnwjk4jdijhsoze@jpeg |
| {profile.handle}    | Displays the Bluesky profile username.     | bsky.app                                                                                                                                |
| {post.content}      | Displays the post content.                 | Welcome to my Bluesky account!                                                                                                          |
| {post.url}          | Displays the post link.                    | https://bsky.app/profile/bsky.app/post/3l6oveex3ii2l                                                                                    |
| {post.id}           | Displays the post ID.                      | 3l6oveex3ii2l                                                                                                                           |
