# Ludwig · progress

Live progress page for my German practice with Ludwig (a Claude skill): https://jaredartt.github.io/ludwig/

- `progress/` holds the learner data (vocabulary with % learned, mistake patterns, roadmap status, profile, session log) as markdown. Ludwig updates it with one commit per message.
- `state.json` is the snapshot the page reads. `index.html` + `vendor/` is the read-only web page (Lexend font and Tabler Icons, MIT/OFL licences included).
