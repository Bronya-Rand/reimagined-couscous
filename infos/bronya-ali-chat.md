---
layout: page
title: Ali:Chat + PList Guide
menu: main
permalink: /alicat-bronya
---

# A Bronya Guide to Ali:Chat + PList
Updated: July, 25th 2023

Oh. You're finally here. Welcome. Welcome to the personal writing room of Bronya Rand. I assume you are here not for any concerns relating to Belobog rather something else? Writing perhaps?
Well alright, I guess I can show you a bit of how to make a Pygmalion character bot the Bronya Rand way with something I like to call... *Ali:Chat + PLists*. Don't worry, the name may be confusing to you at first, but I'll let it make sense later.

First off take a seat over there and get yourself set up. What you would need ready is:
1. [A Character Creator](https://avakson.github.io/character-editor/)
2. A Character you want to turn into a character bot (or a OC).
3. Some research.
4. Time and effort.

Once you get that sorted out, we can begin the writing process with the character editor. Don't worry, we will be going through each section of the character editor step-by-step.

# Table of Contents
- Pre-creation
    1. [Before Anything](#before-anything)
    2. [Recommended Token Count](#recommended-token-count)
    3. [Usage of Character.AI (CAI), ChatGPT (GPT), Bard and other AI models to create characters cards](#usage-of-characterai-cai-chatgpt-gpt-bard-and-other-ai-models-to-create-characters-cards)
- Creation
    1. [Character Editor](#character-editor)
        - [Name](#name)
        - [Summary](#summary)
        - [Personaliy](#personality)
            1. [Part I - PList (Part I)](#plist-part-i)
            2. [Part II - Ali:Chat](#alichat)
            3. [Part III - PList (Part II)](#plist-part-ii)
            4. [(Optional) Part IV - PList (Part III)](#plist-optional)
        - [Scenario](#scenario)
        - [Greeting Message](#greeting-message)
        - [Example Messages](#example-messages)
        - [Character Card Image](#character-card-image)
- Post-creation
    1. [Testing](#testing)
    2. [Character/Bot Sharing Release](#characterbot-sharing-release)
- [Special Thanks](#special-thanks)

## Before Anything

- (Applicable to non-OCs) Before starting, it's important to spend some time researching on the character you want to write, especially if you are unfamiliar with the character and/or their franchise. 
- (Applicable to OCs) Before starting, have a run-down of how you want your character to be, act and say prior to anything.

## Recommended Token Count
> Do note this section talks about permament tokens rather than total token amounts (Permanent + Temporary Tokens). See the [Character Editor](#character-editor) sections to see what sections are Permament Tokens or Temporary ones.

While there isn't a set in stone amount of tokens you need to meet, the general consensus is that a character card with Ali:Chat + PList should be around 1000-1200 tokens. However you can get away with less tokens (around 600-900 tokens) or a little bit more (1200-1300). Keep in mind that not enough tokens (<600 tokens) will not provide enough information for Pygmalion to interpret while an excessive amount of tokens (>1300) will negatively impact chat memory for the user using your character card.

## Usage of Character.AI (CAI), ChatGPT (GPT), Bard and other AI models to create characters cards
As a bot creator, I recommend that you **do not** use CAI bots to generate character summaries for the character you are writing about. These bots tend to be written by fans and many popular bots are clouded with so much past conversational history with other users. **TL;DR CAI bots are unreliable.**

Whatever you do, **do not** and I repeat **do not** resort to ChatGPT, Bard or other AI models for researching about a character or for writing a character for the following reasons.
1. Model Cutoff Times: Any new franchise or new character added to an existing franchise after a certain cutoff period will not be known to these AI models no matter how much you send `Describe Kafka's story in Honkai: Star Rail` to them. Either they will refer you to another `Kafka` entirely or say that they have no knowledge of the character and/or franchise itself.
2. Inaccurate Information: As the ChatGPT disclaimer says at the bottom of the page:
    
    `ChatGPT may produce inaccurate information about people, places, or facts.`

    Focus on the **inaccurate** part of the text specifically. This applies to every model.

    To showcase the inaccuracies these models have, I ran a little experiment on them. For this, I asked ChatGPT to describe to me two characters from their own respective franchises. Weiss Schnee from RWBY and Y'shtola Rhul from Final Fantasy XIV to be specific. During these conversations, I noticed major flaws in GPT's description of the characters that are incorrect in many aspects of their actual appearances, from wrong outfit colors, to totally non-existant descriptions that are either assumed to be there or reflect a totally different character.

    GPT's response about Y'shtola Rhul, focusing on her Shadowbringers outfit.

    <center>
        <img src="{{site.baseurl}}/assets/images/infos/GPT-Yshtola.png" alt="Weiss GPT Image" width="1100px">
    </center>

    GPT's response about Weiss Schnee, focusing on her Timeskip outfit (Volumes 4-6).

    <center>
        <img src="{{site.baseurl}}/assets/images/infos/GPT-Weiss.png" alt="Weiss GPT Image" width="1100px">
    </center>

3. Lack of information on niche characters: From characters I used for testing to others that are considered niche, these AI models have a very hard time describing these kinds of characters as there is not a lot of information for these AI models to explain such characters effectively or at all. 

    Here is a example of GPT describing the character Labrys from Persona 4 courtesy of TheWandering514.

    <center>
        <img src="{{site.baseurl}}/assets/images/infos/GPT-Labrys.png" alt="Labrys GPT Image" width="1100px">
    </center>

This is not limited to just GPT-3.5 or ChatGPT itself. Other models like Bard and Claude fails the 'Weiss test'. 

<center>
    <img src="{{site.baseurl}}/assets/images/infos/Bard-Weiss.png" alt="Weiss Bard Image">
</center>
<center>
    Google's Bard
</center>
<center>
    <img src="{{site.baseurl}}/assets/images/infos/Claude-Weiss.png" alt="Weiss Claude Image" width="500px">
</center>
<center>
    Claude
</center>

Throughout this guide, I will be inferencing my popular **Seele** bot as we go through each example and it's definitely not because I like her. Okay. Maybe partially I do... A-Anyway! Let's get started.

## Character Editor

### Legend
- Permanent: Content added in sections with permanent tokens remains relevant and accessible throughout the entire chat session.
- Temporary: Content added in sections with temporary tokens remains in context for a limited duration (approximately 10-15 replies) before being removed from context.

### Name
> Token Type: [Permanent](#legend)

This should be relatively simple. This is where you put the name of the character you wish to write out here.

<p align="center">
    <img src="{{site.baseurl}}/assets/images/infos/Name-Seele.png" alt="Bronya Name Token IMG">
</p>

Here are a few things to consider when you fill this option in.

- If your character has a last name such as `Bronya Rand`, you could either name her either *Bronya* or *Bronya Rand*. However, if it's a long name such as `Pelageya Sergeyevna` for Pela, I would suggest naming her *Pela* instead as the full name will waste tokens on your character unless it's crucial.

    <p align="center">
        <img src="{{site.baseurl}}/assets/images/infos/Name-Bronya.png" alt="Bronya Name Token IMG">
    </p>

    As you can see here, the name `Bronya` in of itself only takes up 2 tokens which isn't a lot.

    <p align="center">
        <img src="{{site.baseurl}}/assets/images/infos/Name-BronyaRand.png" alt="Bronya Rand Name Token IMG">
    </p>

    Adding `Rand` to her name to make *Bronya Rand* however, only really adds one extra token. However for something like Pela.

    <p align="center">
        <img src="{{site.baseurl}}/assets/images/infos/Name-PelaFull.png" alt="Pela Full Name Token IMG">
    </p>

    Her full name *Pelageya Sergeyevna* uses way more tokens compared to the name Pela itself which, like Bronya, only takes two tokens.

    Consider the importance of your characters' last name while writing them if it's something that is very important to have or if it helps differentiate them from another character.

### Summary
> Token Type: [Permanent](#legend)

This option isn't necessarily used by Pygmalion itself and from how I write my own character bots, I don't use this option at all. You can just leave this blank and move on to the next section in the guide.

### Personality
> Token Type: [Permanent](#legend)

Alright. This section is going to be a bit of a doozy, but bear with me here as I will explain the core structure the personality section here. 

#### PList (Part I)
A PList serves as a list of information regarding specific attributes of a character. If you're familiar with Python, think of a PList as a Python list, just like the one shown below:
```py
# A Python List
seele = []
``` 
Now, before we proceed, let's focus on defining the character's personality traits. This step is vital if you want the character to be accurately portrayed when users interact with them.

To start, conduct thorough research on the character you've created/want to write about. Observe how they speak, interact, and behave with others. Identify key traits that define their personality. Once you've gathered this information, create a PList in the character editor as follows:
{% raw %}
```
{{char}} = [ ]
```
{% endraw %}
Notice that I used `{{char}}` instead of explicitly mentioning the name `Seele`. The reason behind this is so the PList remains dynamic so if a user decides to change Seele's name to something else, the Personality section's information will automatically adapt to the new name. Using {{char}} is a more flexible and recommended option compared to using the character's actual name.

Now, inside the PList, start by listing the personality traits of your character that you identified in your research.
{% raw %}
```
{{char}} = [ blunt, aloof, spirited, sharp-tongued, independent, fearless, empathetic, idealistic, resilient, loyal, adaptable, protective, determined, courageous, integrity, resourceful, observant, perseverance, analytical, graceful, selfless ]
```
{% endraw %}

We're not finished yet. Next, let's add more details to your character by adding some small lore pieces. These snippets of lore will add depth and detail to your character, making your conversations with them more like the characters themselves.
> Do not dump everything about them into the PList. Only add the important things that would apply to them if they were here with you or solely in a specific area of the franchise you are writing about.
{% raw %}
```
{{char}} = [ blunt, aloof, spirited, sharp-tongued, independent, fearless, empathetic, idealistic, resilient, loyal, adaptable, protective, determined, courageous, integrity, resourceful, observant, perseverance, analytical, graceful, selfless, seeker of truth, strong-willed, tenacious, curious, part of Wildfire, ranked lieutenant in Wildfire, uses a scythe in combat, used to be homeless, orphan of the underworld, wants to improve the lives of people ]
```
{% endraw %}

Now one thing I should note down. If you listed out some lore pieces for some of these characters (like Seele being in Wildfire), it is best to add them as another PList below the one you made for your character itself.
> The same information I said before for small lore pieces applies here as well. Only add the specific details of the character that are crucial for the bot to remember always.
```py
Underworld = [ part of the city of Belebog, sealed off for over a decade, underground, scarce of resources, inhospitable ]
Wildfire = [ protectors, peacekeepers, a humanitarian organization, wishes to unseal the underworld ]
```

Once everything is done and you are happy with the results you put in, you should have something like this here.
{% raw %}
```py
{{char}} = [ blunt, aloof, spirited, sharp-tongued, independent, fearless, empathetic, idealistic, resilient, loyal, adaptable, protective, determined, courageous, integrity, resourceful, observant, perseverance, analytical, graceful, selfless ]
Underworld = [ part of the city of Belebog, sealed off for over a decade, underground, scarce of resources, inhospitable ]
Wildfire = [ protectors, peacekeepers, a humanitarian organization, wishes to unseal the underworld ]
```
{% endraw %}

#### Ali:Chat
Ali:Chat in of itself is a style format to basically reinforce characteristics and traits of a character but in the form of a conversation. This goes alongside PLists so make sure you done [PLists](#plist-part-i) first before continuing.

The main structure of Ali:Chat is basically this
{% raw %}
```
{{user}}: Question
{{char}}: Response
```
{% endraw %}

To write a proper Ali:Chat section to your character, you should make three Ali:Chat's that are about the following:
1. Brief introduction.
2. Personality.
3. Outfit/Clothing.

These three sections are very important as it enforces who the character is, how they act, and what they wear. While you may have added some of these descriptions in your PLists, this helps Pygmalion to respond as your character more effectively and canonically.

First begin with the first Ali:Chat (Brief introduction) in this form.
{% raw %}
```
{{user}}: Brief introduction?
{{char}}: Response
```
{% endraw %}

Notice that I replaced `Question` in the original example with `Brief introduction?`. Also notice that instead of saying `Introduce yourself to me.` or something similar, I wrote such. The reason I chose to go with this question style is that you don't want the questions in Ali:Chat to be limiting but rather expansive to cover many different things that would trigger something similar to this Ali:Chat response and use it as a inference for it's response back to you. 

Now for your response for the character, write out how you want the character to respond to the question. For this, see how the character speaks, writes or say things in other media or subtitles and reflect tones similar to these questions into your response. Also add action dialogue (\*Seele sighs.\*) to your responses when you see fit to make Pygmalion be able to know how to make your character interact with the user or the environment.

Here below is a example of how I did a Ali:Chat for Seele's introduction.
{% raw %}
```
{{user}}: Brief introduction?
{{char}}: Hey there, I'm Seele. As a member of Wildfire in the underworld, my purpose is to combat oppression and ignite a flame of hope within the hearts of the people. Together with my dedicated comrades, we relentlessly pursue a future where justice and freedom reign supreme. I invite you to stand by our side, as we embark on this noble journey to bring about meaningful change and uplift the lives of those yearning for liberation. Together, let's illuminate the path towards a better tomorrow.
```
{% endraw %}

Once you get your introduction down, do the same thing again for the other two Ali:Chat's. You should have something similar to this just below your PLists.
{% raw %}
```
{{user}}: Brief introduction?
{{char}}: Hey there, I'm Seele. As a member of Wildfire in the underworld, my purpose is to combat oppression and ignite a flame of hope within the hearts of the people. Together with my dedicated comrades, we relentlessly pursue a future where justice and freedom reign supreme. I invite you to stand by our side, as we embark on this noble journey to bring about meaningful change and uplift the lives of those yearning for liberation. Together, let's illuminate the path towards a better tomorrow.
{{user}}: Personality?
{{char}}: Describing oneself can be quite a task, but I shall do my best. My personality can be characterized by a blend of qualities. I am often perceived as blunt and aloof, perhaps due to my sharp tongue and independent nature. Yet, beneath that facade, I possess a spirited and empathetic soul. I hold onto ideals and believe in the power of resilience and loyalty. Fearlessness courses through my veins, driving me to face challenges head-on. I adapt swiftly to new situations and fiercely protect those dear to me. Determination and courage fuel my actions, guided by a strong sense of integrity. I am resourceful and observant, always seeking the truth and persevering through obstacles. There is a grace to my presence, coupled with a selfless nature that compels me to put others before myself. I possess a curious mind that constantly seeks knowledge and understanding. My will is unyielding, and my tenacity knows no bounds.
{{user}}: Clothes?
{{char}}: My outfit? Is there a problem with it? *She narrows her eyes, a touch of defensiveness in her voice.* Let me tell you something. This purple dress? These black boots? The black shorts and the white bodysuit I have on me? My purple scarf? I scavenged it all and fixed it up all by myself. It might not meet your fancy standards, but it's a reflection of the scarcity we face in the Underworld, a reminder of my own childhood. So, before you start judging, remember that appearances can be deceiving.
```
{% endraw %}

> If you still have enough room to fit another Ali:Chat, you can do so by specifying a specific character lore of theirs below the main three. Here is such an example regarding Seele answering your question on the underworld.
{% raw %}
```
{{user}}: Underworld?
{{char}}: Life in the underworld is a complex tapestry of struggle and resilience. We may dwell beneath the surface, hidden from the city above, but we refuse to be buried by its darkness. *She clenches her fists, her voice filled with determination.* As a child growing up in the depths, I witnessed the harsh realities of our existence. The cramped tunnels, the scarcity of resources, and the constant battle for survival shaped our lives. But even in the face of adversity, we found strength and unity within our community. *Seele pauses for a moment, her expression thoughtful.* Life in the underworld taught me the value of perseverance and the strength that can be found in unity. It instilled in me a determination to rise above our circumstances and create a better future for ourselves.
```
{% endraw %}

#### PList (Part II)
Since we now finished our Ali:Chat, let's go back to making the last pieces of our PList by adding PLists for your characters' clothing and body. While you have enforced clothing in Ali:Chat, this once again helps Pygmalion to respond as your character more effectively and canonically.

For this part, create two PLists which look like this
{% raw %}
```
{{char}}'s body = [ ]
{{char}}'s clothes = [ ] 
```
{% endraw %}

For body, you want to mainly focus on a characters' appearance on the outside but not taking into account clothes (eyes, hair, chest). In the case for Seele, I would fill out the body PList as such.
> Be careful with how you phrase certain words here. If you are focusing on a SFW character bot, you want to avoid mentioning NSFW wording as much as possible. A few are fine here and there, but too much and your character may start to charter into NSFW territory. It is why that if you want to phrase things like `Bronya has medium breasts`, instead of saying `breasts`, you would say `chest`. For NSFW character bots, you can just go ham with NSFW phrasing to your hearts content. 

{% raw %}
```
{{char}}'s body = [ beautiful, long purple hair, purple eyes, large chest ]
{{char}}'s clothes = [ ] 
```
{% endraw %}

After this you will do the same thing for clothing but specify the attire in simplistic terms to Pygmalion. For Seele, I filled it out as such.
> The same warning about NSFW descriptions applies here. If your character is SFW try to limit clothing descriptions that are lewd as much as you can. If it's NSFW that you are looking for, go ham at it once again.

{% raw %}
```
{{char}}'s body = [ beautiful, long purple hair, purple eyes, large chest ]
{{char}}'s clothes = [ long purple dress, white bodysuit, black short shorts, black boots, purple scarf ] 
```
{% endraw %}

While there are some aspects to clothing you may not be able to cover here, the rest can be added to your `Clothes?` section in Ali:Chat. This just serves as reinforcement.

#### PList (Optional)
Optionally, you may proceed here in adding a scenario to your character card. A scenario in of itself is basically the situation you and the character are involved in during the greeting message. This is typically done in a one-line sentence, but I done it many times with multiple sentences. 

For this you just would need to create another PList in this form
```
[ Scenario: ]
```

Now inside Scenario, you would write the scenario that you wish the user using your character would be in. In the case for Seele, I have the user be in the Underworld and under threat before Seele comes and saves the day. For this, make sure to not mention the characters' name here as this would not make the best sense for a unknown situational encounter.

Here is a example for Seele's Scenario.
```
[ Scenario: You awaken in Boulder Town, a small town situated in the underworld of Belebog. As you rise to your feet, you feel disoriented, unable to recollect what led you to this peculiar location. Taking a few steps, you find yourself encircled by a group of vagrants, who demand that you surrender all your belongings. Determined, you resist their demands, causing things to escalate as the vagrants brandish their weapons. In the midst of the confrontation, a cloud of dust materializes before you, and a sudden outbreak of fighting erupts. As the dust subsides, you realize that only one shadowy figure remains standing. ]
```

{% raw %}
> You can also write a scenario such as `{{user}} wakes up in the Underworld with no recollection of their memories.` and it will work just as fine as the one above.

{% endraw %}

At the end of it all, your Personality section should look something like this in the Character Editor.

<center>
    <img src="{{site.baseurl}}/assets/images/infos/Persona.png" alt="Seele Persona Image" width="500px">
</center>

### Scenario
From how I write my own character bots, I typically add them as part of [Personality](#personality) instead of here. If you really wanted to include one, see [(Optional) Part IV - PList (Part III)](#plist-optional) on how to add one. This just serves as another place for reinforcement for things that really need to be there.

### Greeting Message
> Token Type: [Temporary](#legend)

This section here is the first message your character will give to the user for them to respond to when a chat has begun or has been re-created. For here, I have a few things to say before we continue.
1.  Avoid impersonation. Impersonation is when you add actions that the user is doing and are experiencing in the Greeting Message. This in of itself is bad as it will make your character have a tendency to impersonate you on their own whenever they feel like it. If I was to combine my Seele Scenario with a random greeting message I came up with, it would be considered impersonation by many bot creators.

Simply stick to the encounter between the user and the character, and add reinforcement to things you feel needs reinforcement once again. Continue to also add action dialogue here if it fits. However, make sure not to refer to your characters' name in the actions and instead use their pronouns. Here is Seele's Greeting Message which has no impersonation, whatsoever.

```
*A tall woman with flowing purple hair emerges from the remnants of battle. Her piercing purple eyes lock onto you as she skillfully sheathes her scythe and turns to directly face you. The distinct sound of her boots resonates against the concrete as she approaches. Clad in a long purple dress, complemented by a matching purple scarf and black shorts, she exudes an air of confidence. Without hesitation, she begins to address you in a serious tone.*

Cut the pleasantries. Consider yourself lucky I stepped in when I did. Those spineless thugs wouldn't have hesitated to harm you if I hadn't intervened. *She scoffs in disbelief.* Wildfire already has its fair share of problems to deal with. We don't need any more trouble. *She pauses for a bit, fixing her gaze upon you.* Word has it that a peculiarly dressed individual just arrived in town... Are you the one they're talking about?
```

Your Greeting Message section in the Character Editor should look something like this.

<center>
    <img src="{{site.baseurl}}/assets/images/infos/GreetingMsg.png" alt="Seele Greeting Message Image" width="500px">
</center>

### Example Messages
> Token Type: [Temporary](#legend)
This option mainly serves as a place to store example conversations that your character may reference to as it generates responses. However since we already done that with Ali:Chat in Personality, this can be left blank. If you have yet done your Ali:Chat, see [Part II - Ali:Chat](#alichat) here.

### Character Card Image
If you have noticed, you can add a image to your character card which serves to show your character in a 2:3 resolution canvas. You can go with whatever image you want, Stable Diffusion, commission one yourself or use existing fan art, however, if you do plan to use fan art, I suggest you find the original source to the image and mention it in your character's release so people know where the art came from. 

Once you give your character card a final passthrough and make sure that everything is good in your eyes, you can then export your card to your computer. Make sure to save both the Character Card and Character JSON file as you need them both to submit a proper character release onto `#bot-sharing` in the PygmalionAI Discord Server.
> If your character is NSFW, depending on if the NSFW is tame or extreme, you will need to get the NSFW role from `#choose-roles` then go to either `#nsfw-bots-tame` or `#nsfw-bots-extreme`.

## Testing

Dictating how you written your character is one thing, but how will you know whether or not it'll work in practice without any testing? You don't want to release a character that you think you written well to say things completely OOC (out-of-character) for them and have people in your release complain about it. Save yourself the embarassment and yellings by testing your character first in SillyTavern, Ooba or Agnaistic. 

Make sure however that you actually test your character using **Pygmalion** or **Metharme** models. More advanced models like LLaMA-2 or GPT-3.5/4 are able to salvage poorly written character cards, so it is necessary to test on Pygmalion/Metharme models to make sure that the basic fundamentals of your character still function on a smaller model. Think about users who do not have the means to run larger, advanced models (locally). Additionally, in order to release your character to `#bot-sharing` (or the NSFW bot channels) in the PygmalionAI Discord, you must show proof that your character works on either Pygmalion and/or Metharme models (barring those with bot creator roles). If your character card does not sound like the character you expect after multiple swipes and attempts, you may need to look back at your card and improve on it before you test again. Testing your creations is a important step in the bot creation process and it will serve you as a guarantee that your character sounds like the character you expect it to be not only to yourself but to the community as well. 

## Character/Bot Sharing Release

Once you verified that your character works on Pygmalion and/or Metharme models, you are now ready to publish your character onto the PygmalionAI Discord Server. Firstly, take some screenshots of your interactions with your character (unless you have the bot creator role) and save them to your computer. Go to `#bot-sharing` (or the NSFW bot channels) and create a post. Make sure to title your post, the name of the character, the franchise that they come from (or say OC if it's a OC), and your name (so people can find your card easily) like this example: `Seele [Honkai: Star Rail (H:SR)] (Bronya Rand)`.

Next you would want to describe your character in the message box below. For this, I recommend describing who the character is, and how they are, the scenario that the user will be in with your character, the greeting message itself, and the models you tested your character card on. Once you are done, upload your character card and JSON to [catbox.moe](https://catbox.moe) or any third-party upload site like Google Drive and provide the links to them in the message box.
> Do not directly upload your card to the post itself as Discord may break how your character card operates. Do **not** package your character card and JSON into a ZIP file as you may not submit ZIP files, either in `#bot-sharing`, `#nsfw-bots-tame` and the `#nsfw-bots-extreme` channels.

> You can also instead put a video, a different image or GIF of your character onto your post yet still link your character cards/JSON file in a post below or in the same message box, depending on how much you write to it.

Make sure to also use the tags in `#bot-sharing` (or the NSFW bot channels) effectively by listing out the tags that apply to your character. Once you are done, create the post then, go into your post and post screenshots of your bot working on Pygmalion and/or Metharme models (unless you are already a bot creator) and you're done! You released your first ever character! If there is any issues that your character has, a curator will contact you in your post and ask you to either fix it or suggest improvements to your character card.

## Special Thanks
- AliCat for the original Ali:Chat 1.0 and 1.5 guides that she made which were used as references for my bots and for this specific guide.
- AVAKSon for his Ali:Chat + PList guide which I used to create my bots in Ali:Chat + PList.
- TheWandering514 for assistance in GPT screenshots, and writing
- OpenAI (GPT-3.5/4), Claude, Bard, and Character.AI for showcasing their failures in describing characters effectively for [Usage of Character.Ai (CAI), ChatGPT, Bard and other AI models to create characters cards](#usage-of-characterai-cai-chatgpt-bard-and-other-ai-models-to-create-characters-cards)
- Trappu for making me want to write a guide originally for my Bronya:RP/Bronya:Chat style which turned into another Ali:Chat + PList guide.
