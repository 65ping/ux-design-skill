# Quick Reference

Use this for quick lookups when you need specific information about a law.

## Quick Severity Guide

### CRITICAL Issues (Fix Immediately)

**Interaction:**
- Touch targets <44x44px (mobile) or <32x32px (desktop)
- Related actions >200px apart
- No loading states/feedback

**Information:**
- >7 options without categorization
- >9 navigation items uncategorized
- No visual hierarchy

**Layout:**
- Labels >16px from inputs
- Related items not grouped
- Essential info hidden

**Behavior:**
- Unexpected action results
- Required cross-screen memorization
- Oversimplified to unusable

### MINOR Issues (Polish/Optimize)

- >6 colors used
- >3 font families
- Inconsistent spacing patterns
- Missing smart defaults
- No progress indicators
- CTA not optimally placed

---

## By Design Element

### Buttons
- **Fitts's Law**: ≥44x44px touch, ≥32x32px mouse
- **Von Restorff**: Primary distinct from secondary
- **Law of Similarity**: Same level = same style
- **Jakob's Law**: Standard button patterns

### Forms
- **Proximity**: Labels 4-8px from inputs
- **Chunking**: Group related fields
- **Miller's Law**: ≤9 fields per section
- **Postel's Law**: Flexible input validation
- **Cognitive Load**: Simple, clear labels

### Navigation
- **Miller's Law**: ≤9 top-level items
- **Jakob's Law**: Expected locations (top/left)
- **Serial Position**: Important items first/last
- **Common Region**: Clear menu boundaries

### Lists
- **Miller's Law**: ≤9 items uncategorized
- **Chunking**: Group every 5-9 items
- **Serial Position**: Important at start/end
- **Choice Overload**: Limit options

### Text Content
- **Chunking**: 5-9 items per section
- **Cognitive Load**: Simple language
- **Visual Hierarchy**: Size/weight variation
- **Whitespace**: ≥24px between sections

### CTAs (Call to Action)
- **Von Restorff**: Visually distinct
- **Fitts's Law**: Large, accessible
- **Peak-End**: Positive ending
- **Goal-Gradient**: Show progress to CTA

---

## By Task Type

### Form Completion
1. **Proximity** - Labels near inputs
2. **Chunking** - Group related fields
3. **Miller's Law** - ≤9 fields per step
4. **Postel's Law** - Flexible validation
5. **Goal-Gradient** - Show progress

### Navigation/Browsing
1. **Jakob's Law** - Follow conventions
2. **Miller's Law** - ≤9 menu items
3. **Serial Position** - Important first/last
4. **Selective Attention** - Clear hierarchy
5. **Choice Overload** - Limit options

### Decision Making
1. **Hick's Law** - Minimize choices
2. **Choice Overload** - ≤7 options
3. **Von Restorff** - Highlight recommended
4. **Cognitive Bias** - Neutral framing
5. **Aesthetic-Usability** - Build trust

### Content Consumption
1. **Chunking** - Break into sections
2. **Visual Hierarchy** - Size/weight
3. **Selective Attention** - Guide focus
4. **Cognitive Load** - Simple language
5. **Whitespace** - Breathing room

### Task Completion
1. **Flow** - Minimize interruptions
2. **Goal-Gradient** - Show progress
3. **Peak-End** - Positive conclusion
4. **Doherty** - Fast responses
5. **Zeigarnik** - Save progress

---

## By Industry/Context

### E-commerce
**Critical:** Choice Overload, Hick's Law, Von Restorff (CTA), Peak-End (checkout), Postel's Law (forms)

### SaaS Dashboards
**Critical:** Selective Attention, Chunking, Common Region, Cognitive Load, Miller's Law

### Mobile Apps
**Critical:** Fitts's Law (44px), Jakob's Law (platform), Flow, Doherty, Working Memory

### Enterprise Software
**Critical:** Jakob's Law, Cognitive Load, Mental Model, Chunking, Progressive Disclosure

### Content Sites
**Critical:** Visual Hierarchy, Selective Attention, Chunking, Aesthetic-Usability, Whitespace

### Forms/Surveys
**Critical:** Proximity, Chunking, Miller's Law, Goal-Gradient, Postel's Law

---

## Measurement Thresholds

### Size
- Touch targets: ≥44x44px
- Mouse targets: ≥32x32px
- Clickable area = visual area

### Spacing
- Label to input: 4-8px
- Between related items: 8-16px
- Between sections: 24-32px
- Inconsistent variance: <20% deviation

### Quantity
- Menu items: ≤9
- Options without categorization: ≤7
- Items per chunk: 5-9
- Font sizes: 4-6
- Font families: 2-3
- Colors: 3-5 primary

### Time
- Response time: <400ms
- Loading feedback: Show at >400ms
- Provide immediate feedback: <100ms

### Distance
- Related actions: <200px apart
- CTA from content: Visible without scroll (mobile)

---

## Common Conflicts & How to Resolve

### Simplicity vs Functionality
**Conflict:** Occam's Razor vs user needs
**Resolution:** Progressive disclosure - simple by default, complexity available

### Aesthetics vs Usability
**Conflict:** Aesthetic-Usability vs clear function
**Resolution:** Polish enhances usability, doesn't replace it. Never sacrifice critical usability.

### Familiarity vs Innovation
**Conflict:** Jakob's Law vs differentiation
**Resolution:** Innovate only when providing clear value. Test thoroughly.

### Minimal Choices vs Complete Options
**Conflict:** Choice Overload vs user power
**Resolution:** Smart defaults + "Show more" option. Guide but don't limit.

### Speed vs Comprehension
**Conflict:** Doherty vs Cognitive Load
**Resolution:** Fast + clear feedback. Never sacrifice clarity for speed.

---

## Platform-Specific Notes

### iOS
- 44x44pt minimum touch targets
- Bottom nav (thumb zone)
- Swipe gestures standard
- Back button top-left

### Android
- 48x48dp minimum touch targets
- Material Design patterns
- FAB for primary action
- Back button device-level

### Web Desktop
- 32x32px minimum targets
- Hover states available
- Top nav standard
- Right-click context menus

### Web Mobile
- 44x44px minimum targets
- No hover states
- Bottom nav (thumb zone)
- Minimize typing

---

## Quick Diagnostic Questions

**No clear focal point?** → Selective Attention, Visual Hierarchy
**Too many options?** → Choice Overload, Hick's Law, Miller's Law
**Things feel scattered?** → Chunking, Proximity, Common Region
**Buttons too small?** → Fitts's Law
**Actions feel unclear?** → Affordances, Mental Model, Jakob's Law
**Form feels long?** → Miller's Law, Chunking, Goal-Gradient
**Messy appearance?** → Aesthetic-Usability, Cognitive Load
**Similar things look different?** → Law of Similarity
**Can't find important stuff?** → Selective Attention, Serial Position
**Unintuitive behavior?** → Mental Model, Jakob's Law

---

## One-Sentence Summaries

1. **Aesthetic-Usability**: Pretty = trustworthy
2. **Von Restorff**: Different = memorable
3. **Selective Attention**: Hierarchy guides eyes
4. **Chunking**: Group info in 5-9 chunks
5. **Miller's Law**: 7±2 items max
6. **Serial Position**: Remember first & last
7. **Common Region**: Boxes group things
8. **Proximity**: Close = related
9. **Similarity**: Same look = same function
10. **Prägnanz**: Simple shapes work best
11. **Uniform Connectedness**: Lines show relationships
12. **Choice Overload**: Too many options paralyze
13. **Hick's Law**: More choices = slower decisions
14. **Cognitive Bias**: Framing affects choices
15. **Fitts's Law**: Bigger & closer = easier
16. **Doherty**: <400ms = productive flow
17. **Jakob's Law**: Match expectations
18. **Postel's Law**: Accept flexible, output consistent
19. **Cognitive Load**: Less mental effort = better
20. **Working Memory**: Show, don't hide
21. **Mental Model**: Match user expectations
22. **Flow**: Remove friction
23. **Goal-Gradient**: Progress motivates
24. **Peak-End**: Peaks & endings remembered
25. **Zeigarnik**: Incomplete = remembered
26. **Occam's Razor**: Simplest = best
27. **Active User**: No one reads manuals
28. **Pareto**: 80% from 20%
29. **Parkinson's**: Tasks expand to time available
30. **Tesler's**: Complexity is constant

---

Use SKILL.md for detailed explanations and application guidance.
Use this reference for quick lookups and specific thresholds.
