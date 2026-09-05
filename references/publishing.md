# Medium execution

Use the browser tool's documented controls and freshly observed state. Do not guess tool APIs, element IDs, or selectors. Do not access private endpoints or reuse browser credentials outside authorized browser operations.

## Before editing

Identify whether the user wants a new story or an update. Preserve the existing URL for ordinary edits. Read the latest local draft before insertion, including user edits and CTA choices.

Confirm title, subtitle, body, references, chosen account, destination, and intended access model. Establish whether the story is original to Medium or a cross-post; set a canonical link only to the actual original source and measure the canonical destination accordingly. Compare the current title with the title decision record when one exists. If an edit changes a researched target question or article promise, do not publish it as though the original research still applies; perform the focused recheck defined in the skill. For an editorial-only article, verify the title against the reader promise without claiming search validation.

Check the current [Medium AI-content policy](https://help.medium.com/hc/en-us/articles/22576852947223-Artificial-Intelligence-AI-content-policy) and [paywall eligibility rules](https://help.medium.com/hc/en-us/articles/31090080813591-Content-not-eligible-for-the-paywall) before setting access. Record whether the agent generated text or images, the author's material contribution, the disclosure needed, and whether the story is mainly about Medium itself. AI-generated text, or AI-assisted text inserted into the story, requires the disclosure specified by current policy; help limited to outlining, spelling, grammar, or fact verification does not. Do not enable the paywall when the observed provenance or subject makes the story ineligible.

Prepare mode does not operate the publish controls. Publication authorization persists within the task; do not ask again unnecessarily.

## Editor

Create or open the correct story. Paste through the browser's supported clipboard, which may differ from the operating system clipboard. Prefer supported rich text or deliberate formatting over pasting raw Markdown and assuming it renders.

Use Medium's own Unsplash option when requested; locate it in the current editor menu or insertion controls. Select a relevant image after visual inspection, retain photographer attribution, and write literal alt text. Do not assume right-click or any past UI layout still exposes the same controls.

Apply actual subtitle formatting. Verify body paragraphs, references heading, links, image position, disclosure, and unwanted blank paragraphs visually as well as through accessible text.

Map the prepared fields to controls actually visible in the current editor:

- **Story title and subtitle:** text displayed on the story page.
- **Preview title and subtitle:** optional custom fields used in Medium and social previews when exposed.
- **Proposed search snippet:** planning metadata. Apply it only if the editor exposes a corresponding control; otherwise retain it in the deliverable and verify the rendered page title/description after publication.

Set up to five accurate topics. Keep every visible title, subtitle, description, and preview image aligned with the same article promise. Character lengths are preview heuristics, not ranking rules. Avoid keyword stuffing or metadata promising a method the article no longer contains.

Preserve appropriate canonical attribution. Record platform-controlled technical limits instead of claiming to fix infrastructure.

## Submission

Inspect the fully loaded submission dialog. Distinguish publishing to the author's profile, publishing directly to a publication when authorized as an editor, and submitting to a publication for review. Confirm that the observed final action matches the requested destination; a submission for review is not a publication. Confirm preview, topics, paywall, and notification settings immediately before the final action. Do not interpret disabled or still-loading controls as their final state.

Publishing permission does not imply subscriber email permission. Honor existing explicit notification preferences; otherwise keep notifications off. If notification/access state cannot be established or changed to match the authorized request, leave the draft ready and explain the specific blocker.

Before the final action, record the draft URL or story identifier, title, opening text, destination, and submission time. Submit once. On an uncertain result, reload the recorded draft and inspect the author's stories, profile, or destination publication for that fingerprint. Retry only after absence is established; otherwise report the result as ambiguous rather than risking a duplicate.

Verify the resulting URL, title/subtitle, image/credit/alt text, body, disclosure, references, topics, and visible access state. Check public accessibility and paywall behavior in a logged-out context or public fetch when available; an author-session view proves only authenticated visibility. Check rendered title, description, canonical, and robots metadata when tools expose them. Distinguish checks performed from checks unavailable, and record publication confirmation separately from indexing or ranking.
