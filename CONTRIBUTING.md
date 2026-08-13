# Contributing to Awesome AI Engineering

Thank you for helping grow this collection! 🎉 This list stays valuable because every resource is **free, verified, and comes with practical usage guidance** — contributions must keep that bar.

---

## 🧭 Ways to Contribute

| I want to… | Do this |
|------------|---------|
| Suggest a resource (easiest) | [Open a "Resource Suggestion" issue](../../issues/new/choose) |
| Add a resource myself | Submit a Pull Request (guide below) |
| Report a dead/changed link | [Open a "Broken Link" issue](../../issues/new/choose) |
| Improve a description or "how to use" tip | Submit a small PR — these are very welcome |
| Reorganize / propose a new section | Open an issue first to discuss |

---

## ✅ Acceptance Criteria

A resource is accepted when it meets **all** of these:

1. **Free** — completely free, or a free tier good enough to genuinely learn/build with
2. **Relevant** — directly about AI agents, AI automation, or AI engineering (RAG, evals, serving, observability, prompting)
3. **Active** — maintained within the last ~12 months (or a timeless paper/book)
4. **Tried by you** — you have personally used it; don't submit from a headline
5. **Has a "How to use it" tip** — a concrete first step, command, or strategy (this is the whole point of this list!)

### ❌ Not accepted

- Paid courses/tools without a meaningful free tier
- Affiliate or referral links
- Your own product without disclosure (disclose it — genuinely useful self-submissions are fine)
- Listicles/blog spam with no original substance
- Duplicates of resources already listed

---

## 📝 Adding a Resource (PR Guide)

### 1. Fork & branch

```bash
git clone https://github.com/YOUR_FORK/awesome-ai-engineering.git
cd awesome-ai-engineering
git checkout -b add/resource-name
```

### 2. Add your row in the right section

Every table follows this format — **all three columns are required**:

```markdown
| [Resource Name](https://link) | What it is — one factual sentence, 15–40 words, no hype words ("revolutionary", "game-changing") | How to use it — a concrete first command, step, or strategy |
```

**Good example:**

```markdown
| [promptfoo](https://github.com/promptfoo/promptfoo) | Test prompts and agents like code — YAML test cases, CI integration, side-by-side model comparison | `npx promptfoo init` → write 10 test cases for your prompt → run on every change |
```

**Bad example (will be rejected):**

```markdown
| [Cool Tool](https://link) | An amazing revolutionary AI tool that will change everything! | Check out the website |
```

### 3. Placement rules

- Add to the **most specific** matching section
- Keep alphabetical order *within* a table where one exists, otherwise append at the end
- One resource per PR is ideal; max 3 related resources per PR

### 4. Commit & open the PR

```bash
git add README.md
git commit -m "Add: promptfoo to Evaluation & Testing"
git push origin add/resource-name
```

Fill in the PR template completely — especially **"How have you used this resource?"**

---

## 🏅 Contributor Recognition

- Every merged PR automatically appears in the **[Contributors](README.md#-contributors)** section (via contrib.rocks, generated from GitHub's contributor graph)
- Significant contributions (new sections, major reorganizations, sustained curation) are credited by name in release notes
- Repeat contributors may be invited as collaborators with triage rights

---

## 🔍 Review Process

1. A maintainer reviews within ~1 week
2. We check: link works → criteria met → description accurate → "how to use" is genuinely actionable
3. We may edit wording for consistency before merging (you keep authorship)
4. Merged! You're now on the contributors wall ✨

---

## 💬 Community Standards

Be respectful, be honest about what you've actually used, and assume good intent. See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

---

## 📜 License

By contributing you agree your contributions are licensed under the project's [MIT License](LICENSE).
