# Out and About

## Concept

**Out and About** is ARIA's functional-conversation minigame. The learner moves through a small Irish town and uses Gaeilge to satisfy practical needs.

It should answer a simple learner question:

> Could I actually use this Gaeilge if I were standing in Ireland tomorrow?

The minigame follows ARIA's shared interaction loop:

**Need → Communicate → Listen → Interpret → Act → Consequence**

The player should usually demonstrate comprehension by doing something in the world rather than answering a translation question.

## Level 1 Design

Level 1 provides substantial support. Full phrases and English meanings may be visible when language is first introduced, but support should begin disappearing when a phrase becomes familiar.

The same scenarios can later be reused with progressively less scaffolding:

1. Choose the correct full phrase.
2. Assemble a phrase from meaningful chunks.
3. Produce important words with less prompting.
4. Hear NPC responses before seeing text.
5. Conduct short exchanges and act correctly based on comprehension.

## Encounters 1–4: Survival

### 1. Where Is the Restroom?

**Goal:** Find the restroom in a café or pub.

Core phrase:

**Cá bhfuil an leithreas?** — Where is the restroom?

Possible NPC response:

**Tá sé thall ansin, in aice leis an doras.** — It is over there, beside the door.

The translation then disappears and the learner must choose the correct door/location.

Language targets:
- Cá bhfuil...?
- leithreas
- ansin
- doras
- in aice le...

Wrong destinations should produce contextual feedback rather than a generic failure screen.

### 2. I'm Hungry

**Goal:** Communicate hunger and obtain food.

Core phrase:

**Tá ocras orm.** — I'm hungry.

The learner encounters the Irish construction in which hunger is expressed as being "on" the person rather than through a direct equivalent of English "I am hungry."

The NPC offers simple choices such as soup or a sandwich. The learner identifies the spoken choice and responds using:

**Ba mhaith liom...** — I would like...

Language targets:
- Tá ocras orm
- anraith
- ceapaire
- Ba mhaith liom...

`Tá tart orm` should appear early as a distractor/preview so it can later be retrieved rather than introduced from nothing.

### 3. I'm Lost

**Goal:** Ask for help reaching a landmark and follow a simple direction.

Core phrase:

**Tá mé caillte.** — I'm lost.

The learner states a destination and receives a simple direction such as:

**Téigh ar dheis. Tá an séipéal ansin.** — Go right. The church is there.

The translation disappears and the learner physically chooses the direction.

Language targets:
- caillte
- dul
- séipéal
- ar dheis

### 4. I Don't Understand

**Goal:** Manage a conversation that exceeds the learner's current comprehension.

The NPC intentionally uses authentic Gaeilge that is above Level 1. The learner is not expected to translate it.

Useful responses:

- **Ní thuigim.** — I don't understand.
- **Abair arís é, le do thoil.** — Say it again, please.
- **Níos moille, le do thoil.** — More slowly, please.

All can be valid depending on context.

This establishes a critical ARIA mechanic: conversational repair phrases become player tools. As proficiency increases, conventional Replay, Slow Audio, and Translate controls can be reduced because the learner can request assistance inside the simulated conversation.

## Encounters 5–8: Independence

### 5. Where Are the Gardaí?

**Goal:** The learner has found a lost wallet and needs to find a Garda/Garda station.

Core phrase:

**Cá bhfuil stáisiún na nGardaí?** — Where is the Garda station?

Possible response:

**Tá sé ar chlé, in aice leis an siopa.** — It is on the left, beside the shop.

This retrieves `in aice le` and contrasts new `ar chlé` with previously learned `ar dheis`.

A useful whole phrase such as **Fuair mé sparán** (I found a wallet) may be introduced without requiring the learner to understand the underlying past-tense grammar yet.

### 6. I'm Thirsty

**Goal:** Get something to drink.

Core phrase:

**Tá tart orm.** — I'm thirsty.

This retrieves the phrase previewed in Encounter 2 and reinforces the `Tá ___ orm` pattern.

The NPC offers choices such as:
- uisce — water
- tae — tea

The learner reuses:

**Ba mhaith liom ___, le do thoil.**

### 7. How Much Is It?

**Goal:** Buy an item at a market stall and pay the correct amount.

The learner requests an item, such as an apple, then asks the price.

Core language:

**Ba mhaith liom úll, le do thoil.**

**Cé mhéad atá air?** — How much is it?

The NPC gives a price in Gaeilge. Instead of translating the number, the learner must choose the correct money.

The environment provides correction when possible: an incorrect amount causes the merchant to repeat the price rather than generating a generic wrong-answer message.

This mechanic can later scale to larger numbers, multiple items, totals, and change.

### 8. Can You Help Me?

**Goal:** Determine which bus to take.

Core phrases:

**Gabh mo leithscéal.** — Excuse me.

**An féidir leat cabhrú liom?** — Can you help me?

The learner states a destination using language from Encounter 3. The NPC intentionally responds somewhat quickly so the learner has an authentic reason to retrieve:

- Níos moille, le do thoil.
- Abair arís é, le do thoil.

The learner then selects the correct bus based on the response.

This is the first strong integration encounter: several previously learned conversational tools are required to solve one practical problem.

## Encounters 9–11: Integration

### 9. Excuse Me, Where Is...?

**Goal:** Find the bus station from the town square.

The learner initiates politely and asks where the destination is.

The NPC gives the first multi-step direction, combining familiar language such as:
- ar chlé
- ar dheis
- ansin
- in aice le
- séipéal

The learner physically follows the sequence.

If the environment no longer matches the directions, the learner should be encouraged to recognize the misunderstanding and use conversational repair tools rather than immediately receiving a correction.

### 10. The Wrong Order

**Goal:** Correct a misunderstanding.

The learner orders a known drink. The server deliberately brings the wrong one.

The game should not explicitly announce the error; the learner notices it.

Useful language may include:

**Ní hea.** — No / That's not it.

A useful whole phrase such as **D'iarr mé tae** (I asked for tea) can be introduced without turning the encounter into a past-tense lesson.

The server apologizes using **Gabh mo leithscéal**, allowing the learner to recognize a phrase previously learned for personal use when another person says it.

### 11. Where Is My Family?

**Goal:** Find family members in a busy but non-threatening market/festival setting.

The learner asks for help and receives a description/location response.

Basic descriptive vocabulary may include:
- fear — man
- bean — woman
- buachaill — boy
- cailín — girl

The NPC's response should intentionally contain some language the learner has not learned, while also containing enough familiar language—such as **in aice leis an séipéal**—to solve the problem.

This encounter teaches a major real-world comprehension strategy:

> You do not need to understand every word. You need to understand enough.

Maeve may explicitly reinforce that insight after the encounter.

## Encounter 12: A Morning in Town

### Level 1 Capstone

The learner receives several practical objectives and completes them with minimal explicit teaching.

Example objectives:
- Get something to eat.
- Buy an apple.
- Find out when the bus leaves.
- Meet Maeve at the church.

The learner chooses the order and navigates the town independently.

They may need to:
- Express hunger.
- Order food.
- Buy an item.
- Understand a price.
- Ask someone to repeat or slow down.
- Ask where the church is.
- Follow directions.

The capstone should not end primarily with a percentage score. Completion should emphasize functional capability.

## Level 1 Capability Summary

By the end of Level 1, the learner should be able to:

- Greet someone and get their attention.
- Ask where something is.
- Understand basic directions.
- Say they are hungry or thirsty.
- Order simple food and drinks.
- Ask a price and understand basic numbers.
- Ask for help.
- Say they are lost.
- Ask someone to repeat themselves.
- Ask someone to speak more slowly.
- Cope when they do not understand every word.
- Repair a simple misunderstanding.

## World Structure

Out and About should evolve into a small explorable town rather than a sequence of disposable lesson screens.

Locations should recur:
- Café/pub
- Town streets and square
- Shop/market
- Church
- Garda station
- Bus stop/station

The learner should gradually feel:

> I can do more things in this town now because I know more Gaeilge.

Language proficiency should unlock capability, not merely numbered lessons.

## Next Design Work

Before designing Level 2, define Maeve's assistance and scaffolding behavior across minigames:

- When she teaches.
- When she hints.
- When she translates.
- When she uses humor.
- When she lets the environment provide the correction.
- When she reduces difficulty.
- When she says nothing and allows the learner to work it out.

This should become a reusable ARIA-wide system rather than rules unique to Out and About.

---
Version: 0.1
Status: Draft
Last Updated: 2026-08-17
Owner: Martin Maynard
