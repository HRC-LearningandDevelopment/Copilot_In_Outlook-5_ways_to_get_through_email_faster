# Narration script: Copilot in Outlook (HRC Learning Bites)

Record one audio file per part. Keep a relaxed, conversational pace (roughly 150 words per minute) and pause briefly between sentences. Each part's audio should be close to the time shown; if it runs longer, the walkthrough waits for it to finish. Each tip also pauses until the viewer clicks the Copilot icon, so leave a natural pause after "to open the chat."

Use the same voice for every part, and read only the text under each heading (the headings are not spoken).

Good tools for natural-sounding voices: Microsoft Clipchamp (text to speech), ElevenLabs, or a real person recording on a decent headset microphone.

## Intro (intro.mp3)
Welcome to this quick learning bite on Copilot in Outlook. In about two minutes, you'll see five ways to get through your email faster, using everyday situations you'll recognize. Press start whenever you're ready.

## Part 1: Summarize a thread (tip1.mp3, about 17 seconds)
A long thread about the office move? Let Copilot read it for you. Click the Copilot icon at the top right to open the chat. Choose Summarize this email, or type the request in your own words. You get the deadlines and open questions, and the numbers link back to the original replies. Just give the summary a quick check before you act on it.

## Part 2: Help me write an email (tip2.mp3, about 19 seconds)
Start a new email, then click the Copilot icon at the top right to open the chat. Choose Help me write an email, and describe what you need in plain words, with the key details. Copilot writes a first draft right in your email, subject line included. Adjust the length or tone, or select Keep it and make your own edits. You're still the author.

## Part 3: Fix grammar and tone (tip3.mp3, about 21 seconds)
Quick emails often have typos, and the tone may not suit the reader. Click the Copilot icon at the top right to open the chat. Say who the email is for and what you need from them. Copilot fixes the grammar and adjusts the tone for your audience and your goal. Replace the text in your draft, then read it once more before sending.

## Part 4: Turn an email into a meeting (tip4.mp3, about 17 seconds)
Your manager asks to meet about a new hire's first week. Click the Copilot icon at the top right to open the chat, and ask Copilot to set up the meeting in plain words. It creates the invite with the people from the email, a title, and an agenda. Check the time and details, and send. No copying and pasting.

## Part 5: Ask what needs your reply (tip5.mp3, about 18 seconds)
Back from leave, or a full day of meetings? Click the Copilot icon at the top right and ask in plain language, like "What needs my reply today?" Copilot points you to the emails that matter, with a reason for each. Then go straight to the next step, like drafting a reply to the client.

## Recap (outro.mp3)
Nice work. Pick one tip and try it on your next email. And remember, always read what Copilot writes before you send it.

---

### Adding the files
1. Put the MP3 files in the same folder as `copilot-outlook-learning-bite.html`.
2. Open the HTML file in Notepad, find the line starting with `const AUDIO =`, and fill in the names:
   `const AUDIO = { intro:'intro.mp3', s1:'tip1.mp3', s2:'tip2.mp3', s3:'tip3.mp3', s4:'tip4.mp3', s5:'tip5.mp3', outro:'outro.mp3' };`
3. Share the folder (for example on SharePoint or Teams) so the HTML file and audio stay together.
