---
type: documentation
tags:
  - philosophy
  - utility/documentation
created: 2025-10-18
---

# 📖 Using Your Philosophy Learning Environment

Welcome to your structured philosophy study vault! This environment is designed following **Zettelkasten principles** and organized into **7 stages** covering 14-22 months of intensive study.

---

## 🚀 Quick Start

1. **Start here**: Open [[Philosophy Dashboard]] - Your main navigation hub
2. **Begin learning**: Read [[Stage 1 - Foundations]]
3. **Understand the system**: Read [[CLAUDE.md]] for vault conventions
4. **Check the source material**: [[Study Plan v2 (claude)]] and [[Questions (claude)]] in the Unbroken folder

---

## 📂 Vault Structure

### Note Types (Zettelkasten)

Your vault uses **5 types of notes**:

1. **Literature Notes** (`@Author - Title.md`)
   - Reading notes from primary sources
   - Example: `@Plato - Republic.md`
   - Capture key ideas, arguments, questions

2. **Permanent Notes** (Concept names)
   - Atomic ideas that stand alone
   - Example: `Eudaimonia.md`, `Theory of Forms.md`
   - One concept per note, heavily linked

3. **Question Notes** (`Q - Question.md`)
   - Philosophical questions driving inquiry
   - Example: `Q - What is the good life.md`
   - Track evolving answers across traditions

4. **Structure Notes** (`Topic - MOC.md`)
   - Maps of Content organizing domains
   - Example: `Ancient Greek Ethics - MOC.md`
   - Entry points and navigation hubs

5. **Synthesis Notes** (Descriptive titles)
   - Your original arguments and positions
   - Example: `Reconciling Aristotle and Nietzsche.md`
   - Build on permanent notes with original analysis

### Special Folders

- **Unbroken/** - Protected original study plans and questions (DO NOT EDIT)
  - `Study Plan v2 (claude).md` - Complete curriculum
  - `Questions (claude).md` - Question framework

---

## 🎯 The 7-Stage Learning Path

### Stage 1: Foundations (1 month)
**Goal**: Learn what philosophy is and how to think philosophically
- [[Stage 1 - Foundations]]

### Stage 2: Ancient Greek Philosophy (2-3 months)
**Goal**: Build foundation in classical thought
- Pre-Socratics, Socrates, Plato, Aristotle, Hellenistic
- [[Stage 2 - Ancient Greek Philosophy]]

### Stage 3: Medieval & Early Modern (2-3 months)
**Goal**: Bridge ancient and modern philosophy
- Medieval, Rationalism, Empiricism
- [[Stage 3 - Medieval & Early Modern Thought]]

### Stage 4: Enlightenment & Existential Roots (2-3 months)
**Goal**: Understand Kant and precursors to Nietzsche
- Kant, Hegel, Schopenhauer, Kierkegaard
- [[Stage 4 - Enlightenment & Existential Roots]]

### Stage 5: Nietzsche Deep Dive (3-4 months)
**Goal**: Master Nietzsche's philosophy thoroughly
- All major works systematically
- [[Stage 5 - Nietzsche Deep Dive]]

### Stage 6: Diverse Traditions (4-6 months)
**Goal**: Gain breadth across traditions
- Continental, Analytic, Eastern, Political
- [[Stage 6 - Diverse Traditions]]

### Stage 7: Integration & Living Philosophy (Ongoing)
**Goal**: Synthesize and live your philosophy
- The Big Five Essays, Personal Manifesto
- [[Stage 7 - Integration & Living Philosophy]]

---

## 📊 Using the Dashboard

The [[Philosophy Dashboard]] provides:

### Progress Tracking
- **All Stages** - Status overview
- **Current Reading** - What you're reading now
- **Completed Books** - Track accomplishments

### Database Views (Obsidian Bases)

The dashboard uses Obsidian's **Bases** feature - a built-in database system that creates dynamic views of your notes.

**What are Bases?**
- Bases are `.base` files that define filtered, sorted views of your notes
- They use YAML syntax to specify filters, columns, and sorting
- Embedded in markdown using `![[filename.base]]`
- Automatically update as you change note properties

**Base Files in This Vault:**
- `Stages Progress.base` - Overview of all 7 stages
- `Books Not Started.base` - Upcoming reading list
- `Books In Progress.base` - Current readings
- `Books Completed.base` - Finished books
- `Questions Unanswered.base` - Open philosophical questions
- `Books by Branch - Ethics.base` - Ethics books
- `Books by Priority - Critical.base` - Must-read texts
- `Revisitation Due.base` - Texts to revisit

**How They Work:**
All bases filter notes based on their YAML frontmatter properties (type, status, stage, branch, priority, etc.).

### Browsing
- By Stage (1-7)
- By Branch (Ethics, Metaphysics, Epistemology, Political)
- By Period (Ancient, Medieval, Modern)
- By Priority (Critical, High, Medium)

---

## 🔄 The Learning Workflow

### Daily Practice

1. **Morning**:
   - Open current Stage note
   - Review current Literature Note
   - Set reading goal

2. **Reading Session**:
   - Actively engage with text
   - Create links to concepts as you read
   - Mark confusing passages

3. **Processing** (After reading):
   - Extract 2-3 Permanent Notes (atomic concepts)
   - Create/update Question Notes
   - Link bidirectionally
   - Update Stage progress

4. **Evening**:
   - Philosophical journaling (15 min)
   - Review backlinks - unexpected connections?

### Weekly

- **Monday**: Review last week, strengthen links
- **Friday**:
  - Create/update Structure Note (MOC)
  - Write 500-word Synthesis Note
  - Update [[Philosophy Dashboard]]

### Monthly

- **Week 4**: Revisitation week
  - Reread one foundational text
  - Update old notes with new insights
  - Create comparative Synthesis Note

### Quarterly

- Write 2000-word stage synthesis essay
- Create comprehensive MOC for completed stage
- Comparative analysis across stages

---

## 📝 Note-Taking Best Practices

### When Reading a Book

1. **Create Literature Note**:
```markdown
@Philosopher - Work Title.md
```

2. **Add YAML frontmatter**:
```yaml
---
type: literature-note
author: Name
stage: 2
branch: [ethics, metaphysics]
status: in-progress
---
```

3. **Structure**:
- Context
- Main Thesis
- Key Arguments
- Important Concepts (link to [[Permanent Notes]])
- Questions Raised
- Personal Insights

4. **Extract Concepts**:
- Create Permanent Note for each new concept
- Link bidirectionally
- Connect to existing notes

### When Creating Permanent Notes

**Atomic principle**: One idea per note

**Structure**:
- Definition (your own words)
- Origin (who introduced it?)
- Examples
- Related Concepts (10-20 links)
- Critiques
- Evolution across thinkers

### Question-Driven Learning

Use the **Five Question Types** from [[Questions (claude)]]:

1. **INTERPRETIVE** - What is the philosopher saying?
2. **CRITICAL** - Is the argument sound?
3. **COMPARATIVE** - How does this relate to others?
4. **APPLIED** - How does this matter for life?
5. **SYNTHETIC** - What is MY position?

---

## 🔍 Search & Discovery

### Finding Connections

1. **Graph View** - Spot clusters of related concepts
2. **Backlinks Panel** - Who references this note?
3. **Search** - How does usage evolve across texts?
4. **Tags** - Filter by philosopher, branch, period
5. **Unlinked Mentions** - Create explicit links

### Using Tags

**Hierarchical structure**:
- `#philosopher/plato`
- `#branch/ethics`
- `#period/ancient-greek`
- `#theme/virtue`

**In frontmatter** (primary categorization):
```yaml
tags: [plato, ethics, ancient-greek]
```

**Inline** (contextual):
```markdown
This connects to #master-slave-morality
```

---

## 🔄 Revisitation (Spiral Learning)

Philosophy deepens through returning to earlier texts with new knowledge.

### Revisitation Schedule

**After each stage**:
- Return to 5 key texts from earlier stages
- Add `## Revisitation - [Date]` section
- Create new connections

**Monthly**:
- Pick one earlier philosopher
- Review all their Literature Notes
- Update with recent learning

**Quarterly**:
- Write comparative essay
- Example: "Plato's Forms Through Kantian Lenses"

**Yearly**:
- Reread foundational texts:
  - Plato's Republic
  - Aristotle's Ethics
  - Nietzsche's Genealogy

### Built-in Revisitation Prompts

Each Stage note includes prompts like:
- "After Stage 4, return to Plato with these questions..."
- "After Stage 5, return to Aristotle and ask..."

---

## 🎓 Integration & Synthesis

### The Big Five Questions (Stage 7)

Write 2000-3000 word essays on:

1. [[Q - What Is Real]] - Metaphysics
2. [[Q - What Can We Know]] - Epistemology
3. [[Q - How Should I Live]] - Ethics
4. [[Q - What Is the Meaning of Life]] - Existential
5. [[Q - What Is the Good Society]] - Political

### Personal Philosophy Manifesto

**Capstone Project** (10,000 words):
- Part I: Metaphysics & Epistemology
- Part II: Ethics & Values
- Part III: Existential & Meaning
- Part IV: Social & Political
- Part V: Practice & Living

---

## 🛠️ Using Claude Code

When working with Claude Code in this vault:

1. **Read [[CLAUDE.md]]** first - Complete guide for AI assistance
2. **Follow Zettelkasten principles** - Atomic notes, heavy linking
3. **Respect protected areas** - Never edit Unbroken/ folder
4. **Use proper naming conventions**:
   - `@Author - Title` for books
   - `Q - Question` for questions
   - `Topic - MOC` for structure notes

Claude Code can help you:
- Create properly formatted notes with frontmatter
- Extract Permanent Notes from reading
- Find connections between concepts
- Generate comparative analyses
- Organize notes into MOCs
- Track progress and suggest next steps

---

## 🔧 Creating Custom Base Files

You can create your own `.base` files for custom views:

**Example: Create a "Books by Difficulty - Advanced" base**

1. Create file: `Books by Difficulty - Advanced.base`
2. Add YAML:
```yaml
formulas:
views:
  - type: table
    name: Advanced Books
    filters:
      and:
        - note["type"] == "literature-note"
        - note["difficulty"] == "advanced"
    order:
      - file.name
      - author
      - stage-name
      - status
    sort:
      - key: stage
        direction: ASC
```
3. Embed anywhere: `![[Books by Difficulty - Advanced.base]]`

**Base Syntax Reference:**

**Structure:**
- `formulas:` - Define custom formulas (can be empty)
- `views:` - Array of view definitions
  - `type:` table, list, calendar, or task
  - `name:` Display name
  - `filters:` Filter conditions
  - `order:` Properties to display as columns
  - `sort:` Sorting rules
  - `limit:` Maximum results (optional)

**Filter Syntax:**
- Access properties: `note["property-name"]`
- Equality: `note["type"] == "value"`
- Inequality: `note["status"] != "completed"`
- Contains: `contains(note["branch"], "ethics")`
- **MUST** use `and:` or `or:` at filter root
- Nest `or:` inside `and:` for complex logic

**Sort Syntax:**
- Use `key:` for property name
- Use `direction:` ASC or DESC
- Can sort by `file.name`, `file.mtime`, custom properties

---

## 📈 Tracking Progress

### Update Book Status

In Literature Notes, change frontmatter:
```yaml
status: not-started  # → in-progress → completed
```

### Update Stage Status

In Stage Notes:
```yaml
status: not-started  # → in-progress → completed
```

### Watch the Dashboard

The [[Philosophy Dashboard]] and all `.base` files automatically update!

---

## 💡 Tips for Success

### Do:
- ✅ Read actively, create notes as you go
- ✅ Link extensively (10-20 links per Permanent Note)
- ✅ Write in your own words
- ✅ Create Question Notes to track inquiries
- ✅ Revisit earlier material regularly
- ✅ Write Synthesis Notes with original thinking
- ✅ Update the dashboard regularly

### Don't:
- ❌ Passively read without taking notes
- ❌ Create orphan notes (no links)
- ❌ Just copy quotes (understand first)
- ❌ Move too fast (philosophy requires slow thinking)
- ❌ Skip revisitation (spiral learning is key)
- ❌ Forget to apply concepts to life

---

## 🔗 Key Resources

### In This Vault
- [[Philosophy Dashboard]] - Main hub
- [[CLAUDE.md]] - AI assistant guide
- [[Study Plan v2 (claude)]] - Complete curriculum (Unbroken/)
- [[Questions (claude)]] - Question framework (Unbroken/)

### External
- [Stanford Encyclopedia of Philosophy](https://plato.stanford.edu/)
- [Internet Encyclopedia of Philosophy](https://iep.utm.edu/)
- Gregory Sadler (YouTube) - Text close readings
- Philosophize This! (Podcast) - Chronological history

---

## 🎯 Getting Started Checklist

- [ ] Read this README completely
- [ ] Open [[Philosophy Dashboard]]
- [ ] Read [[CLAUDE.md]]
- [ ] Review [[Stage 1 - Foundations]]
- [ ] Get first book: Bertrand Russell - The Problems of Philosophy
- [ ] Create your first Literature Note
- [ ] Set up daily practice schedule
- [ ] Begin the journey!

---

**Remember**: Philosophy is not about accumulating answers but about deepening questions. The point is not to finish, but to continue examining, questioning, and living thoughtfully.

*"The unexamined life is not worth living." - Socrates*

*"One must still have chaos in oneself to give birth to a dancing star." - Nietzsche*

*"One must imagine Sisyphus happy." - Camus*

Now begin walking. The questions await.
