# Maintain the case library

The English README is the editorial source. The [curated JSON](../data/opus-5-6-usecase-curated.json) records the case order, source URLs, posting accounts, dates and evidence types. The ten translated READMEs carry the same cases and links in the same order.

## Choosing evidence

- Open the original source and confirm the account, date and claimed model before adding an entry. Credit the posting account and identify a different creator if the source establishes one.
- Separate what the post shows from what the poster reports. Use the attribution line for the model claim and update it only when there is stronger, public evidence linked in the entry.
- Label gameplay footage, trailers and playable builds distinctly. Run a publicly linked build before describing it as verified playable.
- Link to the source post for playback. The cover is original artwork shared by all language editions. Original posts and linked third-party media keep their own rights.

## Updating an entry

1. Deduplicate by post ID and check for reposts of the same work.
2. Add or update the source record in the curated JSON and the case index. Keep published case numbers stable.
3. Keep the menu, case anchors, source URLs and metadata aligned across all 11 READMEs. Translate new notes and update the counts.
4. Run `python3 -m json.tool data/opus-5-6-usecase-curated.json >/dev/null` and `git diff --check`. Open the Markdown preview and test the menu, language badges and source links. Confirm every updated model attribution matches the cited evidence.
5. If the repository reaches 10 GitHub stars, verify the live count before adding Star History to the end of each README.

The repository uses the Evolink Use Case README template from [agent-repo](https://github.com/cheercheung/agent-repo) at commit `b7ca117e02bc8905e388ad7ee22eb16624ebc425`. The Quick Start navigates the collection. Model access claims and playback are left to their original sources.
