# Discord Music Bot
Este é um projeto sobre um bot que toca músicas na plataforma discord.

## Como funciona:
Para iniciar o projeto, é necessário baixar o repositório em sua máquina. Depois execute o Lavalink.jar prompt de comando (Windows) ou no terminal (Linux):

```java -jar Lavalink.jar```

Após executar o lavalink, execute o programa:

```python launcher.py```

Posteriormente, basta apenas convidar o bot para seu canal do Discord.
Nome do Bot: MusicPlayerBot

## Comandos do Bot:

* prefix: ``` ! ou . ```
* Commands:
  * .connect: Connect the bot to the voice channel (You need to be connected to a voice channel)
  * .disconnect: Disconnect the bot from the voice channel.
  * .play <url>: Play the music that it was in URL.
  * .play <suggested-name-music>: Show a list of musics from Youtube for user choice
  * .play (when the playback is paused): Resume playback.
  * .stop: Stop the music and clear the queue.
  * .pause: Pause playback
  * .queue: Shows 10 musics starting to the current music.
  * .next: Jump to the next music in the queue.
  * .prev: Jump to the previous music in the queue.
  * .shuffle: Shuffle the queue except the current music.
  
