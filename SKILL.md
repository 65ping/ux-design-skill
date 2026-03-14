---
name: UX Design Evaluation
description: Apply the 30 Laws of UX to product design, UI/UX evaluation, and design critique. Use this skill whenever the user mentions UX principles, design evaluation, usability heuristics, cognitive psychology in design, user interface critique, design feedback, UX best practices, or wants to understand why a design does or doesn't work. Also trigger when users ask questions like "is this good UX?", "how can I improve this design?", "what's wrong with this interface?", or reference specific laws like Fitts's Law, Miller's Law, Jakob's Law, etc.
---

# UX Design Evaluation

A comprehensive guide to the 30 established Laws of UX and how to apply them in product design and interface evaluation.

## What This Skill Covers

This skill helps you:
- **Evaluate designs** against proven UX principles
- **Identify issues** in interfaces and explain why they're problematic
- **Apply psychology** and cognitive science to design decisions
- **Communicate** UX concepts clearly to designers, developers, and stakeholders
- **Prioritize** which issues are critical vs minor
- **Design better** by understanding human perception, cognition, and behavior

## The Laws of UX

### Perception & Visual Design

#### 1. Aesthetic-Usability Effect
**Principle:** Users often perceive aesthetically pleasing design as design that's more usable.

**Application:**
- Invest in visual polish - it builds user trust and tolerance
- Beautiful designs create positive emotional responses
- Users forgive minor usability issues in attractive interfaces
- BUT: Don't let aesthetics mask real usability problems

**Evaluation Criteria:**
- Visual hierarchy: Clear size/weight differentiation
- Color harmony: 3-5 colors maximum, intentional relationships
- Typography: 2-3 font families, consistent scale (4-6 sizes)
- Polish: Consistent shadows, borders, hover states, spacing
- Balance: Intentional symmetry or deliberate asymmetry

**Common Issues:**
- CRITICAL: No visual hierarchy, all elements same weight
- CRITICAL: >3 font families, >8 font sizes
- MINOR: >6 colors without clear purpose
- MINOR: Inconsistent spacing, irregular gaps

#### 2. Von Restorff Effect (Isolation Effect)
**Principle:** When multiple similar objects are present, the one that differs is most likely to be remembered.

**Application:**
- Make primary CTAs visually distinct
- Use contrast to highlight important information
- Don't overuse - if everything is emphasized, nothing is
- Ensure distinctiveness has purpose

**Evaluation Criteria:**
- Primary CTA must stand out from secondary actions
- Important info uses visual distinction (color, size, weight)
- Maximum 2-3 distinct elements per screen
- Distinction matches importance hierarchy

**Common Issues:**
- CRITICAL: Primary CTA looks identical to secondary actions
- CRITICAL: No visual distinction for important information
- MINOR: Too many elements trying to stand out (3+)

#### 3. Selective Attention
**Principle:** Users focus attention only on a subset of stimuli, usually those relevant to their goals.

**Application:**
- Design clear visual hierarchy
- Don't bury critical information
- Use contrast, size, color, position to guide focus
- Remove or de-emphasize unnecessary elements

**Evaluation Criteria:**
- Clear focal point on each screen
- Important elements visually prominent
- Size/color/position create attention flow
- Critical info not lost in visual noise

**Common Issues:**
- CRITICAL: No clear focal point or hierarchy
- CRITICAL: Important information buried/same weight as everything else
- CRITICAL: Multiple elements competing equally for attention

### Information Architecture

#### 4. Chunking
**Principle:** Information is easier to process and remember when broken into small, meaningful groups.

**Application:**
- Group related information together
- Use 5-9 items per chunk maximum
- Create visual separation between chunks (whitespace, cards, sections)
- Progressive disclosure for complex information

**Evaluation Criteria:**
- Related content visually grouped (cards, sections, whitespace)
- Chunks limited to 5-9 items each
- Clear visual boundaries between groups
- Whitespace creates breathing room (minimum 24-32px gaps)

**Common Issues:**
- CRITICAL: Related information scattered, not grouped
- CRITICAL: No visual separation between content groups
- CRITICAL: Information chunks >9 items without sub-grouping
- CRITICAL: Insufficient whitespace (<16px gaps)

#### 5. Miller's Law
**Principle:** The average person can hold 7±2 items in working memory.

**Application:**
- Limit navigation menus to 5-9 items
- Break long lists into categories
- Don't require users to remember info across screens
- Use progressive disclosure for large datasets

**Evaluation Criteria:**
- Navigation menus ≤9 top-level items
- Lists >9 items are categorized or paginated
- No requirement to memorize info between screens
- Context always visible when needed

**Common Issues:**
- CRITICAL: Navigation with >9 items uncategorized
- CRITICAL: Lists with >9 items without grouping
- CRITICAL: Requiring users to remember codes/numbers across screens

#### 6. Serial Position Effect
**Principle:** Users best remember the first and last items in a series.

**Application:**
- Place important actions at beginning or end of lists
- Position key navigation at start or finish
- Don't bury critical options in the middle
- Order lists intentionally

**Evaluation Criteria:**
- Important items at start or end positions
- Critical actions not in middle of long lists
- Intentional ordering (not arbitrary)

**Common Issues:**
- CRITICAL: Critical actions buried in middle of 7+ item lists
- MINOR: Random ordering when priority-based would be better

### Gestalt Principles

#### 7. Law of Common Region
**Principle:** Elements sharing a clearly defined boundary are perceived as a group.

**Application:**
- Use cards, boxes, backgrounds to group related content
- Create visual containers for sections
- Borders, backgrounds establish clear boundaries

**Evaluation Criteria:**
- Related elements within visible boundaries
- Clear distinction between regions
- Appropriate nesting (not overly complex)

**Common Issues:**
- CRITICAL: Related elements without visual grouping
- CRITICAL: Ambiguous boundaries between content sections

#### 8. Law of Proximity
**Principle:** Objects close together are perceived as related.

**Application:**
- Place related items close together
- Use whitespace to create separation
- Keep labels near their inputs (4-8px gap)
- Group related actions together

**Evaluation Criteria:**
- Labels within 4-8px of inputs
- Related items closer than unrelated items
- Whitespace creates clear groupings
- Related actions adjacent

**Common Issues:**
- CRITICAL: Labels >16px from inputs
- CRITICAL: Related items spaced as far as unrelated items
- CRITICAL: Related actions separated by unrelated content

#### 9. Law of Similarity
**Principle:** Elements with similar visual characteristics are perceived as related.

**Application:**
- Style similar elements consistently
- Differentiate element types through styling
- Maintain pattern consistency
- Same function = same appearance

**Evaluation Criteria:**
- Buttons of same type styled consistently
- Similar functions have similar appearance
- Different functions have different styling
- Patterns maintained throughout interface

**Common Issues:**
- CRITICAL: Same-level buttons styled differently
- CRITICAL: Different elements styled identically
- MINOR: Breaking established patterns without reason

#### 10. Law of Prägnanz (Simplicity)
**Principle:** People interpret ambiguous or complex images in the simplest form possible.

**Application:**
- Design with simplicity in mind
- Use familiar, simple shapes
- Reduce visual complexity
- Avoid ambiguous elements

**Evaluation Criteria:**
- Simple, recognizable shapes
- No unnecessarily complex visuals
- Clear, unambiguous icons
- Minimal decoration

**Common Issues:**
- CRITICAL: Ambiguous icons or visuals
- MINOR: Overly complex elements that could be simplified

#### 11. Law of Uniform Connectedness
**Principle:** Visually connected elements are perceived as more related.

**Application:**
- Use lines, arrows, backgrounds to show relationships
- Connect related elements explicitly
- Don't create misleading connections

**Evaluation Criteria:**
- Related elements connected when appropriate
- Clear relationship indicators
- No false connections

**Common Issues:**
- CRITICAL: Visual connections between unrelated elements
- MINOR: Missing connections where they'd clarify relationships

### Decision Making & Choice

#### 12. Choice Overload (Paradox of Choice)
**Principle:** Too many options overwhelm users and impair decision-making.

**Application:**
- Minimize options when speed/quality matters
- Use progressive disclosure
- Provide smart defaults or recommendations
- Categorize when many options necessary

**Evaluation Criteria:**
- ≤7 options without categorization
- Progressive disclosure for complex tasks
- Smart defaults provided
- Recommendations when helpful

**Common Issues:**
- CRITICAL: >7 uncategorized options
- CRITICAL: No defaults or recommendations when needed
- CRITICAL: All options shown at once in complex flows

#### 13. Hick's Law
**Principle:** Decision time increases with number and complexity of choices.

**Application:**
- Reduce choices for faster decisions
- Break complex decisions into steps
- Highlight recommended options
- Use progressive disclosure

**Evaluation Criteria:**
- Choices minimized for time-sensitive tasks
- Complex decisions broken into steps
- Recommended options highlighted
- Clear differentiation between options

**Common Issues:**
- CRITICAL: Too many equal-priority options
- CRITICAL: Options difficult to compare
- MINOR: No recommended/default selection

#### 14. Cognitive Bias
**Principle:** Systematic errors in thinking affect judgment and decisions.

**Application:**
- Be aware of common biases (confirmation, anchoring, availability)
- Use neutral language
- Present balanced information
- Test with diverse users

**Evaluation Criteria:**
- Neutral framing, not leading
- Both pros and cons presented
- No manipulation through bias

**Common Issues:**
- MINOR: Leading language manipulating choices
- MINOR: Only positive aspects shown

### Interaction Design

#### 15. Fitts's Law
**Principle:** Time to acquire a target = function of distance to and size of target.

**Application:**
- Touch targets ≥44x44px (mobile/touch)
- Mouse targets ≥32x32px minimum
- Place frequent actions close together
- Put important actions in easy-to-reach locations
- Use screen edges/corners (infinite targets)

**Evaluation Criteria:**
- Interactive elements ≥44x44px (touch) or ≥32x32px (mouse)
- Related actions close together (<200px)
- Primary CTA in optimal position
- Clickable area matches visual size

**Common Issues:**
- CRITICAL: Buttons <44x44px on touch interfaces
- CRITICAL: Related actions >200px apart
- MINOR: CTA not in expected/optimal location

#### 16. Doherty Threshold
**Principle:** Productivity soars when system response <400ms.

**Application:**
- Keep response times <400ms
- Use perceived performance (skeleton screens, optimistic UI)
- Provide immediate feedback
- Show loading indicators for >400ms

**Evaluation Criteria:**
- Loading states for async operations
- Immediate feedback on all actions
- Skeleton screens for slow content
- Progress indicators when needed

**Common Issues:**
- CRITICAL: No loading indicators
- CRITICAL: No feedback on user actions
- MINOR: Blank screens vs skeleton loaders

#### 17. Jakob's Law
**Principle:** Users prefer sites to work like all the other sites they know.

**Application:**
- Follow platform conventions
- Only innovate when providing clear value
- Match user expectations
- Test deviations carefully

**Evaluation Criteria:**
- Standard patterns for core interactions
- Innovation justified by value
- Platform conventions followed
- Expected locations for common elements

**Common Issues:**
- CRITICAL: Core interactions deviate from conventions
- CRITICAL: Navigation doesn't follow platform norms
- MINOR: Custom icons don't match universal meanings

#### 18. Postel's Law (Robustness Principle)
**Principle:** Be liberal in what you accept, conservative in what you send.

**Application:**
- Accept varied input formats
- Auto-format when possible
- Provide clear, consistent output
- Flexible validation

**Evaluation Criteria:**
- Flexible input validation (phone, credit card, dates)
- Auto-formatting on blur
- Consistent output format
- Error recovery, not just rejection

**Common Issues:**
- CRITICAL: Rejecting valid inputs due to formatting
- CRITICAL: No attempt to parse/correct user input
- MINOR: Inconsistent output formats

### Cognitive Load

#### 19. Cognitive Load
**Principle:** The mental effort required to use an interface.

**Application:**
- Minimize unnecessary elements
- Use clear, simple language
- Progressive disclosure
- Avoid simultaneous complex tasks

**Evaluation Criteria:**
- Element density <5 per 100x100px
- Simple, clear language
- No jargon without reason
- Single-focus tasks

**Common Issues:**
- CRITICAL: High element density, visual clutter
- CRITICAL: Jargon, complex terminology
- CRITICAL: Multiple competing tasks
- MINOR: Decorative elements adding noise

#### 20. Working Memory
**Principle:** Temporary system for holding information needed for tasks.

**Application:**
- Display relevant info in context
- Don't hide necessary context
- No cross-screen memory requirements
- Keep related info visible

**Evaluation Criteria:**
- Context always visible
- No hidden essential information
- Data needed for task is displayed
- No memorization between screens

**Common Issues:**
- CRITICAL: Hiding necessary context (tooltips for essential info)
- CRITICAL: Requiring memory across screens
- CRITICAL: System state not visible

#### 21. Mental Model
**Principle:** Internal representation of how a system works.

**Application:**
- Align interface with user expectations
- Use familiar metaphors
- Clear feedback when behavior differs
- Reduce mismatch between user/system model

**Evaluation Criteria:**
- Behavior matches expectations
- Clear feedback for unexpected results
- Familiar metaphors used
- Consistent mental model

**Common Issues:**
- CRITICAL: Actions producing unexpected results
- CRITICAL: System feedback contradicting expectations
- MINOR: Unfamiliar metaphors without explanation

### Motivation & Completion

#### 22. Flow
**Principle:** Complete immersion in an activity.

**Application:**
- Remove interruptions
- Maintain clear goals
- Provide immediate feedback
- Balance challenge and skill

**Evaluation Criteria:**
- Minimal interruptions (modals, popups)
- Clear next steps
- Smooth task progression
- No unnecessary friction

**Common Issues:**
- CRITICAL: Unnecessary modals/interruptions
- CRITICAL: Unclear what to do next
- MINOR: Friction points breaking momentum

#### 23. Goal-Gradient Effect
**Principle:** Motivation increases near goal completion.

**Application:**
- Show progress clearly
- Provide completion indicators
- Give users head start (10% vs 0%)
- Celebrate completion

**Evaluation Criteria:**
- Progress indicators in multi-step flows
- Clear completion feedback
- Visual progress representation
- Milestone acknowledgment

**Common Issues:**
- CRITICAL: Multi-step process without progress indication
- MINOR: No completion celebration
- MINOR: Missing artificial progress boost

#### 24. Peak-End Rule
**Principle:** Experiences judged by peak moment and ending.

**Application:**
- Design memorable peak moments
- End on positive note
- Minimize pain at end
- Special attention to last impression

**Evaluation Criteria:**
- Memorable highlights in journey
- Positive ending experience
- No frustration at conclusion
- Celebration of completion

**Common Issues:**
- CRITICAL: Errors/friction at end of flow
- MINOR: No memorable moments
- MINOR: Flat ending without acknowledgment

#### 25. Zeigarnik Effect
**Principle:** Incomplete tasks better remembered than completed.

**Application:**
- Show incomplete tasks/profiles
- Save progress, enable resume
- Use for motivation (not manipulation)
- Progress indicators

**Evaluation Criteria:**
- Save states in long processes
- Resume capability
- Incomplete indicators visible
- No lost progress

**Common Issues:**
- CRITICAL: No save/resume in multi-step processes
- MINOR: No incomplete task indicators

### Other Principles

#### 26. Occam's Razor
**Principle:** Simplest solution is usually best.

**Application:**
- Remove unnecessary features
- Keep interfaces simple
- Question every element
- Simple solutions over complex

**Evaluation Criteria:**
- No unnecessary features
- Minimal complexity
- Each element justified
- Simple solutions preferred

**Common Issues:**
- CRITICAL: Feature bloat, too many competing features
- MINOR: Complex solutions where simple works
- MINOR: Unjustified elements

#### 27. Paradox of the Active User
**Principle:** Users don't read manuals, they jump right in.

**Application:**
- Design for immediate use
- Progressive disclosure, not tutorials
- Contextual help, not manuals
- Discoverable features

**Evaluation Criteria:**
- No forced tutorials
- Features discoverable without instructions
- Clear visual affordances
- Just-in-time guidance

**Common Issues:**
- CRITICAL: Long mandatory tutorials
- CRITICAL: Essential features requiring instructions
- CRITICAL: No visual affordances

#### 28. Pareto Principle (80/20 Rule)
**Principle:** 80% of effects from 20% of causes.

**Application:**
- Focus on most-used features
- Optimize common tasks
- Don't let edge cases drive design
- Prioritize by usage

**Evaluation Criteria:**
- Common actions prominently placed
- Primary features emphasized
- Edge cases don't dominate
- Usage-based prioritization

**Common Issues:**
- CRITICAL: Common actions not prominent
- MINOR: All features given equal weight
- MINOR: Edge cases driving design

#### 29. Parkinson's Law
**Principle:** Work expands to fill available time.

**Application:**
- Set time limits when appropriate
- Create urgency for time-sensitive tasks
- Don't let tasks drag indefinitely
- Clear deadlines/expectations

**Evaluation Criteria:**
- Time constraints for time-sensitive tasks
- Urgency indicators when needed
- Clear completion expectations

**Common Issues:**
- MINOR: No time expectations for tasks
- MINOR: Missing urgency for time-sensitive actions

#### 30. Tesler's Law (Conservation of Complexity)
**Principle:** Every system has irreducible complexity.

**Application:**
- Identify inherent complexity
- Decide: UI complexity or system complexity
- Don't oversimplify to point of confusion
- Progressive disclosure for complex features

**Evaluation Criteria:**
- Essential complexity preserved
- Appropriate UI vs system complexity balance
- Not oversimplified
- Progressive disclosure available

**Common Issues:**
- CRITICAL: Hiding essential complexity, making tasks impossible
- CRITICAL: Oversimplification causing confusion
- MINOR: Technical complexity exposed unnecessarily

---

## How to Use This Skill

### For Design Evaluation

When evaluating a design:

1. **Identify the context** - What type of interface? (Dashboard, form, landing page, mobile app)
2. **Consider relevant laws** - Not all 30 apply to every design
3. **Look for violations** - Check against evaluation criteria
4. **Classify severity**:
   - CRITICAL: Fundamentally breaks usability, accessibility, or user trust
   - MINOR: Polish issues, optimization opportunities
5. **Explain why** - Connect issue to psychological principle
6. **Suggest fixes** - Concrete, actionable improvements

### For Design Decisions

When making design choices:

1. **Consider the user's mental model**
2. **Apply relevant laws proactively**
3. **Balance competing principles** (simplicity vs functionality)
4. **Test assumptions** - Laws guide but don't replace user testing
5. **Iterate** based on real user feedback

### Communication Framework

When discussing UX with others:

**For designers:**
- Use principle names, they're familiar
- Focus on application, not theory
- Show examples, not just rules

**For developers:**
- Connect to implementation (button sizes, response times)
- Explain why, not just what
- Provide specific thresholds/numbers

**For stakeholders:**
- Connect to business impact (conversion, satisfaction, support costs)
- Use simple language
- Show before/after comparisons

---

## Evaluation Priority Matrix

**Always address CRITICAL issues first:**
- Touch targets <44px
- >7 choices without categorization/defaults
- No visual hierarchy
- Labels far from inputs
- Navigation >9 items uncategorized
- Hidden essential information
- Actions producing unexpected results
- Oversimplified to point of unusability

**Then address MINOR issues:**
- Inconsistent spacing
- Too many colors/fonts
- Missing smart defaults
- Suboptimal CTA placement
- No progress indicators
- Overly decorative elements

---

## Context-Specific Applications

### Mobile vs Desktop
- **Mobile**: Fitts's Law critical (44px minimum), thumb zones important
- **Desktop**: Can use smaller targets (32px), hover states available

### Forms
- Priority laws: Proximity (labels), Chunking (grouping), Miller's Law (field count), Postel's Law (input validation)

### Navigation
- Priority laws: Miller's Law (item count), Jakob's Law (conventions), Serial Position (important items), Choice Overload

### Dashboards
- Priority laws: Selective Attention (hierarchy), Chunking (grouping), Cognitive Load (density), Common Region (cards)

### E-commerce
- Priority laws: Choice Overload, Hick's Law, Von Restorff (CTA), Peak-End (checkout), Flow

### FigJam/Boards
- Relevant: Chunking, Miller's Law, Proximity, Hierarchy, Common Region
- Less relevant: Fitts's Law (no buttons), Doherty (no loading), Jakob's Law (no UI conventions)

---

## Remember

- **Laws are guidelines**, not absolute rules
- **Test with real users** - laws inform, testing validates
- **Context matters** - consider your specific users and use case
- **Balance is key** - sometimes laws conflict, use judgment
- **Simplicity wins** - when in doubt, simpler is usually better

These laws are grounded in psychology and research, but human behavior is complex. Use them to make informed decisions, then validate with real users.
