---
name: Discord Translation Bot
tools: [Java, Hackathon]
image: "/assets/images/Discordbot/picture.jpg"
description: A discord bot that translates messages between languages
sequence: 4
---
#### <b>Discord Translation Bot<b>
<p style="font-size:12px; color:#808080;padding: 0 0 1em 0;">Anna Chen, Kyle Burgess, Johnothan Ngoy</p>
<p style="font-size:15px; padding: 0 0 1em 0;">October, 2021</p>
During the fall of our freshman year of college, myself and a few friends decided to participate in our campus’s “VandyHacks” 2021 Hackathon. Our idea: making a Discord Bot to translate messages between languages. Being nearly halfway through CS 1103: Intro to Java, we knew we were a little bit behind the 8-ball. Having only one night to complete this project, we got to work. 
<br><br>
In case you are unaware, Discord is a social platform used to communicate via both voice and text channels. You can join or create servers with your friends and communicate in real time. You can also host/purchase “bots” that sit in a server for you and respond to stimulus. There are thousands of bots that have been made over the years and they each serve a different purpose, playing music, watching videos, sending pets, etc.. The prevalence of bots both causes and is caused by improvements to Discord’s Bot API. It has plenty of documentation, which makes it much less daunting of a task to work on.
<br><br>
The second thing we needed to look into was the method of translation. We ended up using Google Translate’s API, mostly because it is the first name that anyone thinks of when computerized translation comes up. Luckily, being Google, the Translation API was pretty plug and play. 
<br><br>
We started individually, making one program that hosted a bot in our private server and another translating text that we input. After minor tweaks, we got each to work and give us the outputs that we needed out of each. At this point it was as simple as patching the two together into one functioning program. With some difficulty (mostly caused by the fact that we were learning concepts as we were introducing them), we managed to get it to work. 
<br><br>
Our original version used text commands such as “!translate” to indicate that a message needed to be translated. Though this was a good proof of concept, we quickly realized some drawbacks to this model. It required us to either have a command to switch your preferred language or using commands like “!langtranslate” to translate to a specified language. This is very clunky and it requires 2 messages in the text stream (one by the user request and another by the bot). To improve the user feel, we instead replaced this with a system where you could react to a message with the flag of a country. That message would be translated to the primary language of that country. Though it is not a perfect system, it looks and feels much better to use. And with that, our night/morning was finished.
<br><br>
Overall this was a fun experience and it exposed us to so many new ideas and concepts that we otherwise would not have seen for a while. Though it didn’t make us experts, I feel as though I grew a lot as a computer scientist as a result of taking part in this. If you would like to check this out for yourself, check out my Github linked below.
