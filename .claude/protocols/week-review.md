# Protocol: week review

Run on Sundays or the last workday of the week.

1. Read all daily review files from this week in `reviews/daily/`
2. Calculate habit completion rates from `habits/log/` files for the week
3. Cross-check week's output against current quarter goals
4. Sweep `todos.md` — flag any "This week" item that's been there more than 10 days.
   Ask once per flagged item: done, dropped, or still live?
5. Identify: best day / hardest day / top win / top miss
6. Read the State lines from the week's daily reviews. Average each scale, name the
   trend in one line each ("stress 2→4, peaked Tuesday — deadline day"). Trends and
   correlations, not judgments. If a difficult scale averaged at the bad end, say so
   plainly and connect it to what the week held.
7. If any habit completed less than 50% for two weeks running, flag it
8. Check the week against `context/operating-manual.md` — did any blind spot or
   early-warning sign fire? If so, name it plainly.
9. If the *Sensitive Context* section in CLAUDE.md is filled, ask once:
   "How are you carrying everything this week?" — then wait. No frameworks.
10. Write `reviews/weekly/YYYY-WNN.md` using this format:

    ```
    # Week Review — YYYY-WNN (DD Mon – DD Mon)

    [One-paragraph honest read of the week.]

    ## Wins / Losses
    - Top win:
    - Top miss:
    - Best day: / Hardest day:

    ## Habits
    - [habit]: N/7 [+ streak note]

    ## State trend
    - energy avg N.N — [trend in one line]
    - motivation avg N.N — [trend]
    - stress avg N.N — [trend, with what drove the peaks]

    ## Against the quarter
    [2–3 lines: did the week serve the season's top focus areas?]

    ## Patterns
    [Anything that fired from the operating manual; recurring behaviours]

    ## One adjustment
    [The single proposed change — or "none warranted"]
    ```

11. Append pattern observations to `meta/reflections.md` (dated, specific)
12. Propose one adjustment — habit, schedule, or priority — if the data warrants it
