# Why Livebook? Technical Foundation of Coding5s

Every platform makes trade-offs. Coding5s chose Livebook for four inescapable reasons. This document explains why, what we rejected, and how to get started.

---

## 🎯 The Core Requirement

Coding5s needed a platform where:
1. **Code and explanations live side by side** (no switching between tabs/windows)
2. **Every concept is executable** (no "copy this code and hope")
3. **Version control works** (curriculum changes must be diffable, forkable, auditable)
4. **Zero environment setup** (students install one thing, click one button)

**Livebook is the only tool that satisfies all four.**

---

## 🏗️ What Livebook Is

[Livebook](https://livebook.dev) is an open-source, Elixir-based interactive notebook platform originally built for Elixir, but with **first-class Python support** via `{:erlport}` and the `Python` cell type.

For Coding5s, Livebook runs **pure Python 3.10+** inside `.livemd` files (Markdown with executable code cells).

**Key features we use:**
- Markdown for explanations
- Python code cells with real output
- Hide hints behind foldable sections
- Notebook linking (Stage 1 → Stage 2 → Stage 3 via relative paths)
- Zero-config local runtime (Livebook Desktop bundles Python)

---

## ❌ Alternatives Considered (and Rejected)

| Platform | Why We Rejected It |
|----------|---------------------|
| **Jupyter Notebooks** (`.ipynb`) | JSON-based = terrible for git diffs. Encourages cell-out-of-order execution. No native foldable sections for Scrolling Barrier. |
| **Google Colab** | Requires Google account. Cloud-only (no offline). Execution state can disappear. Hard to version control. |
| **Replit** | Proprietary, subscription for private notebooks. Not forkable on GitHub. |
| **VS Code + Markdown** | No native code execution in Markdown. Requires manual Python environment setup (fails "zero setup"). |
| **Custom Web App** | Massive maintenance burden. No community tooling. Would take months to reach Livebook's polish. |
| **Quarto** | Great for reports, but code execution requires separate kernel setup. Overkill for interactive learning. |

**Livebook won because it's the only notebook that treats `.livemd` as plain text and respects the Scrolling Barrier via `<!-- livebook: -->` directives and foldable `<details>` blocks.**

---

## 🔬 The Scrolling Barrier in Livebook

Livebook allows **foldable Markdown sections** using HTML `<details>` tags. This is how Coding5s implements the Scrolling Barrier:

```markdown
<details>
<summary>📚 Click for solution (after attempting!)</summary>

```python
# Full solution here
print("You scrolled past the barrier")