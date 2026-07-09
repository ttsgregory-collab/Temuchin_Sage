# Writing Guide for Temuchin_Sage

## Chapter Format

Each chapter should be a separate Markdown file in the `chapters/` directory.

### Naming Convention
```
chapters/01_chapter-title.md
chapters/02_another-chapter.md
chapters/03_section-name.md
```

### Chapter Header Template
```markdown
# Chapter 1: Opening

**Themes:** loss, transition, discovery  
**Timeline:** [specific date or era]  
**Key moments:** [brief outline]

---

[Chapter content starts here]
```

## Writing in Markdown

### Basic Formatting
```markdown
# Heading 1 (Chapter title)
## Heading 2 (Section)
### Heading 3 (Subsection)

**Bold text** for emphasis
*Italics* for subtle emphasis
> Blockquotes for reflection or dialogue

[Link text](url) for references
```

### Tips for Memoir Writing

- **Scene-setting:** Use vivid details. Put readers *there*.
- **Dialogue:** Use quotation marks naturally. Let voices breathe.
- **Reflection:** Break scenes with internal thoughts or present-day commentary.
- **Chronology:** Number chapters logically, but feel free to jump timelines if it serves the narrative.
- **Authenticity:** Write in your voice. Don't aim for perfection—aim for truth.

## Workflow

### Draft Phase
1. Write rough drafts in `drafts/` as you explore ideas
2. Move polished sections to `chapters/` when ready
3. Use **commit messages** to note what you revised:
   ```
   git commit -m "Chapter 3: Expanded memory of childhood home"
   git commit -m "Drafts: Raw notes on transition period"
   ```

### Revision Process
- Keep old versions in Git history (never delete)
- Use **branches** for major rewrites:
  ```
  git checkout -b chapter-3-revision
  # Make changes, then merge back when satisfied
  ```
- Add **comments** in draft files for future work:
  ```markdown
  <!-- TODO: Verify this date with photos -->
  <!-- QUESTION: Should this scene go in Chapter 2 instead? -->
  ```

### Metadata
Fill in `metadata/book-info.md` as your project develops:
- Working title
- Themes and motifs
- Timeline / era
- Central figures / relationships
- Intended audience

## Tools & Integration

### Converting to PDF or EBOOK
When ready, consider:
- **Pandoc** — converts Markdown to PDF, EPUB, Word, etc.
- **mdBook** — generates a beautiful website from your chapters
- **Calibre** — formats for e-readers

### Sharing & Feedback
- Use GitHub's **Issues** to track writing goals or questions
- Use **Pull Requests** to share drafts with beta readers
- Use **Discussions** for thematic reflections or brainstorming

---

**Remember:** First drafts are supposed to be messy. Git has your back—every version is saved.

Happy writing.
