## AI interaction 1
Date:10/14/20226
Assistant: GitHub CoPilot
Purpose: Explanation of GitHub history
Prompt or summary: can you help me Explain what a GitHub history view shows.
Useful Suggestion: A GitHub history view shows the repository’s commits in order, usually with the newest first. Each entry typically includes who made the commit, when it was made, and its message describing the change. Selecting a commit lets you inspect the files and lines that were added, changed, or removed. The history is tied to a branch, so it shows that branch’s recorded commits rather than every edit made locally.

You could write: “The GitHub history view is a timeline of saved changes to a repository. It shows commit messages, authors, and dates, and lets you open a commit to review the exact changes it contains.”
Decision: revised
Reason: simple revision at the start of the prompt
Related GitHub URL: https://github.com/MichieRulz/swe325_325_525-github-ai-practice.git

## AI interaction 2
Date: 10/14/20226
Assistant: GitHub CoPilot
Purpose: Explanation of different areas of GitHub
Prompt or summary: can you Explain the difference between a repository, branch, commit, pull request, and issue
Useful Suggestion: A **repository** is the project space that stores files, history, and collaboration activity.

A **branch** is a separate line of work within a repository. It lets you make changes without changing the main branch right away.

A **commit** is a saved snapshot of changes on a branch, usually with a message explaining what changed.

A **pull request (PR)** proposes merging changes from one branch into another. Teammates can review, discuss, and approve the changes before they’re merged.

An **issue** tracks a task, bug, question, or idea. It helps organize work but doesn’t itself contain code changes.

In short: issues describe work; branches hold work in progress; commits save changes; pull requests request review and merging; repositories contain it all.
Decision: revised 
Reason: Simple revision at the start of the prompt
Related GitHub URL: https://github.com/MichieRulz/swe325_325_525-github-ai-practice.git

## AI interaction 3
Date: 10/14/20226
Assistant: GitHub CoPilot
Purpose: Checklist for pull-request description
Prompt or summary: Can you Suggest a checklist for a complete pull-request description.
Useful Suggestion: A complete pull-request description can include this checklist:

- [ ] **Summary:** What does this PR change?
- [ ] **Reason:** Why are these changes needed?
- [ ] **Related issue:** Link the issue, if there is one.
- [ ] **Changes made:** List the main updates.
- [ ] **Testing:** Explain what you tested and the results.
- [ ] **Screenshots or recordings:** Add them for visual changes.
- [ ] **Impact or risks:** Note anything reviewers should be aware of.
- [ ] **Review notes:** Point reviewers to areas that need special attention.

**Example template:**

```markdown
## Summary
[Briefly describe the change.]

## Motivation
[Explain why the change is needed.]

## Changes
- [Main change]
- [Another change]

## Testing
[Tests run and results.]

## Related issue
Closes #[issue number]

## Notes for reviewers
[Any risks or areas needing extra attention.]
```
Decision: revised 
Reason: Simple revision at the start of the prompt
Related GitHub URL: https://github.com/MichieRulz/swe325_325_525-github-ai-practice.git