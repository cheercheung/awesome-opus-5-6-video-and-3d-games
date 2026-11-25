# Maintain the video prompt gallery

The English README is the editorial source. The [case data](../data/opus-5-6-usecase-curated.json) records source URLs, posting accounts, dates, prompt sources and the evidence type. [Content layout](../data/content-layout.json) records the case routes and media. The ten translated READMEs carry the same cards in the same category order.

## Choosing evidence

- Open the original source. Confirm the posting account, date and model claim. Record conflicting primary sources on the detail page.
- Distinguish what the original video shows from what the poster reports. Keep gameplay recordings, trailers, playable builds and 3D scene demos labeled by evidence.
- Use a source thumbnail for the preview and the creator platform's video link for playback. Include the original post as a second way to reach the work. Source media and authored prompts retain their respective rights.
- Include a Prompt section when the creator has published the exact text. Preserve the original text, cite it, and state whether the entry contains a scoped excerpt such as the original brief. Use Demo when the complete relevant prompt text is unavailable.

## Updating the gallery

1. Deduplicate by source post ID and by the work shown. Keep existing case IDs, slugs and anchors stable.
2. Update both JSON files, the [case index](../data/opus-5-6-usecase-curated.md), and the localized README galleries and details. Relative detail links must return to the matching language and case.
3. Keep three cards per row and reconcile each menu count against the cards in that category.
4. Run `git diff --check` and confirm that the gallery, preview images, source links and full videos work. Compare all languages against the source inventory.
5. Check the live star count before changing Star History. The template adds it at 10 stars.

The gallery uses the Evolink [Video Prompt Gallery template](https://github.com/cheercheung/agent-repo/blob/b7ca117e02bc8905e388ad7ee22eb16624ebc425/agents/model-repo-pipeline/bundled-skills/github-template/templates/video-prompt-readme.md.tmpl). The shared cover was generated with GPT and is committed in the repository.
