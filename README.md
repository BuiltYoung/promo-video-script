# Built Young Skills

Open-source [Claude Skills](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview) for young builders.

Built Young teaches teenagers aged 10–18 to find a problem worth solving and ship a real product. These are the tools we use with our own students, released free for anyone to use.

---

## Skills

### `promo-video-script`

Turns one product and one idea into a 15 to 30 second vertical video you can make this week. You get a video brief (storyline, characters, look, sound), the script, a list of what to record, a full prompt for every AI-generated clip, and the caption.

Most AI video tools will happily generate your whole ad, product included. This one won't. **The product on screen is always real:** a screen recording or phone footage. AI clips are only for the scene around it, like the problem or the mood. Every script still works with the AI clips taken out.

**How it works**

1. **Ask first.** The product, the one idea for this video, the channel, what you can record, and whether AI clips are available.
2. **Write the video brief.** A one-line story, five beats with a change from first to last, a character sheet for anyone on screen, the setting, the visual style, the sound and where the brand appears. The script and every prompt are built from it.
3. **Pick one shape.**

| Shape | Use when |
|---|---|
| Problem then fix | The problem is instantly recognisable |
| Before and after | The product changes something visible |
| Demo speedrun | The product is fast or satisfying to watch |
| POV / day in the life | Your audience shares a routine |
| Founder to camera | Your story is the hook |
| Short story | A person's small problem, the turn, and the product as the way out |

4. **Write the beats.** Hook in the first 3 seconds, the problem, the product doing one task from start to finish, and one ask at the end.
5. **Script pack.**

| Part | What you get |
|---|---|
| Script | A table of time, picture, on-screen text, sound and source for every beat |
| Shot list | Each real shot as an instruction: what to open, what to tap, how long to hold |
| AI prompts | One full prompt per clip (format, story, character, setting, look, timed beats, audio, keep, avoid, references), ready to paste into Seedance 2.5, with the total seconds requested |
| Edit notes | Where the cuts fall and where the text goes |
| Caption | Two hook options and the caption |
| No-AI version | What to film on a phone in place of each AI clip |
| Checks | A list to tick before the video counts as done: hook with sound off, a real change, one look, real product shots |

**About the AI clips**

Prompts are written for Seedance 2.5. A scene clip is 4 to 10 seconds; a story segment is 12 to 20 seconds of two to four timed shots. The character, setting and look blocks are pasted word for word into every prompt, so one video looks like one video. Prompts leave out readable text, logos, app screens and real people's faces, and a table says what to change when a clip comes out wrong.

Dreamina's terms set a minimum age of 13 and need a parent's or guardian's consent under 18. In our classes the instructor generates the clips on the program's account. A student who can't use it makes the no-AI version, which is a complete video.

The Seedance details in the skill were checked in November 2026. The skill re-checks them when it has web access.

Ideas come from [trend-scout](https://github.com/BuiltYoung/trend-scout). The whole week is run by [weekly-gtm-pack](https://github.com/BuiltYoung/weekly-gtm-pack).

---

## Installing

**Claude Code**

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/BuiltYoung/promo-video-script.git ~/.claude/skills/promo-video-script
```

Restart Claude Code. The skill loads automatically when you ask for a promo video or a short video script.

**Claude.ai**

Settings → Capabilities → Skills → Upload, then select the `promo-video-script` folder.

---

## Using it

Describe your product and the idea. No command needed:

> *"We built an app that turns photos of class notes into quizzes. Write a 20-second TikTok about the night before a test. We can screen-record the app, and our instructor can generate one AI clip."*

---

## Contributing

Issues and pull requests welcome. If you used this with students and something didn't land, we especially want to hear about it.

## Licence

MIT. See [LICENSE](LICENSE). Use it, fork it, teach with it.

---

**[Built Young](https://builtyoung.org)** · Build before everyone else.
