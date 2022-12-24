
# Welcome One, Welcome All!
Well, here you are on my GitHub page. What brings you here? Are you roaming looking for a potential employee? or a freelancer? or perhaps a friend? Firstly, you can check out my website to see what I offer [here](https://chezyname.github.io/portfollio/).
## About Me
Well, let's start a the beginning, How did I find myself in the joyous world of programming? It first started on the [Unity Game Engine](http://unity.com) and made some terrible games on there. Then I started working on a Multiplayer game on Unity and found out quickly that Unity does not have a netcode solution but relies on its community.

Then I started using [Roblox](https://www.roblox.com/users/151058724/profile#!/creations) Studio, they used Lua and had free networking, The downside is that I could not customize the net code and they only had local, and server scripts.

So After using Roblox, I started learning more languages that are useful, like Typescript, JavaScript, Rust, and C++. That's also when I started to learn different frameworks and [npm - *Node Package Manager*](https://www.npmjs.com/). After a couple of projects, I went over to Unreal Engine 4 learning how to create games with the *Industry Standard Tool* used by many of my Favorite gaming companies. *[Respawn Entertainment](https://www.respawn.com/)* and *[Riot Games](https://www.riotgames.com/en)*.

### What's Next?
My future is very important but also not limited. I've always loved games ever since I was a child, but I also don't want to specialize in a single field. I kind of want to bounce around different roles in the software engineering world, From a Game developer to a Systems developer, and so on.

# Projects:
Well, most of my projects are on [GitHub](https://github.com/ChezyName), but here are the most notable in order from when created.
> Heres a fair warning, Projects that are archived are usually left or forgotton / projects that were there for boredom / testing grounds.
  Archived projects could also be working but not garenteed.

## [Harmoney : Discord 2.0](https://github.com/ChezyName/Harmoney)
[Harmoney](https://github.com/ChezyName/Harmoney) spelled like that was my AP Computer Science project for the 'create task'. The app is honestly kind of cool and has documentation so you can create your own! It took around 2 weeks to completely develop and is currently *archived*. It has an auto-update feature whenever a GitHub release was detected and full customizability when it comes to themes. In reality, you can give the app a CSS file with custom variables and it will save it as a theme where you can load it and change it. The app was also  **Open Source**, meaning anyone can modify or make their app with the current codebase. For more information, check out the repository [here](https://github.com/ChezyName/Harmoney).

## Train Combat:
A Roblox game I made one day because I was bored, It's mostly a prototype but I'll eventually remake it in Unreal Engine or Unity,
### Gameplay & Gameloop,
The game loop was simple, There were 2 even teams on 2 separate trains with guns. The trains were on a track that would loop and their goal was to kill each other. 
### Future Updates?
If and **When** I remake this masterpiece, I would make guns apply to a single role instead of giving them any gun, I would also fix the netcode, the spawning, and other mechanics. Lastly, I would give the train a button to change tracks to allow for more forms of play.

## [Discord PauseBot](https://github.com/ChezyName/PauseBot)
A **Javascript** project that used **Discord.JS** in order to record people and able to send it back in a given text channel.
### How It Works?
Its Quite Simple, When the `npm start` is ran, the project will create the temp folders, and create the bot using the keys given inside `.env`, Then it will wait for either `/join`, `/pause target=@USER`, or `/pausev2 target=@USER` commands.

**Join Command:** The Bot joins the voice channel

**Pause Command** The bot will find all the audio snippets from the last 30 secords and combine them using **FFMPEG.** Once the files are combined it will send it to the user.

**Pausev2 Command** is about the same as the **Pause Command** but wont use **FFMPEG** as it may corrupt files sometimes. Instead it sends each induvidual file from the last 30s.

**Project Tree**
``` mermaid
stateDiagram-v2

  

OnStart --> CreateTempFolders

CreateTempFolders --> CreateBot

CreateBot --> `/join`

CreateBot --> `/pause[user]`

  
  

`/join` --> RecordVoices

RecordVoices --> SaveToFile

SaveToFile --> DeleteOldFiles

DeleteOldFiles --> RecordVoices

  

  

`/pause[user]` --> GetAllAudioSnippets

GetAllAudioSnippets --> CombineUsingFFMPEG

CombineUsingFFMPEG --> SendBackFinalAudioFile
```

# Future
Well, my future is clear and bright, so I'll update this file when my life gets a grand update, until then, chao.
![Github Snake](https://github.com/ChezyName/ChezyName/blob/main/githubsnake.svg?raw=true)
