# The Personality Archive

Single-file app: open `index.html` in a browser (or host it on any static host).

- Routes use hash URLs (#/explore, #/quiz/villain, #/result/villain/ma, ...), so it works on any static host.
- Quiz content is the `QUIZZES` array in the script. Add an object there to add a quiz.
- Set `CFG.domain` at the top of the script to print a custom domain on share cards.
- Fonts load from Google Fonts. No backend, accounts or analytics.
