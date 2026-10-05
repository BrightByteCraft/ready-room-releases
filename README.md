# Ready Room: Interview Coach

Practice interviews out loud with a voice coach that runs entirely on your Mac.

Most of us prepare for interviews in our heads. We read the common questions, think
through an answer, and feel ready. Then in the room the words come out differently, a
story runs long, and a question we'd "covered" catches us off guard.

Saying your answers out loud is a different kind of practice. You hear your own voice
tell the story, you find where it gets stuck, and you have already answered the hard
questions before anyone asks them. Nothing in the real interview is a surprise, and that
is where confidence comes from.

Ready Room is somewhere to do that practice. The coach asks the questions out loud, you
answer the way you would in the interview, and it gives you feedback on what you said.
No account, and no one listening: your voice is understood on your own Mac and never
leaves it.

This repo holds downloads and install instructions only. It isn't the app's source.

## Features

There are four ways to prepare:

- **Practice**: the coach asks one question and gives you feedback right after. A good
  place to start.
- **Mock interview**: closer to the real thing. A run of questions, with feedback at the
  end.
- **Learn**: short spoken lessons on interview skills, like how to tell a strong story.
- **Talk**: just talk with the coach about nerves, plans, or anything else on your mind.

Also built in:

- **Prep for a specific job**: paste a job posting. The coach reads it on your Mac and
  writes questions matched to the role and its level, from first job to VP, for you to
  review before you practice.
- **Ask in your own words**: "slow down", "give me an example", "skip this one". The
  coach waits until you've finished talking before it replies, and you can choose how
  long it waits.
- **Calm your nerves**: quick breathing and grounding exercises, any time in a session.
- **Progress**: see how your answers improve over time.
- A short spoken tour on first launch shows you around. You can choose the coach's
  voice and speaking speed, or switch the voice off and type instead.

## Download

Grab the latest build from the [Releases page](../../releases/latest).

## macOS (Apple Silicon)

Requires an M1 or newer Mac running macOS 14 (Sonoma) or later. It doesn't run on Intel
Macs. You need about 3 GB of free disk space.

1. Download `ReadyRoom.app.zip` and unzip it.
2. Drag **Ready Room.app** into **Applications**.
3. The first time you open it, macOS will block it with a message like *"Apple could
   not verify 'Ready Room' is free of malware..."*. That's expected for a small app
   from outside the App Store. It doesn't mean anything is wrong or corrupted. You only
   need to get past it once:
   - Open **System Settings → Privacy & Security** and scroll down. You'll see a line
     saying Ready Room was blocked, with an **Open Anyway** button next to it. Click
     it, confirm once more, and from then on it opens normally.
   - If that line doesn't appear, open **Terminal** and run
     `xattr -cr "/Applications/Ready Room.app"`, then open Ready Room again.
4. **First launch: getting your coach ready.** Ready Room downloads the coach's
   language model once (2.5 GB, from huggingface.co). It's too big to include in the
   download above. A progress bar shows how long is left, and you can cancel and try
   again later. The file is checked against a fixed fingerprint (SHA-256) before it's
   kept. From then on the app works offline.
5. When asked, allow **Microphone** access. The coach needs it to hear your answers.
   You can also switch the voice off and type instead.

## Your data

Ready Room listens, understands and replies entirely on your Mac. Your voice, answers,
notes and job postings are never sent anywhere, and there's no account to make. The
only time it goes online is the one-time model download in step 4, plus any optional
models you choose to download in Settings. **Settings → Your data** lets you export
everything or delete it.

## Feedback

admin@brightbytecraft.com
