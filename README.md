
What this is and what this is not:

This application is to help train analysts and QA testers responsible for the constant improvement cycle of EW RF based defense or civilian applications. 

This application comes with 294 questions and answers hard coded. These question-answer pairs cover a usefully broad and significant spectrum of the basic specialist knowledge needed for understanding applications that automate any part of the EW RF workflows.

The goal of this application is for non-engineers to gain enough specialist knowledge so that requirements and design from the dev department can be more readily converted to preconditions and boundary parameters by QA for testing. 

DO NOT put any information on this application that is proprietary or otherwise sensitive in nature. 

REMEMBER This application stores its data on your browser so any data you add can get lost easily for any number of reasons. Keep a backup of your data if you make new cards.

How to use:

This is a self-contained HTML/JS flashcard trainer — just open the file in any browser. There is no server or install needed.

How it's built:

Storage: uses the browser's localStorage as the database (the app's own key-value store). Cards persist across sessions on that device/browser. 

Export/Import buttons let you back up the deck as JSON or move it to another browser.

There are already 294 seeded cards across several categories that pertain to basic EW RF terminology. Add cards as you see fit but with the current design you gotta keep your own backup of any new data that you add in case the browser's memory gets wiped. 

Study mode: flip-card UI (click, button, or spacebar), category filter, shuffle/sequential order, progress bar.
Manage Deck: full add/edit/delete for any card, live search, category filter, plus "Restore Factory 100" to reset the seed set if you mess with it.

Stats view: card counts per category and session progress.

A couple of things worth knowing:

Data is local to whatever browser profile you open this in. Clearing your browser storage will wipe it all out! (export first if that matters).

If you want this synced across devices or shared with a team, that'd need a real backend.

Any modern browser will run this fine — it's plain HTML/CSS/JS with localStorage, which is supported everywhere. A few practical notes to help you pick:

Chrome, Firefox, Edge, Safari — all work well. No real functional difference for this app.

Whichever one you'll actually keep using matters most, since the data lives in that specific browser's local storage on that specific device. If you study in Chrome one day and Firefox the next, you'll see two separate decks — they don't share storage.
Avoid Incognito/Private browsing — some browsers clear or restrict localStorage when the private window closes, so your added/edited cards could vanish.

Don't rely on "Clear browsing data" hygiene habits — if you or your browser is set to auto-clear site data/cookies on exit, that can wipe localStorage too. Worth checking your settings if you customize the card set a lot.
Desktop vs. mobile — the layout is responsive and works on phone browsers, but you'll get a much better editing experience (long question/answer text, table-like card list) on a laptop/desktop screen.

One habit that's recommended regardless of browser choice: use the Export Deck (JSON) button periodically once you start customizing cards, especially after adding your own  questions. That gives you a portable backup independent of any one browser's storage, and you can re-import it anywhere (or hand it to a teammate) if your local storage ever gets cleared.




