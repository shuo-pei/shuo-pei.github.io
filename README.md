# Shuo Pei — academic homepage

This is a standalone English-language academic homepage for Shuo Pei. It presents his research, selected peer-reviewed publications, and education on one continuous page, with links to email, Google Scholar, and GitHub. The upper navigation links to sections on that page.

## Files

- `index.html` contains the page, icons, and interactive canvas scene. There is no build step or external JavaScript library.
- `style.css` contains the unified dark editorial layout and an open full-width scene.
- `portrait.jpg` contains the profile photograph at its original portrait aspect ratio.
- `.nojekyll` lets GitHub Pages serve the static page without Jekyll processing.

The compact city-road scene includes a light-colored ego vehicle matching the simplified style of four surrounding traffic vehicles, buildings, roadside trees, and scattered points that gather into a path around a vehicle ahead. The bottom fades into the page background. It is a **conceptual visualization**, not a model output or research result. The scene still supports pointer and keyboard camera controls. Review the public contact details and portrait before publishing.

The design draws on the clear research and publication hierarchy of [Cyrus Huang's homepage](https://cyrus.bot/) and the direct project navigation of [Jason Klein's homepage](https://jasonklein.dev/), without copying their layouts or assets.

The education entries follow the supplied academic CV review copy. Only its two peer-reviewed publications are shown; manuscripts still under verification are omitted.

## Preview

Open `index.html` in a modern browser. The profile, research summary, and links remain available without JavaScript. Reduced-motion preferences pause the animation initially.

## Publish with GitHub Pages

Upload `index.html`, `style.css`, `portrait.jpg`, and `.nojekyll` to the root of the `main` branch of `shuo-pei/shuo-pei.github.io`, then configure **Settings → Pages → Deploy from a branch → main → /(root)**. Once GitHub Pages finishes deploying, the intended address is <https://shuo-pei.github.io/>.

Local edits appear on the live site after the updated files are committed to `main` and GitHub Pages deploys them.
