# Project Interview Notes

These are my working notes for building my AI + Design project website. The site needs to work as a case study, a portfolio piece, a process share, and a product highlight. The public stuff is kept separate from my private evaluation notes at the bottom.

---

## Project Title

Born To Create - 
A short AI-made video about human creativity, made as an ad for Claude.

---

## One-Sentence Project Summary

A video about human creativity that invites viewers to reconsider AI.

It takes the form of an ad for Claude, but the ad is just the vehicle. The real point is about creativity and working with AI.

---

## Starting Point

My inspiration came from the Pinterest ad "How did they do it." I loved the feeling and emotion that ad gave me. It made me want to go offline more and enjoy the silly little life we live, and appreciate humans and the small things. The thing that stuck with me was that it was an ad by a social media company, but it made you want to be offline.

I knew I wanted to make a video that evokes emotion about AI and creates room for good questioning. I wanted to give people that same kind of feeling, but pointed at a different idea.

It didn't start as an ad. About halfway through I decided to make it an ad for Claude. I use Claude for lots of things, so it felt like the honest choice. But that part doesn't matter as much as the message.

---

## Inquiry Question

Can AI be used for good, and could it be something we work together with instead of something we hate before we even understand it?

I personally sit in the middle on AI, so this felt like the right thing to make. Not too opinionated, but inviting the viewer to reflect. I want people to give the idea of AI being useful a chance, instead of full on hate before knowing things.

---

## Why This Question Mattered

I sit in the middle myself, and I think a lot of people don't. They pick a side fast. I wanted to interrupt that reflex of hating something before understanding it.

The video isn't trying to convince anyone or win an argument. It's an invitation, not an argument. I want everyone to be able to give the idea a chance and wonder if AI can be used for good and work together with us.

It also mattered because the video makes its point by being the thing it's talking about. It's made with AI, and it shows we can still be creative by making the piece as a collaborator with the tool. The making is the proof.

---

## Research and Sources

- Pinterest "How did they do it" ad. I studied this for the emotional tone and that feeling of being offline and appreciating human life.
- Apple "Think Different." I studied this for the way it shows the humanness of all of us and how inspiring that is, and for the black and white visual style.
- Kling 3.0 tutorial videos. Lots of videos on how to generate good clips. This is where I learned the technical side.

Each one fed a different part of the project. Pinterest for feeling, Apple for the message and the look, Kling tutorials for the actual generating.

---

## What I Found

On the idea side, black and white wasn't just a style I took from Apple. It also has a nostalgic, timeless feel that fit what I was going for. The way "Think Different" celebrates humanness became my own through line too.

On the craft side, I built a system for making clips:

1. Use Claude to generate and refine the prompts.
2. Put the prompt into ChatGPT Image 2.0 to make a starting frame, a still I could control exactly how I wanted it.
3. Use Claude to write a second prompt made specifically for Kling, built off that starting frame.
4. Animate the frame in Kling 3.0.

Making a still starting frame first meant I locked the visual direction before spending Kling credits, which I had to use sparingly. The big technical thing I found was that AI clips come out too perfect by default, and I had to fight that to get a human, nostalgic feeling.

---

## Source Verification

- I tested the Kling tutorial techniques against my own clips instead of just trusting them. I kept what actually gave me the look I wanted and dropped what didn't.
- I questioned the AI's default output. The first clips looked too perfect (skin, lighting, backgrounds), so I didn't just accept realistic looking AI footage. I pushed against it.
- I checked the start frame approach by comparing. I first tried using both a start and an end frame, found Kling messed up trying to get from one to the other, and confirmed through trying it that one strong starting frame worked better.

---

## How Research Shaped the Project

The Pinterest ad set my emotional goal. "Think Different" gave me the through line (humanness) and the look (black and white). The Kling tutorials gave me a starting point that I then turned into my own Claude to ChatGPT Image to Kling workflow. The research didn't just shape the message, it shaped my whole process and the look of every shot.

---

## Research Dashboard / Approach and Engagement

A section that shows the inquiry instead of just describing it, laid out side by side:

- Approach: the still to motion workflow. Claude (prompt) to ChatGPT Image 2.0 (starting frame) to Claude (motion prompt) to Kling 3.0 (clip). Plus the production logic of locking visuals cheaply in stills before spending limited Kling credits.
- Engagement: the sources I actually studied. Pinterest "How did they do it," Apple "Think Different," Kling 3.0 tutorials.
- Inquiry: the question. Is AI really that bad, or can we create with it?
- Evidence: the iPhone 8 prompt block, the start and end frame pivot, the still to motion pairs, the final video.

(I'm picturing a structured layout, not a literal interactive dashboard.)

---

## AI Tools and Prompt Experiments

Tools I used:

- Claude. Co-wrote the script and generated and refined the image and motion prompts.
- ChatGPT Image 2.0. Made the starting frames.
- Kling 3.0. Animated the starting frames into clips.
- ElevenLabs. Made the AI voiceover from my script.
- Premiere Pro. Editing.

The key prompt thing I found. To stop the clips from looking too perfect, I added this exact block to the end of all my video prompts:

> "Shot on an iPhone 8 — slightly imperfect focus, not color corrected, casual framing. Real time motion, not slow motion. Camera completely locked, no movement, no zoom, no drift. Natural micro-tremor as if handheld. Candid, not posed. Photorealistic, 16:9."

Why "iPhone 8" specifically. The first clips looked too perfect, especially the characters' skin, the lighting, and the backgrounds. Naming a real, slightly older phone adds imperfect lighting and exposure and makes it look more real. Giving the AI a real object to copy worked better than just saying "make it realistic."

Two-step still then animate. Making the starting frame first locked the visual direction before I spent Kling credits, which were limited.

The lesson about restraints. If you put too strict of restraints on the AI, it sometimes turns out a lot worse. I learned to control the intent (the iPhone 8 block, locked camera, one strong frame) and leave room for the tool to do its thing (generate the motion).

---

## Process Page / Workflow and Pivots

Workflow: Claude prompt to ChatGPT Image 2.0 starting frame to Claude motion prompt to Kling 3.0 clip, then put together and edited in Premiere Pro.

Pivot 1, dropping the end frame. I started by making both a start and an end frame and having Kling move between them. It didn't work out. Kling messed up a lot of the time trying to get from the start frame to the end frame. So I switched to one strong starting frame and let the model make the motion from there. Less control on paper, but better results. This taught me where to hold on tight and where to let the tool do its thing.

Pivot 2, fighting too perfect. The early clips looked too clean and too AI. I fixed it with the iPhone 8 prompt block, basically making it imperfect on purpose to get the human, nostalgic feeling I wanted.

Editing (in Premiere Pro):

- Sequenced and timed the clips to the voiceover and ambient audio.
- Slight color grading.
- A film frame overlay, which does the same kind of thing as the iPhone 8 prompt but in editing, making the footage feel more handmade and aged.
- A few cross dissolves.
- Text added at the end.

So I'm fighting the too perfect look at two stages, in the generating and in the editing.

Audio:

- AI voiceover (ElevenLabs) reading my script.
- One audio bed, a royalty free Pixabay track with kids laughing and waves at the beach. No separate music.
- The voice carries the message and the black and white clips carry the feeling.

The ending reveal:

1. Text card: "The future of creativity still starts with you."
2. Text card: "This ad was made with the collaboration of AI" with the Claude logo, revealing it's an ad for Claude.

I held the reveal until the end on purpose. The viewer feels something for 40 seconds, then finds out the thing that moved them was made in collaboration with AI.

Runtime: about 40 seconds.

---

## Final Product or Outcome

A roughly 40 second AI-made video about human creativity, with a nostalgic, black and white feel, that ends by revealing it's an ad made in collaboration with Claude. AI-generated shots (ChatGPT Image 2.0 and Kling 3.0), an AI voiceover (ElevenLabs) reading my co-written script, one royalty free ambient bed, and editing in Premiere Pro.

The strongest part is the voiceover with the ambient background. Together they create and evoke the emotion. The voice carries the message and the visuals carry the feeling.

The script (co-created with Claude):

> Before we had words for it—we were already doing it. Nobody teaches a child to make a mark. Nobody explains to a teenager why a feeling needs a song. Nobody tells us to build things we don't need—or make things nobody asked for. We just do. It passes through us. From one pair of hands to the next. From one generation to the next. Now we create together.

It builds like a nostalgia piece and then turns on the last line, "Now we create together," into the present and the collaboration, without ever naming the AI or arguing. An invitation, not an argument.

---

## Product Page / Authorship and Synthesis

My role across the whole project was director and editor. I held the vision and intent, the AI made the raw material and options, and I picked, refined, and decided what stayed.

- Script: I gave Claude the idea of what I wanted, it came up with drafts and lines, and I refined it. I shaped it and chose what stayed.
- Visuals: I controlled the starting frame exactly, wrote and refined the prompts, and made the imperfect, human look on purpose.
- Edit: the sequencing, color grade, film overlay, transitions, and the final text cards were my calls.

The same thing runs through every tool. I set the direction and the judgment, the AI generates, and I curate. Where my authorship shows up most is in pulling the tool away from its too perfect default toward something more flawed and human, and in giving the human the last word ("still starts with you") while keeping the door to collaboration open.

The project isn't an exception to its own point. It's an example of it.

---

## What I Learned

- AI is useful and good, but it can't do everything for you. My teacher described it as glasses for your brain, it can just help. That stuck with me and it matches how I see it.
- Too strict of restraints on the AI can make the output worse. Control the intent and leave room for the execution.
- A concrete reference, like a real phone or a real object, directs these tools better than vague words.
- Locking the visuals cheaply with stills before spending limited video credits is smart.

Where I had to grow: patience. Learning to sit with not getting the results I wanted right away, regenerating, adjusting, and accepting that the collaboration takes time.

Did my view change? Not really. Making it confirmed what I already believed. AI is useful and good, but it can't do it for you. I started in the middle and I'm still there.

---

## Reflection Notes

- One click moment: realizing the problem with the early clips was that they were too perfect, and that naming a real, slightly older phone ("iPhone 8") would fix it where "make it realistic" couldn't. Giving the AI a real object to copy instead of an adjective.
- Beginning to now: I started out wanting to recreate a feeling (the Pinterest ad) and ended up with a piece that proves its own point. The ad admits it's a human and AI collaboration and asks to be judged by how it made you feel.
- What's next: not sure right now. (Open, come back to it.)

---

## Private Evaluation Notes

(Not for the public site. For my own Canvas reflection and self-evaluation. To fill in.)

- Honest take on the final cut, what works and what I'd be critical of: (TBD)
- What I'm still unsure about: (TBD)
- Struggles or frustrations I wouldn't necessarily put publicly: (TBD)
- Anything I'm unsure whether it's public or private: (none yet)

---

## Evidence to Include

Have or can show:

- The final video (about 40 seconds). Done.
- A starting frame still shown next to the clip it became (the still to motion step).
- The iPhone 8 prompt block (text).
- The script (text).
- ChatGPT Image and Kling interface screenshots.
- The end text cards: "The future of creativity still starts with you" and "This ad was made with the collaboration of AI" with the Claude logo.

Maybe:

- Screenshots of the Claude prompt and script writing sessions (grab from history if I still have them, they'd show the co-authorship).

Don't have (describe in the writing instead, don't make up):

- A before and after "too perfect" vs fixed clip pair.
- The failed start and end frame clip.

---

## Links and Workspace Materials

- Pinterest "How did they do it": https://www.youtube.com/watch?v=qr8bNBuptpU
- Apple "Think Different": https://www.youtube.com/watch?v=5sMBhDv4sik
- Ambient audio (Pixabay, royalty free), "Let the Children Play / Shoreline Ambient Background": https://pixabay.com/sound-effects/film-special-effects-amb-let-the-children-play-shoreline-ambient-background-532812/
- Tools: Claude, ChatGPT Image 2.0, Kling 3.0, ElevenLabs, Adobe Premiere Pro
- Project files: local
