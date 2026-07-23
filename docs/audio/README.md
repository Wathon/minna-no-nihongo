# 🎧 Minna no Nihongo Official Audio Tracks Directory (အသံဖိုင်များ သိုလှောင်ခန်း)

This directory is designated for official Minna no Nihongo Shokyu I (3A Corporation) Listening & Conversation audio tracks.

---

## 📁 Audio File Naming Convention (အသံဖိုင် အမည်ပေးစနစ်)

Place your official Minna no Nihongo CD / MP3 audio files inside `docs/audio/` using the following naming structure:

- `lesson-01-track-01.mp3` — Lesson 1 Choukai (聴解) Listening Track 1
- `lesson-01-kaiwa.mp3` — Lesson 1 Kaiwa (会話) Official Dialogue Track
- `lesson-02-track-01.mp3` — Lesson 2 Choukai (聴解) Listening Track 1
- `lesson-02-kaiwa.mp3` — Lesson 2 Kaiwa (会話) Official Dialogue Track

---

## 🎵 HTML5 Audio Player Integration in Notes

In your lesson Markdown notes, the HTML5 audio player automatically embeds and streams official audio files:

```html
<audio controls style="width: 100%; max-width: 500px; margin: 10px 0;">
  <source src="../audio/lesson-01-track-01.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```
