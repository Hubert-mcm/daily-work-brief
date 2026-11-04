# Daily Work Brief — standing instructions

Each daily "Hubert Work Briefing" must:
- Be titled exactly "Hubert Work Briefing", saved as `briefings/YYYY-MM-DD-hubert-work-briefing.md` and copied into `latest-brief.md`. Follow `briefing-template.md` for the structure.
- Use the date of the day the run happens (check today's date; never reuse the previous day's header).
- Be pushed to the default branch `claude/quirky-goldberg-si1fmj` (authorised by the user) as well as the session branch.

## Sections (in this order)
1. **Today's Top Priorities & Deadlines** — keep the existing style. Include **Top 3 Actions Today** inside this section (a numbered list at the end of it).
2. **This Week's Commitments & Meetings** — calendar events, commitments and follow-ups due.
3. **Matters I'm Handling & Facilitating** — procurement, orders, issues and other matters Hubert is coordinating or facilitating, from recent Outlook emails. Split into two groups: **Directly involved** (Hubert is the sender, owner or in To) and **CC'd / FYI** (Hubert only in Cc or on a broadcast). Check To/Cc with read_email before classifying. Use specific bold labels (e.g. "Plant offhire", "Material approval").
4. **People to Follow Up Today** — table (Who / Topic / What to chase) built from recent Outlook emails and calendar: unanswered outbound requests, quotes/reports awaited, open tickets, deadlines. Include named suppliers (e.g. Billy, Mina, Abdel, Coates) and colleagues.
5. **Industry Updates (brief)** — 3–5 relevant Australian construction/civil/remediation items from the last 24–72 hours with sources, or say there is no meaningful update. AI/digital item only if materially relevant.

Do NOT repeat the Top 3 Actions at the bottom, and do NOT include a "What This Means for Me" section.

## Email search procedure (do this every run)
The Outlook search tool caps results (about 25 per call) and returns newest first, so one broad search misses older items. Always:
1. Check the current Sydney time with get_user_timezone first, and state in the header how far the Outlook read goes.
2. Search **sent items**: `from:hubert.lin@mcmservices.com.au received>=<start date>`, because outbound requests are the basis of Section 4.
3. Search inbound mail in date slices (one search per day, or per half day) and by key people: Acciona (Mahan, Toma, Kevin, Nicole, Bryan), Beralon, Coates, Bingo, LNM, Concrete Solutions, Allgeo, Anil, Maede, Hadi.
4. If any search returns exactly the cap, narrow the dates and search again until it returns fewer than the cap.
5. Check whether the sender has already replied or acted before listing something as a to-do (for example, an RFI Hubert has already sent should be listed as awaiting a reply, not as an action to send).
6. Ignore blank-subject items with no recipients (drafts).
