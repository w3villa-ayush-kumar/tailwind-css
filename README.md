# 📘 Tailwind CSS — Learning Documentation

A concise, utility‑focused summary of all Tailwind concepts learned.

---

## 1. Typography

- `text-*` controls font size.
- `font-*` controls weight.
- `text-*` colors text.
- `uppercase` transforms text.
- `leading-*` adjusts line height.
- `max-w-*` limits readable width.

---

## 2. Spacing

- `m-*` margin, `p-*` padding.
- Direction: `mx-*`, `my-*`, `mt-*`, `mb-*`.
- Gap between children: `space-x-*`, `space-y-*`.

---

## 3. Flexbox

- `flex` enables flexbox.
- Direction: `flex-row`, `flex-col`, responsive variants.
- Alignment: `justify-*` (main axis), `items-*` (cross axis).
- `gap-*` adds spacing.
- `flex-1` allows expansion.

---

## 4. Layout

- Display: `block`, `inline-block`, `flex`, `grid`, `hidden`.
- Width: `w-*`, `w-full`, fractional widths (`w-1/2`, `w-1/3`).
- Height: `h-*`, `h-auto`, `h-screen`.
- Max/min sizing: `max-w-*`, `min-h-*`.

---

## 5. Grid

- `grid` enables CSS Grid layout.
- `grid-cols-*` defines the number of columns, with responsive variants like `md:grid-cols-*`.
- `gap-*` controls spacing between grid items.
- Elements can span using `col-span-*` and `row-span-*`.

## 6. Colors

- Text color uses `text-*` utilities.
- Background color uses `bg-*` utilities.
- Shades follow Tailwind’s numeric scale (50–900).
- Opacity can be applied using slash syntax: `bg-color/opacity` (e.g., `bg-red-500/60`).

## 7. Borders & Radius

- Border width: `border`, `border-2`, `border-4`, `border-8`.
- Border color: `border-*` using Tailwind’s color scale.
- Side-specific borders: `border-t`, `border-b`, `border-l`, `border-r`.
- Radius utilities: `rounded`, `rounded-md`, `rounded-lg`, `rounded-full`.

## 8. Shadows

- Shadow utilities provide different elevation levels: `shadow-sm`, `shadow`, `shadow-md`, `shadow-lg`, `shadow-xl`, `shadow-2xl`.
- `shadow-none` removes shadows.
- Colored shadows are supported using `shadow-color/opacity` syntax.

## 9. Backgrounds

- Solid backgrounds use `bg-*` utilities.
- Opacity uses slash syntax (e.g., `bg-blue-500/50`).
- Gradients use `bg-gradient-to-*` with color stops via `from-*`, `via-*`, `to-*`.
- Background images use `bg-[url('...')]`.
- Size and position utilities include `bg-cover`, `bg-contain`, and `bg-center`.

## 10. Positioning

- Position types: `static`, `relative`, `absolute`, `fixed`, `sticky`.
- Offsets use `top-*`, `right-*`, `bottom-*`, `left-*` or combined utilities like `inset-0`.
- Sticky behavior combines `sticky` with an offset (`top-0`).
- Z-index controlled using `z-*` values.

## 11. Transitions & Transforms

- Transitions: `transition`, `transition-colors`, `transition-opacity`, `transition-all` with timing utilities (`duration-*`, `ease-*`).
- Transforms require `transform` and support movement (`translate-x-*`, `translate-y-*`), scaling (`scale-*`), rotation (`rotate-*`), and skewing (`skew-*`).
- Often combined with hover or focus states.

## 12. Responsive Design

- Tailwind uses mobile-first breakpoints: `sm`, `md`, `lg`, `xl`, `2xl`.
- Prefix utilities with breakpoints to change styles at specific widths (e.g., `md:text-lg`).
- Enables full control of layout, spacing, typography, and visibility across screen sizes.

## 13. State Variants

- Apply styles conditionally using prefixes like `hover:`, `focus:`, `active:`, and `disabled:`.
- Parent-based styling uses `group` with `group-hover:*` on children.
- Sibling-based styling uses `peer` with variants like `peer-checked:*`.
- Enables interactive styling without custom CSS or JavaScript.

More sections will be added as Tailwind learning continues.
