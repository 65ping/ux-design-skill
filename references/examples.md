# Laws of UX Application Examples

Real-world examples showing how to apply the 30 Laws of UX.

## Example 1: E-commerce Product Page Evaluation

**Context:** Mobile product page for online clothing store

### Issues Found

#### CRITICAL
1. **Fitts's Law Violation**
   - Buy button: 32x28px (should be ≥44x44px)
   - Add to wishlist icon: 24x24px
   - **Fix:** Increase to 44x44px minimum

2. **Choice Overload**
   - 8 color options + 5 size options shown simultaneously
   - No smart defaults
   - **Fix:** Show color first, then size after selection. Pre-select most popular size.

3. **Cognitive Load**
   - 47 elements visible (density too high)
   - Product details, recommendations, reviews all competing
   - **Fix:** Progressive disclosure - fold "You may also like" until after selection

4. **Proximity Violation**
   - "Free shipping" label 40px from product
   - Price 30px from product name
   - **Fix:** Group price + shipping + product name together (8-12px gaps)

#### MINOR
1. **Aesthetic-Usability**
   - Using 7 font sizes (headline, price, old price, description, size label, legal, footer)
   - **Fix:** Consolidate to 4-5 sizes using type scale

2. **Von Restorff**
   - "Add to Cart" button same visual weight as "Add to Wishlist"
   - **Fix:** Make primary CTA larger, different color, more prominent

**Severity:** High - Core purchasing flow impacted
**Priority:** Fix Critical issues before launch

---

## Example 2: SaaS Dashboard Evaluation

**Context:** Analytics dashboard for marketing team

### Issues Found

#### CRITICAL
1. **Selective Attention Failure**
   - No clear visual hierarchy
   - All metrics same size/weight
   - Important alerts buried in noise
   - **Fix:** Size critical metrics larger (24-32pt), use color for status, create clear focal points

2. **Hick's Law / Choice Overload**
   - 14 equal-priority action buttons in header
   - User paralyzed deciding what to do
   - **Fix:** 3 primary actions visible, rest in "More actions" menu

3. **Jakob's Law Violation**
   - Search bar in bottom-right corner (unconventional)
   - Users looking top-right (expected location)
   - **Fix:** Move search to top-right

4. **Common Region Missing**
   - Related metrics scattered across screen
   - No visual grouping
   - **Fix:** Card-based layout grouping metrics by category

5. **Serial Position**
   - "Logout" button in middle of 12-item nav menu
   - **Fix:** Move to bottom of menu (expected location)

#### MINOR
1. **Aesthetic-Usability**
   - Spacing values: 12, 16, 18, 22, 24, 28, 32px (too many)
   - **Fix:** Use spacing scale: 8, 16, 24, 32px only

2. **Occam's Razor**
   - Settings cog, preferences cog, options menu all present
   - **Fix:** Consolidate into single "Settings" menu

3. **Pareto Principle**
   - Rarely-used "Export to CSV" same size as "View Details"
   - **Fix:** Make secondary actions smaller, tertiary actions in menu

**Severity:** High - Daily use, impacts productivity
**Priority:** Address before rolling out to wider team

---

## Example 3: Mobile App Onboarding

**Context:** First-time user experience for fitness tracking app

### Issues Found

#### CRITICAL
1. **Paradox of the Active User**
   - 7-screen tutorial before letting user try app
   - Forced progression through all screens
   - **Fix:** Let users dive in, offer contextual tips as they explore

2. **Miller's Law**
   - Tutorial explaining 12 features at once
   - **Fix:** Show 3-5 core features, let users discover rest

3. **Flow Interruption**
   - Permission modals for notifications, location, health data all at once
   - **Fix:** Request permissions contextually when features are first used

#### MINOR
1. **Goal-Gradient**
   - No progress indicator in tutorial
   - **Fix:** Add "2 of 4" progress dots

2. **Peak-End Rule**
   - Tutorial ends with privacy policy screen (negative)
   - **Fix:** End with encouraging message and first workout suggestion

**Application:** Onboarding is first impression - nail the peak and ending

---

## Example 4: Form Design - Sign Up Flow

**Context:** Multi-step account creation

### CRITICAL Issues

1. **Proximity**
```
❌ BAD:
Name [label]
[24px gap]
[input field]

✓ GOOD:
Name [label]
[4px gap]
[input field]
```

2. **Miller's Law**
```
❌ BAD:
All 11 fields on one screen

✓ GOOD:
Step 1: Name, Email, Password (3 fields)
Step 2: Company, Role, Team Size (3 fields)
Step 3: Preferences (3 fields)
```

3. **Chunking**
```
❌ BAD:
[First Name]
[Last Name]
[Email]
[Company]
[Title]
[Phone]

✓ GOOD:
Personal Information
├─ [First Name]
├─ [Last Name]
└─ [Email]

Work Information
├─ [Company]
├─ [Title]
└─ [Phone]
```

4. **Postel's Law**
```
❌ BAD:
Phone: (555) 123-4567 [exact format required]
Error: "Invalid format"

✓ GOOD:
Phone: 5551234567 [accepts any format]
Auto-formats to: (555) 123-4567
```

5. **Goal-Gradient**
```
❌ BAD:
[No progress indicator]

✓ GOOD:
Step 2 of 3 [====---]
[Progress bar showing 66% complete]
```

---

## Example 5: Navigation Menu

**Context:** Main navigation for content website

### Evaluation

**Current State:**
- 16 items in horizontal nav
- No categories
- All equal weight
- "About" in position #8

**Laws Applied:**

1. **Miller's Law** (≤9 items)
```
❌ CURRENT: 16 items
✓ FIX: 6 top-level categories
```

2. **Serial Position** (Important first/last)
```
❌ CURRENT:
Home | Products | Services | Resources | 
Tools | Blog | Events | About | Careers | 
Contact | Support | Docs | API | Partners | 
Press | Legal

✓ FIX:
Products | Solutions | Resources | 
Company | Blog | Contact
```

3. **Chunking** (Group related)
```
✓ GROUPED:
Products (dropdown)
├─ Product A
├─ Product B
└─ Product C

Resources (dropdown)
├─ Blog
├─ Docs
├─ API
└─ Support
```

4. **Jakob's Law** (Expected locations)
```
✓ Standard placement:
[Logo] [Nav items...] [Search] [Login] [CTA]
```

---

## Example 6: Data Table

**Context:** Admin panel showing user list

### Issues & Fixes

#### CRITICAL
1. **Selective Attention**
```
❌ All columns equal width
✓ Prioritize: Name (30%), Email (25%), 
   Status (15%), Actions (30%)
```

2. **Chunking**
```
❌ 200 rows, no pagination
✓ 25 rows per page with pagination
```

3. **Von Restorff**
```
❌ All statuses same appearance
✓ Active: green, Inactive: gray, 
   Suspended: red
```

#### MINOR
1. **Fitts's Law**
```
❌ Action icons: 16x16px
✓ Action buttons: 32x32px
```

2. **Aesthetic-Usability**
```
❌ Dense, cramped rows
✓ Comfortable row height (48px) 
   with hover states
```

---

## Example 7: Modal Dialog

**Context:** Confirmation dialog for destructive action

### Best Practices Applied

**Flow** - Only show for irreversible actions
```
✓ Delete account → Modal
✓ Save draft → No modal (reversible)
```

**Cognitive Load** - Clear, simple language
```
❌ "Are you sure you want to proceed with the 
    deletion of this resource?"
✓ "Delete this project? This can't be undone."
```

**Hick's Law** - Limit choices
```
✓ Two options: "Cancel" | "Delete"
❌ Three+: "Cancel" | "Delete" | "Save First"
```

**Von Restorff** - Distinguish dangerous action
```
✓ "Cancel" (secondary) | "Delete" (red, prominent)
```

**Fitts's Law** - Button sizing
```
✓ Both buttons ≥44x44px
✓ Safe action (Cancel) closer to cursor entry point
```

---

## Pattern Library

### Button Groups
```
Primary (large, distinct color)
Secondary (medium, outlined)
Tertiary (small, text only)

Laws: Von Restorff, Similarity, Fitts's Law
```

### Form Fields
```
[Label] ← 4-8px gap → [Input]
Related fields grouped visually

Laws: Proximity, Common Region, Chunking
```

### Card Layouts
```
┌─────────────┐
│ Heading     │ ← Clear hierarchy
│ ─────────── │
│ Content     │ ← Grouped content
│             │
│ [Action]    │ ← CTA bottom-right
└─────────────┘

Laws: Common Region, Selective Attention, Fitts's Law
```

### Progress Indicators
```
Step 1 → Step 2 → Step 3
[====--------]
67% complete

Laws: Goal-Gradient, Flow, Serial Position
```

---

## Quick Fixes by Severity

### CRITICAL (Fix Before Launch)
- [ ] Touch targets <44px → Resize to 44x44px
- [ ] >7 options → Add categories or defaults
- [ ] No hierarchy → Add size/weight/color variation
- [ ] Labels far from inputs → Reduce to 4-8px gap
- [ ] >9 nav items → Categorize or reduce

### MINOR (Polish Before v2)
- [ ] >6 colors → Reduce to 3-5
- [ ] Inconsistent spacing → Use 8/16/24/32px scale
- [ ] Missing progress → Add indicators
- [ ] No defaults → Add smart defaults
- [ ] CTA not distinct → Make visually prominent

---

These examples show the laws in action. Use them as templates for evaluating your own designs.
