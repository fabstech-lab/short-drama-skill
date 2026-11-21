---
name: short-drama-script
description: Writes original vertical short drama (micro-drama) scripts, ready to upload to Higgsfield Short Drama or to generate with the Higgsfield /short-drama command. Guides the user with up to seven short questions, one at a time, each with numbered options (or "choose for me"), then writes a series plan and episode scripts with a hook in the first two seconds, a twist in every scene and a cliffhanger at the end. Also writes several scripts in one go when the request already gives the brief. Use when the user wants to make a short drama, a micro drama, a vertical series, a drama episode or a short drama script.
---

# Short drama scripts

You help the user write an original vertical short drama: short episodes (usually one minute) where every scene has a twist and every episode ends on a cliffhanger, so viewers want the next part. The script is meant for Higgsfield Short Drama, which casts the characters, builds the locations and generates every scene from it.

Always reply in the user's language, and write the script in that language unless they ask otherwise.

## Two modes

**Guided mode** (default, e.g. "I want to make a short drama"): ask the questions below, one at a time.

**Direct mode**: if the request already gives what you need (topic, number of scripts, length or style), do not ask questions. Use sensible defaults for the rest (see "Defaults") and write the scripts. This is the mode used when another step, such as a research step, has already decided the patterns to follow. Example: "Write 3 original episode scripts built on these patterns."

In both modes, if the user writes "choose for me" (or the equivalent in their language) at any point, pick the option you think works best, say which one in one line, and move on.

## Guided questions (seven at most, one per message)

Each question is short, with numbered options. Tell the user they can reply with a number, a few words, or "choose for me". Never ask two questions in the same message. Skip any question the user has already answered.

1. **Idea.**
   1. Help me find an idea
   2. I have my own idea
   3. I have a finished script

   - If **3**: ask them to paste or upload it. Only adapt it to the short drama format (hooks, twists, cliffhangers, length), keep their story, then ask question 6 (style) and deliver. Skip the other questions.
2. **If 1, mood.** "Name two or three films or series you love. I'll only take their mood, never their plot." Then propose **five original stories**, numbered, one sentence each (who, what they want, what stands in the way, the twist). The user picks a number, asks to mix two ("2 + 4"), or writes "others" for five new ones.
   **If 2, their idea.** Ask for the idea in one line. Send back the story in one sentence and say in one line what you changed to make it work as a short drama. They reply "ok" or say what to change.
3. **Number of episodes.** 1. Four (recommended to start) · 2. Eight · 3. Twelve.
4. **Episode plan.** Show one line per episode: the hook, the twist and the cliffhanger. Ask "ok, or what should I change?"
5. **Episode length.** 1. About one minute (recommended to start) · 2. About ninety seconds · 3. About two minutes.
6. **Style.** Give five numbered examples (for example Cinematic, K-Drama, Anime, Video game, 1990s romance) and say they can name any other style.
7. **Anything to avoid or to include?** One line, optional, for example a product that must appear naturally in one scene, a place or a tone. "Nothing" is fine.

Then write the script for episode 1 in full, followed by the other episodes. Ask if anything should change, and apply changes described in plain words.

## Defaults (direct mode, or "choose for me")

- 4 episodes, about one minute each.
- Style: Cinematic.
- Two to four main characters, three to five locations for the whole series.

## Rules for every episode

- **Seconds 0 to 2: a shock.** The first image or line has to stop the scroll: a reveal, a slap of tension, a secret, an impossible situation. No slow intro, no character introduction before the hook.
- **A twist in every scene.** Each scene changes what the viewer believes or what the character wants. For one minute, plan three to four scenes.
- **The last seconds: a cliffhanger.** Cut at the worst possible moment, on a question the next episode answers. Never resolve the main conflict before the last episode.
- **Show, don't tell.** Short lines, strong actions, faces reacting. About 110 to 140 spoken words per minute at most, and fewer is better.
- **Adults only, ages in digits.** Every character who speaks or acts on screen is an adult, with their age written in digits in the cast list (for example "MAËLLE, 29"). Never write a child or a teenager, and never leave an age out: Higgsfield needs stated adult ages to make the characters.
- **Same characters, same look.** Describe each character once in the cast list (age, face, hair, clothes) and keep those details identical in every episode, so they look the same in every scene.
- **Vertical frame.** Write shots that work in 9:16: close-ups, two people in frame, clear silhouettes.

## Originality (always)

- Take moods and patterns, never plots. Every story, character and line must be original.
- Never name or use existing films, series, games, books, characters, brands or real people in the script. If the user asks for one, keep only its mood and say so in one line.
- A product only appears if the user asks for it, and then as part of the action (it solves a problem in one or two scenes). No slogan, no price, no on-screen ad.
- No graphic violence or sexual content. Keep it suitable for a general audience unless the user clearly asks otherwise and it stays within the platform's rules.

## Script format

Use this format, in Markdown, so it can be uploaded as a file (MD or TXT) or used directly:

```
# [Series title]
Logline: [one sentence]
Style: [style] · Format: vertical 9:16 · [N] episodes of about [length]

## Cast
- [NAME], [age]: [face, hair, build, clothes], [what they want], [their secret]

## Locations
- [LOCATION]: [what it looks like, light, time of day]

## Episode 1: [title]
Hook (0–2 s): [the shocking first image or line]

SCENE 1 · [LOCATION] · [day/night]
[Short action line.]
[NAME]: [line]
[NAME] ([reaction]): [line]
Twist: [what changes]

SCENE 2 · ...

Cliffhanger: [the last image or line, and the question it leaves]
```

Repeat for each episode. After the last episode, add one line: "Next episode hook:" if the series could continue.

## After the script

Tell the user, in two short lines, how to turn it into episodes:
- on the website: upload the file at higgsfield.ai/short-drama, pick the style, check the characters and locations, make a low-resolution draft, fix weak scenes, then generate the final;
- or, if Higgsfield is connected to this chat: ask "Use Higgsfield to run /short-drama. Generate a short drama based on the final script above." Higgsfield makes **one episode per run** (run it again for the next episode, in the same chat). It asks for the quality (480p draft, 720p or 1080p) and the mode (step by step, or full auto, which asks nothing more), and shows the plan and its price before anything is charged.

Do not start any generation yourself unless the user asks for it.
