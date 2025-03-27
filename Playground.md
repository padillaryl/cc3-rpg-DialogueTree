### **Princess Diane Yvette (Heir to the State): In My Time of Need**
- **Quest picked up at:** When the player meets the princess on the way to the Upper City.
- **Step 0**
    - (Diane's questline ties directly with the player's reacquisition and learning about the Vermin Key) if the player chooses to explore the way to the Upper City (where all the nobility lives) early, they are stopped at the gate in a small fortress/drawbridge where the gate is guarded by Senior Knight Hans and a room to the left contains the Princess, who is distressed about the missing key. She doesn't know that the player is actually the one tasked to give her the key, but she tasks the player to go find it (this is basically a failsafe in case the player does not know what they're doing at all)
```mermaid
flowchart TD
  STEP1[Diane: Hm? I don't recall summoning a mercenary recently, what brings you here, sellsword?] --> STEP1A[Player: I heard about some key?] & STEP1B[Player: Goodbye. *Leave Diane*]
  STEP1A --> STEP2[Diane: Ah, yes... well since the courier is gone and done wherever I guess I can take anyone at this point. Tell me, are you good at finding things?] --> STEP2A[Player: Depends on who I need to find.] & STEP2B[Player: I know my way around.] & STEP2C[Player: Whatever you're offering, I'm not taking. *Decline quest.*]
  STEP2A --> STEP3A[Diane: You will not be finding anyone, I hope. I need you to find some THING, rather.] --> STEP3B
  STEP2B --> STEP3B[Diane: Put simply, a package addressed to me is late... or missing, I don't know anymore. I just want someone to go and find it, bring it back to me... you do not know how much this means to me. Will you take my offer?] --> STEP4A[Player: Alright, I'll find it.] & STEP4B[Player: Can you describe what I'll be looking for first?] & STEP4C[Player: No thanks. *Decline quest.*]
  STEP4B --> STEP5[Diane: I'm sorry to say that this package is highly confidential, but I will say this much: it can sway the fate of the entire state. I promise I will tell you more once you retrieve it.] --> STEP4A & STEP4C
  STEP2C & STEP4C --> DECLINE[Diane: Oh... what a shame. Perhaps you may reconsider in the future. In any case, I will wait here, gathering dust.]
  STEP4A --> STEPACCEPT[Diane: Oh thank you... you cannot mistake my package for anything else, it bears a symbol that looks like a small... mouse, yes. It should also have the courier guildmaster's seal on it... which reminds me, you should check there first for directions or clues. Good luck.]
```
- **Step 1 (Requires Vermin Key)**
    - Diane will thank the player for bringing back the key and says that she is willing to work with the player after they prove themselves and prove that they are prepared. To proceed, she tasks the player to complete 2 Lower District bounties from Magistrate Ken Nough OR 2 Wilderness bounties from Wenduag.
```mermaid
flowchart TD
  STEP1[Diane: Hello... have you found the key?] --> STEP1A[Player: Here it is. *PLEDGE ALLEGIANCE TO DIANE*] & STEP1B[Player: Not yet. *Leave Diane*] & STEP1C[Player: Goodbye. *Leave Diane*]
  STEP1A --> STEP2[Diane: Oh thank you so much... you have no idea how much this means to me... to everyone. Here is your reward... like I promised. Now I hope you don't mind, but I have another boon to ask you. You've proven yourself capable of chasing down this here key, but if you want to be more involved in it's journey, perhaps you would like to collaborate with me?] --> STEP2A[Player: What do you mean collaborate?] & STEP2B[Alright, what must I do?] & STEP2C[Player: I'll get back to you. *Leave Diane*]
  STEP2A --> STEP3A[Diane: Put simply, this key, the Vermin Key it's called, is extremely dangerous and powerful. Now I can't say the reason why yet, as you must earn my trust first, but trust me when I say that this here key is so much more than it seems. You can spend your life here... drifting around the capital, the wilds, wherever, but if you want to play a role in deciding this nation's fate, then we can do business.] --> STEP2B & STEP2C
  STEP2B --> STEP3[Diane: There's an old saying, a brittle alliance cannot be strengthened... it can only break. For us to establish a solid alliance, we must learn to trust each other. Go to the wilds or the lower district... both have their respective guardians or wardens... I want you to do 2 of their bounties for them... then we shall cooperate.] --> STEP4[Player: Understood. I'm ready to head out.] & STEP2C
  STEP4 --> STEP5[Diane: Good... I look forward to your return, as do we all.]
  STEP1C & STEP2C --> GOODBYE[Diane: Well get back to it then... for all of our sakes.]
```
- **Step 2**
    - Diane says that the player is now ready to be her partner for her plans for the state. She states her plans which are to drive out both the Thomasians and the Legion of Ahmed and push the state of Yrmania to independence for the good of the common people. She points out the flaws in both: although Thomasia seems like the benevolent and good faction their methods and their actual purpose for being in Yrmania is questionable and wrong, in addition she has a disdain for the Legion of Ahmed because as a woman, she has no future or even rights if Ahmed was to take over, not to mention women who are not even in the nobility. She also explains the true purpose of the Vermin Key: there is a defense system underground the state which is comprised of rats and the Vermin Key controls valves at specific areas that release the rats. She then tasks the player to accompany a guardian of hers to the Thomasian Pilgrimage site to spy on the Thomasian officials who are working there. If the player is not affliated with Stalker Svignee at this time, the player can then witness his cruelty in full-view: wherein he orders that those bullying and discriminating the Thomasian pilgrims be executed.
    - 650GP (or the currency decided) is rewarded upon completion.
```mermaid
flowchart TD
  STEP2START[Diane: You've returned. And from the look in your eyes, you've seen what our people endure daily.] --> STEP2A[Player: Those bounties were easy. What's next?] & STEP2B[Player: I've completed your request, now we proceed.] & STEP2C[Player: *Show her the bounty proofs silently*]

  STEP2A --> STEP2PLAN[Diane: *smiles faintly* Confidence suits you. Very well... you're ready to hear the truth. This key controls Yrmania's greatest defense: an underground network of... rats. Yes, voracious and aggressive rats. Thousands upon thousands, waiting beneath our feet. In fact, I have been waiting for this key ever since I was adopted by my stepfather, he was the one who had it constructed.]
  STEP2B --> STEP2PLAN
  STEP2C --> STEP2PLAN

  STEP2PLAN --> STEP2CRITIQUE[Diane: But before we speak of defenses or our plan, you must understand why we're to use them. So you should by now know the two sides: the Thomasians and the Legion, I'll give you a brief overview of why they are bad news. The Thomasians seem benevolent, but their 'faith' is just Borisya's fist in velvet gloves. And Ahmed? *her voice hardens* His 'liberation' would make chattel of every woman in Yrmania, liberation that would still condemn hundreds if not thousands of our people into slavery...] --> STEP2Q1[Player: *Question* You sound personal about Ahmed.] & STEP2Q2[Player: *Question* So we're fighting both factions?] & STEP2Q3[Player: *Question* Hang on... what's wrong with Thomasia? They seem nice.] & STEP2Q4[Player: *Question* Rats? You're joking.] & STEP2PROCEED[Player: Alright, what must I do?]

  STEP2Q1 --> STEP2ANSWER1[Diane: *coldly* I grew up in the slums before my adoption, so I know what it's like to live unpriveleged and without dignity. I know what happens to women under regimes like his, trust me... it's a fate worse than death. The nobility might buy protection, but the rest? *She grips the Vermin Key tightly* I won't allow that to happen, not while I draw breath.]
  STEP2Q2 --> STEP2ANSWER2[Diane: Not quite. Right now, the two of us stand no chance bringing down both of them, but our advantage is that they wouldn't expect a thing from us, so listen closely. It's inevitable that Ahmed will assault the capital, and Thomasia will be at the gates waiting for them... then, with the element of surprise, chaos, or what have you, we launch an attack that would cripple and drive out both forces. But first, we need numbers, and that is what we'll be doing while they stand and shake their fists at each other...]
  STEP2Q3 --> STEP2ANSWER3[Diane: Oh it might seem that way, but recall that there are no charities in the lower city or the slums, recall that their base of operations is right beyond that gate, in the Upper City... as a daughter of the Royal Family I have the privilege of knowing why they're here. The faith is being used to sway the nobles, sway my family into allowing Yrmania to be annexed... that's all the Thomasian presence here cares about. That is not to say Thomasia is evil, there's a reason why Borisya, the state it originates from, is so strong... but the Thomasian presence here is far too overextended and capture-driven to care about the people that need their help the most.]
  STEP2Q4 --> STEP2ANSWER4[Diane: *grim smile* My stepfather and his foreign collaborators were... thorough. These aren't common vermin or the ones you see running around in the streets. They're engineered to leave no flesh ungnawed, with a hunger no food can sate. Now passed down to me... to us, as a great weapon to use against invaders.]

  STEP2PROCEED --> STEP2MISSION

   STEP2MISSION[Diane: Here's what you'll do: accompany my guardian Elric to the pilgrimage site, it's now my turn to make sure that you trust me, otherwise our alliance wouldn't be so strong, now would it? Observe how the Thomasians treat their own.] --> STEP2CHOICE[Diane: If you see a strange armoured man, their Sanctified Stalker, they call him, then the show will truly begin... speaking of... don't you find it strange how they have someone named as such? More food for thought for you.]

  STEP2CHOICE --> STEP2C1[Player: Understood. Where do I meet Elric?] & STEP2C2[Player: *Question* Why not gather evidence publicly?] & STEP2C3[Player: *Question* This seems too cautious for someone with a rat weapon.] & STEP2C4[Player: *Nod silently and leave*]

  STEP2C1 --> STEP2END1[Diane: At the stables near the Lower District gate. *Hands you a purse* 650GP for your services thus far. And remember - we need witnesses, not martyrs. Observe only.]
  STEP2C2 --> STEP2END2[Diane: Possible, but shortsighted... remember that Thomasia and especially that Sanctified Stalker of theirs will catch wind of it very quickly, and they would not appreciate a blight forming in their new backyard.]
  STEP2C3 --> STEP2END3[Diane: *sharp laugh* The time for rats comes later. First we must show the people why they should stand with us before the gnawing begins... and mind you we can't just unleash them whenever we want, we still need to keep the common populace safe. They are contained underground for a reason, so we must do all we can to minimize the areas that we are to unleash the rats in.]
  STEP2C4 --> STEP2END4[Diane: *nods approvingly* A person of action. Elric will be waiting by the pilgrim tents. Don't keep him long.]

  STEP2END1 --> STEP2FINAL[Diane: Be quick... I have the next part of our plan laid out.]
  STEP2END4 --> STEP2FINAL
```
- **Step 3**
    - After sending the player to spy on the Thomasians, Diane will then task the player to accompany her to the center of the capital wherein she will give a speech and the player is meant to defend her. What happens is a skirmish starts after the Thomasians try to put down the small speech event. Diane will make a comment on "alright, that was not how I wanted that to go, but after that much people saw what happened, there is no doubt that their reputation will take a nose dive. they're starting to get aggressive, so soon it might be time for us to act."
    - 650GP (or the currency decided) and Truesight Amulet, a unique amulet that boosts ranged attacks is rewarded upon completion.
- **Step 4**
    - Diane receives news that the Legion of Ahmed is planning to attack the next village of Summonwater, so she tasks the player to aid the militia there. Afterwards, she will make a comment like "good. we will need every corner of Yrmania's support if we're to become independent. but for now we rest."
    - 650GP (or the currency decided) is rewarded upon completion.
- **Step 5 (Symbiosis)**
    - Diane tasks the player with going to Fort Faroth and requesting the aid of the army stationed there. She requests the player to make contact with Quartermaster A'jak'nir Jeera and request her support and loyalty diplomatically.
    - 800GP (or the currency decided) and Jeera's Arm, a unique armour piece that boosts strength is rewarded upon completion.
- **Step 6 (I Am What I Am: which requires completion of Symbiosis)**
    - Diane gets word that Ahmed himself has started negotiating an alliance and peace-deal with the de-facto leader of the slums, King Bennett. Diane says that she knows King Bennett from when she was still a child living in the slums and urges that the player accompany her and aid her in promising King Bennett to stay neutral or even aid Diane in the upcoming war.
    - 800GP (or the currency decided) and Bennett's Rapier, a unique rapier is rewarded upon completion.
- **Step 7 (Pre-finale)**
    - Just before Ahmed leads his massive assault on the capital and the Thomasians also rally their foreign Borisyan military to attempt and repel them, Diane asks the player once again to accompany and protect her for a speech in the capital, but this time the capital streets are full of militiamen, state soldiers, Upper City knights, and her personal guardians. She gives a rallying speech, making notes about "I know we are surrounded, but think of what we can achieve once this is all over..." and "this is our home... will you really allow the likes of Thomasia or Ahmed's barbarians to take it from you?". The crowd is roused and inspired, and Diane informs the player that whenever the fight may happen, Yrmania is ready.
    - 1000GP (or the currency decided) and Sceleritas Fel's Hat, a unique item that greatly increases initiative (or whatever turn order system, basically it helps you go first) is rewarded after the speech. Diane hands it to the player, gently stating "this was my first and favourite guardian's hat once. I remember the time when I was a sweet girl, when I entered the Upper City for the first time and he was there to greet me. Now I'm here, about to face my greatest challenge ever, I just wish he could be here to see me. Atleast you're here now."
 
      
