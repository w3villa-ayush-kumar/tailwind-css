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

## 14. Dark Mode

- Tailwind supports dark mode automatically using the user's system preference.
- Dark mode styles use the `dark:` prefix, active when the OS/browser is set to dark theme.
- No configuration file is required when using Tailwind's default media-query–based dark mode.
- Example pattern: `bg-white dark:bg-gray-800`, `text-gray-800 dark:text-gray-100`.

## 15. Sizing

- Width utilities: `w-*`, fractional widths like `w-1/2`, and arbitrary values using bracket notation.
- Height utilities: `h-*`, `h-full`, `h-screen`, and arbitrary sizing.
- Min/max sizing: `min-w-*`, `min-h-*`, `max-w-*`, `max-h-*` for responsive constraints.
- Aspect ratio utilities: `aspect-square`, `aspect-video`, and custom ratios (`aspect-[4/3]`).

## 16. Interactivity

- Cursor utilities: `cursor-pointer`, `cursor-default`, `cursor-wait`, `cursor-not-allowed`.
- Text selection: `select-none`, `select-text`, `select-all`, `select-auto`.
- Pointer behavior: `pointer-events-none` disables interaction; `pointer-events-auto` restores it.
- Resize controls: `resize`, `resize-none`, `resize-x`, `resize-y`.
- Scroll behavior: `scroll-smooth` for smooth scrolling.
- Accent color: `accent-*` applies custom colors to radios and checkboxes.

## 17. Filters & Backdrop Filters

- Visual filters include `blur-*`, `brightness-*`, `contrast-*`, `grayscale`, `invert`, and `hue-rotate-*`.
- Backdrop filters apply effects behind an element, such as `backdrop-blur-*`, `backdrop-brightness-*`, and `backdrop-contrast-*`.
- Useful for effects like glassmorphism and softened visuals.

## 18. Advanced Typography

- Line height: `leading-*` controls vertical text spacing.
- Letter spacing: `tracking-*` adjusts character spacing.
- Text decoration: `underline`, `line-through`, with styles via `decoration-*`.
- Text transform: `uppercase`, `lowercase`, `capitalize`.
- Text overflow: `truncate`, `whitespace-nowrap`, and related utilities.

## 19. Advanced Flex & Grid

- Flex growth controlled with `flex-1` and sizing via `basis-*`.
- Flex wrapping: `flex-wrap`, `flex-nowrap`.
- Ordering controlled using `order-*` for responsive rearrangement.
- Grid auto-fit/fill patterns using arbitrary values (`grid-cols-[repeat(auto-fit,minmax(...))]`).
- Grid row behavior with `auto-rows-*`.
- Alignment helpers like `place-items-*` and `justify-items-*`.

## 20. Animations

- Built-in animations include `animate-spin`, `animate-ping`, `animate-pulse`, and `animate-bounce`.
- Custom keyframes require Tailwind's build pipeline and are not applicable in this setup.

## 21. Arbitrary Values

- Custom values can be applied directly using bracket notation.
- Supports custom sizes (`w-[300px]`, `p-[3rem]`).
- Supports custom colors (`bg-[#ff6b6b]`).
- Allows custom shadows (`shadow-[...]`) and transforms (`rotate-[8deg]`).
- Works without Tailwind config or build steps.
