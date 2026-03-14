# UX Design Evaluation Skills

A comprehensive skill teaching the established UX laws and how to apply them in product design and interface evaluation.

## What This Skill Does

This skill enables Claude to:

✅ **Evaluate designs** against 30 proven UX principles  
✅ **Identify issues** and explain why they're problematic  
✅ **Prioritize fixes** (Critical vs Minor)  
✅ **Apply psychology** to design decisions  
✅ **Communicate UX** clearly to any audience  
✅ **Design better** from the start

## When to Use This Skill

This skill triggers when users mention:
- UX principles, design evaluation, usability heuristics
- UI/UX critique, design feedback, design review
- Questions like "is this good UX?", "how can I improve this?"
- Specific laws (Fitts's Law, Miller's Law, Jakob's Law, etc.)
- Design problems ("users can't find X", "too many options")

## The 30 Laws Covered

### Perception & Visual Design
1. Aesthetic-Usability Effect
2. Von Restorff Effect
3. Selective Attention

### Information Architecture
4. Chunking
5. Miller's Law
6. Serial Position Effect

### Gestalt Principles
7. Law of Common Region
8. Law of Proximity
9. Law of Similarity
10. Law of Prägnanz
11. Law of Uniform Connectedness

### Decision Making
12. Choice Overload
13. Hick's Law
14. Cognitive Bias

### Interaction Design
15. Fitts's Law
16. Doherty Threshold
17. Jakob's Law
18. Postel's Law

### Cognitive Load
19. Cognitive Load
20. Working Memory
21. Mental Model

### Motivation & Completion
22. Flow
23. Goal-Gradient Effect
24. Peak-End Rule
25. Zeigarnik Effect

### Other Principles
26. Occam's Razor
27. Paradox of the Active User
28. Pareto Principle
29. Parkinson's Law
30. Tesler's Law

## How to Use

### Design Evaluation Example

**User:** "Can you evaluate this checkout flow?"

**Claude with this skill will:**
1. Ask for context (mobile/desktop, target users)
2. Identify relevant laws (Fitts's, Proximity, Goal-Gradient, Peak-End, etc.)
3. Check against evaluation criteria
4. List CRITICAL issues (e.g., buttons too small, no progress indicator)
5. List MINOR issues (e.g., inconsistent spacing)
6. Explain WHY each is an issue (connect to psychology)
7. Suggest specific fixes

### Design Decision Example

**User:** "How many items should I have in my navigation menu?"

**Claude with this skill will:**
1. Reference Miller's Law (7±2 items in working memory)
2. Recommend ≤9 top-level items
3. Suggest categorization if more needed
4. Explain Serial Position Effect (important items first/last)
5. Mention Jakob's Law (follow platform conventions)

### Quick Consultation Example

**User:** "Why should buttons be 44x44px?"

**Claude with this skill will:**
1. Explain Fitts's Law (time to target = f(distance, size))
2. Reference touch target standards (44x44px iOS/Android)
3. Show the psychology behind it
4. Provide desktop alternative (32x32px minimum)

## File Structure

```
ux-design-skill/
├── SKILL.md                    # Main skill (comprehensive guide)
├── README.md                   # This file
└── references/
    ├── quick-reference.md      # Fast lookups, thresholds, one-liners
    └── examples.md             # Real-world application examples
```

## Quick Reference Access

The skill includes a quick reference guide for:
- Severity classification (Critical vs Minor)
- Measurement thresholds (44px, 7±2 items, etc.)
- One-sentence summaries of each law
- Platform-specific notes (iOS, Android, Web)
- Common conflicts and resolutions

## Examples Included

Real-world scenarios with before/after:
- E-commerce product pages
- SaaS dashboards
- Mobile app onboarding
- Form design
- Navigation menus
- Data tables
- Modal dialogs

## Key Features

### Context-Aware
- Adapts to mobile vs desktop
- Considers industry (e-commerce, SaaS, enterprise)
- Adjusts for audience (designers, developers, stakeholders)

### Practical
- Specific thresholds (not just "make it bigger")
- Concrete examples
- Actionable fixes

### Evidence-Based
- Grounded in psychology research
- References to original studies
- Explains the "why" behind each principle

## Best Practices

### When Using This Skill

✅ **Do:**
- Consider context (who are the users? what's the task?)
- Apply relevant laws (not all 30 apply to every design)
- Prioritize CRITICAL issues
- Provide specific, actionable recommendations
- Explain the psychology/reasoning

❌ **Don't:**
- Apply all 30 laws to everything
- Treat laws as absolute rules (they're guidelines)
- Skip user testing (laws inform, testing validates)
- Overcomplicate simple issues

### Communication

**For designers:** Use principle names, focus on application

**For developers:** Connect to implementation, provide thresholds

**For stakeholders:** Link to business impact, use simple language

## Integration with Other Skills

This skill works well with:
- **Frontend-design** - Apply laws while building interfaces
- **Docx/PDF** - Create UX evaluation reports
- **Product self-knowledge** - Anthropic product UX evaluation

## License

This skill packages public domain knowledge (UX principles from research) with practical application guidance.

Laws of UX principles curated by Jon Yablonski (lawsofux.com) and original researchers.

---

**Ready to evaluate some designs?** Just ask Claude to review your interface against the Laws of UX!
