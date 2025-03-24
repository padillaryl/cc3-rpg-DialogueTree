```mermaid
flowchart TD

  A[You approach the group of guards stationed at the grounds. They immediately stop you in your tracks.]
  A --> B[Tower Guard 1: Halt! Stop where you are right now!]
  B --> C[Tower Guard 2: Yeah, what he said! You wouldn't want an arrow in your head now, would you?]
  C --> D[Tower Guard 3: Maybe not like what she said, but one more step and maybe you'll have one.]

  D --> E[Player: I'm just here to ask a question.]
  D --> F[Player: Woah now, I'm not an idiot to take 3 people at once now. Just needed to ask a question.]
  D --> G[Player: Yeah, no. *Leave*]

  G --> H[Tower Guard 2: Yeah, that's what I thought! See that? Hah! Only words!]
  H --> I[Tower Guard 3: Yeah, words. That, and your arrow pointed at his head.]

  J[*If player returns* Tower Guard 1: Halt! Stop right there!]
  J --> K[Tower Guard 2: Wait a minute, You again? You really want that arrow in your head, huh?]
  K --> L[Tower Guard 3: Stop with the arrow!]

  L --> M[*Reuse dialogue Choices]
  M --> E & F & G

  E & F --> N[Tower Guard 1: What is your question?]
  N --> O[Tower Guard 3: Just don't take a step forward.]

  O --> P[Player: Have you seen anyone passing by who bears this emblem? *Show Emblem*]
  O --> Q[Player: *Take a step forward*]

  Q --> R[The 2nd tower guard shoots her arrow at you and fortunately, it missed. Maybe you shouldn't do that again if you wanna keep that head of yours.]
  R --> S[Tower Guard 2: T-that was only a warning shot! I didn't miss or anything!]
  S --> T[Tower Guard 3: You threaten someone only for you to miss? Very impressive.]

  P --> U[Tower Guard 2: Throw it over! We don't have eyes of an hawk, you eejit.]
  U --> V[Player: *Throw Emblem Over*]
  U --> W[Player: No, I don't think so. *Don't Throw Emblem Over*]

  W --> X[Tower Guard 2: We're not thieves, y'know? Just throw it over!]
  X --> V

  V --> Y[You threw the emblem over to the tower guards' side. The archer didn't catch it in time and instead, the emblem hit her in the head. You can see the other tower guard snickering.]
  Y --> Z[Tower Guard 2: Yeah, yeah. I almost had it y'know?]

  Z --> A1[Silence followed as the tower guards examined the emblem.]

  A1 --> B1[*If the company is present in this place*: Tower Guard 2: Yeah, we've seen some. They set up camp near here.]
  B1 --> C1[She, and one of the tower guard, approaches you and gives you directions to the Company's camp site.]
  C1 --> D1[You thank them and asked for the emblem. The archer gives it to you halfway before being snatched back.]
  D1 --> E1[Tower Guard 2: Ah ah. Pay up first.]
  E1 --> F1[The other tower guard snatches the emblem and gives it back to you.]
  F1 --> G1[Tower Guard 2: Aw, no fair.]
  G1 --> H1[You thank them again and followed the directions to the Company.]

  A1 --> I1[*If the Company is not present*: Tower Guard 2: Sorry, but we didn't see anyone. A group of people passed by though. To Summonwater and The Pilgirmage Site. Maybe they're the ones you're looking for. Or not. Not my fault of you get lost.]
  I1 --> J1[You asked for the emblem. The archer, alongside one of the tower guard, approaches you and gives it to you halfway before being snatched back.]
  J1 --> K1[Tower Guard 2: You know our "services" aren't free, right?]
  K1 --> L1[The other tower guard snatches the emblem and gives it back to you.]
  L1 --> M1[Tower Guard 2: Alright, fine. You're no fun y'know that?]
  M1 --> N1[You thank them and followed the directions to where the Company may have gone to.]

```
