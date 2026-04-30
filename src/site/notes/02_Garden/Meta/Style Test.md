---
{"dg-publish":true,"dg-pinned":false,"dg-note-icon":"🍎","status":"fruit","category":"Meta","permalink":"/meta/style-test/","dg-created":"30 April 2026, 04:41","dg-updated":"30 April 2026, 04:41","author":"Jackie Plage","tags":["status/fruit","meta/csstest"],"description":"CSS test page","dg-path":"Meta/Style Test.md","dgPassFrontmatter":true,"noteIcon":"🍎","created":"30 April 2026, 04:41","updated":"30 April 2026, 04:41","dg-note-properties":{"status":"fruit","category":"Meta","permalink":null,"author":"Jackie Plage","tags":["status/fruit","meta/csstest"],"description":"CSS test page"}}
---


# BRAIN STATIC: STYLESHEET TEST

This is the ultimate benchmark note for testing the current css on the site.

---

## 1. Typography & Hierarchy (The Header Stack)
Testing `--h1-color` through `--h6-color`.

# Level 1 Heading (H1)
## Level 2 Heading (H2)
### Level 3 Heading (H3)
#### Level 4 Heading (H4)
##### Level 5 Heading (H5)
###### Level 6 Heading (H6)

---

## 2. Text Decorations (Inline Signals)
Testing `--text-normal`, `--text-muted`, and `--text-accent`.

- **Bold text** for heavy emphasis (`--text-bold`).
- *Italic text* for secondary thoughts (`--text-italic`).
- ***Bold and Italic*** for critical system alerts.
- ~~Strikethrough~~ for deprecated ideas.
- ==Highlighted Text== for the ADHD-essential "Read this first" signal.
- `Inline code` for variables and terminal commands (`--code-normal`).

---

## 3. Lists & Tasks (The ADHD Buffer)
Testing indentations and bullet colors.

- Unordered List Item
    - Nested Item Level 1
        - Nested Item Level 2
- [ ] Task List: Unchecked
- [/] Task List: In Progress
- [x] Task List: Completed
- [!] Task List: Important

1. Ordered List Item 1
2. Ordered List Item 2
    1. Nested Ordered 1
    2. Nested Ordered 2

---

## 4. Callouts & Blockquotes (Recessed Data)
These are critical. In a terminal theme, callouts should look like "sub-terminals" or recessed windows.

> [!abstract] NAVIGATION
> This is an abstract callout. It usually handles the metadata summary at the top of notes.

> [!info] SYSTEM LOG
> This is a standard info callout. Testing `--text-accent`.

> [!warning] VOLTAGE SPIKE
> Warning callouts for risky ideas or half-baked thoughts.

> [!danger] CRITICAL FAILURE
> High-contrast red/magenta text should go here.

> This is a standard blockquote. It should have a distinct border color controlled by `--blockquote-border-color`.
>> This is a nested blockquote for even deeper recursion.

---

## 5. Data Structures (Tables & Math)
Testing the "Structured" side of the brain.

| Command | Action | Status |
| :--- | :---: | ---: |
| `git push` | Upload to Garden | `OK` |
| `npm run build` | Compile Noise | `ERROR` |
| `brain --static` | Process ADHD | `ACTIVE` |

### Mathematical Formulas (LaTeX)
Testing if the engine renders complex physics/math variables properly.

The energy of the "Brain Static" state is defined as:
$$ E = mc^2 + \int_{noise}^{signal} f(adhd) \,dt $$

---

## 6. Code & Logic (Fenced Blocks)
Testing syntax highlighting against your background-primary.

```python
def brain_static_loop():
    thoughts = ["Music", "Tech", "Books", "Static"]
    for thought in thoughts:
        print(f"Synthesizing {thought}...")
    return "System Online"
```

---

## 7. Connectivity (Links & References)
- **External Link:** [The Digital Garden Repo](https://github.com/oleeskild/digitalgarden)
- **Internal Link:** [[02_Garden/Meta/Meta\|Meta]]
- **Footnote Link:** This thought needs a citation[^1]. 

[^1]: This is the footnote content at the bottom of the system log.

---