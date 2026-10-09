# MHGU Armor Skills Explained

Every armor skill in **Monster Hunter Generations Ultimate**: the game's own description, then a detailed
explanation of what the skill actually does — the exact amounts, what counts and what doesn't, the limits per
weapon, how it stacks with other skills (Felyne skills, Deviant souls), and what isn't confirmed yet.

Live: https://armoredraven17.github.io/mhgu-armor-skills-explained/

The in-game descriptions say *what* a skill touches. This page says *how*: for example, Artillery Expert is
x1.2 on Gunlance shells and x1.35 on Charge Blade phials, Felyne Bombardier multiplies on top, and the total is
capped at x1.3 for Gunlance but x1.4 for Charge Blade, so the Felyne skill is worth about +8% to one and +4% to
the other.

## Where the numbers come from

The numbers were read from the game's own code and data (a personally-owned copy), not taken from guides.
Community figures were only used as a check. Where something could not be confirmed, the skill says so under
"Not confirmed yet".

## How it fits the family

Static site served from `docs/`, no build step, deployed to GitHub Pages on push to `master` by
[.github/workflows/deploy-pages.yml](.github/workflows/deploy-pages.yml). It shares the look of the sibling
MHGU apps (the MHFU font and the menu textures) and links to them from the 🔗 button.

`docs/index.html` is generated (with the skill text embedded) from the research notes kept outside this
repository; edit those and regenerate rather than editing the page by hand.

See [NOTICE.md](NOTICE.md) for attributions. Code is MIT-licensed ([LICENSE](LICENSE)).
