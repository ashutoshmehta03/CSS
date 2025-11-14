<!-- CSS Priority (Highest → Lowest)

1. Inline CSS
2. Internal CSS
3. External CSS

Inline always wins
Internal overrides external
External has lowest priority

Example Priority Explanation

If all three styles target the same element: -->

<!--1.  Inline -->

<h1 style="color: blue;">Hello</h1>

<!-- 2. Internal: -->

<style>
  h1 { color: green; }
</style>

<!-- 3. External: -->

h1 { color: red; }

Final color will be BLUE because Inline > Internal > External.
