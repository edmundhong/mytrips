# My Trips

A collection of trip journals published as small, self-contained web pages.

## URL structure

Every trip is stored by year and gets its own directory:

```
/YYYY/Trip-Name/
```

When deployed at `https://edmundhong.com/mytrips/`, that directory maps directly to:

```
https://edmundhong.com/mytrips/YYYY/Trip-Name/
```

For example, [`2026/Nanjing/`](2026/Nanjing/) is available at
`https://edmundhong.com/mytrips/2026/Nanjing/`.

## Adding a trip

1. Create `YYYY/Trip-Name/`.
2. Put an `index.html` in that directory.
3. Keep the page self-contained where practical, or store its assets beside it in `assets/`.
4. Add the trip to the appropriate year section in the root `index.html`.

Use URL-safe directory names (prefer `Pascal-Case` or hyphenated words; avoid spaces).
