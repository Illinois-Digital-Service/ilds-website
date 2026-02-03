# Dev workflow guide

A Git & GitHub workflow guide for Illinois Digital Service website development.

---

## 1. Picking up a task

This is where we begin!

We'll discuss tasks to be done in our regular project checkin meetings. We discuss as a team what work should be prioritized, and who has capacity to take it on.

We track work to be done through stories on our project sprint board: https://github.com/orgs/Illinois-Digital-Service/projects/2

Once you have a task, note the issue number — you'll use it in your branch name.

## 2. Getting set up locally

**Pull the latest changes**

```bash
git pull origin main
```

**Create a branch linked to the issue**

Include your initials and the issue number in your branch name:

```bash
git checkout -b jn/42/fix-contact-form
```

Examples: `jn/42/fix-contact-form`, `mc/107/add-faq-page`, `kp/89/update-footer-links`

This makes it easy to connect branches back to the issue they're solving and helps us know who is working on each branch.

## 3. Write code!

✨ Coding work happens here. ✨

## 4. Save your work with git

### The main idea

⚠️ Before committing your work, take a moment to review what you're about to save.

This helps us avoid accidentally including things like test data, personal information, or files that don't belong.

### Working on an issue

Check the files that your work touched:

```bash
git status
```

This shows every file that's been modified. Take a look and make sure you recognize everything.

**Review the changes**

```bash
git diff
```

Scan through and check:
- Does this look right?
- Any debugging code left in? (console.log, test data, etc.)
- Any PII that shouldn't be there?

**Stage files intentionally**

Rather than `git add .`, try adding files individually so you know exactly what's going in:

```bash
git add src/pages/contact.html
```

**Commit with a clear message**

```bash
git commit -m "Fix contact form validation (#42)"
```

Including the issue number (with `#`) links the commit to the issue on GitHub. Start with a verb, keep it short and specific.

**Push to GitHub**

```bash
git push origin jn/42/fix-contact-form
```

### Quick pre-commit checklist

- [ ] `git status` — Do I recognize all these files?
- [ ] `git diff` — Do the changes look right?
- [ ] No debugging code left in
- [ ] No PII or other info that shouldn't be there

### Useful commands

| Command | What it does |
|---------|--------------|
| `git status` | Shows what's changed |
| `git diff` | Shows line-by-line changes |
| `git log --oneline -10` | Shows recent commits |
| `git checkout -- filename` | Discards changes to a file |

---

## 5. Push your branch to GitHub ...

e.g.:

```
git push origin ars/1/add-dev-workflow-guide
```

## 6. ... and check out the preview build!

Our [preview build workflow](https://github.com/Illinois-Digital-Service/ilds-website/blob/main/.github/workflows/preview-build.yml) will automatically generate a preview build for each branch.

To find the preview build URL, look under `checks > build and deploy > Print Preview URL`.

## 7. Open a pull request

### What's a pull request?

A pull request (PR) is how we propose changes. Instead of pushing directly to `main`, we push to a branch and ask teammates to review before merging. This helps catch mistakes and share knowledge.

### Our process

- Push your branch to GitHub
- Open a Pull Request and write a brief description (what changed, why, how to test)
- Reference the issue in your PR description (e.g., "Closes #42")
- Keep PRs small when possible (easier to review)

### Writing a good PR description

Keep it simple:
- **What** does this change?
- **Why** is it needed? (link to the issue)
- **How to test** (steps a reviewer can follow)
- **Screenshots** if it's a visual change

## 8. Request reviews

Next request two reviewers using the GitHub interface.

### Reviewing code

When reviewing someone else's code:

- Read the description to understand what it's trying to do
- Look through the changes for functionality, readability, and anything that seems off
- Leave specific, helpful comments
- Be kind — frame feedback as suggestions and questions

You can **Approve**, **Request changes**, or just **Comment** without blocking.

Try to review within a day or two so that you don't block your teammates.

## 9. Receive and respond to feedback

Code review is about the code, not about you. When you get feedback:
- Assume good intent
- Ask questions if something's unclear
- It's fine to disagree — just discuss it respectfully
- A quick "good catch, fixed!" goes a long way

## 10. Merge

- PRs are ready to merge when they have **two approvals in GitHub**.
- For PRs that make major content changes, one approval should be from the product owner.
- For PRs that make small dev-related changes (e.g. updating a dependency), two dev approvals work fine.

## 11. Review the live end result!

GitHub will automatically publish changes when they are merged to `main`.

## 12. Celebrate!

🎉

---

## Questions?

If something doesn't make sense or you hit a situation this doesn't cover, just ask!
