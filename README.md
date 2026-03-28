# Psycho Overlay

Python/GTK3 overlay that fills the screen with falling particles, flashing text, and (optionally) CC0 political-figure portraits.

## Run

```sh
poetry install
poetry run python psycho_overlay.py
```

Press `Esc` or `q` to exit.

## Custom images (requested CC0 political figures)

1. Create `assets/political_figures/` next to `psycho_overlay.py`.
2. Drop CC0/public-domain PNG/JPG/WEBP portraits there (Wikipedia often notes CC0/PD in the image license; verify before use).
3. Run again: `poetry run python psycho_overlay.py`.

Images are randomly scaled, spun, and dropped across the overlay alongside the particle spam.
# Hyprchan-Waitlist-Repo
