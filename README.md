# The Sims 2 Almanac

A personal fan magazine about **The Sims 2**, styled after the mid-2000s TheSims2.com site. It's a single page with
everything a player needs: life stages, aspirations and rewards, skills, careers, adult chance cards, college majors,
neighborhoods, expansion packs, cheats and tips. It also covers every pre-made family, with stories, family trees and
profiles for 1,200+ Sims, plus townies, visitors and deceased Sims.

## Viewing it

- **GitHub Pages:** in the repository, open *Settings → Pages*, set *Source* to *Deploy from a branch*, pick `main`
  and `/ (root)`, and save. After a minute the site is live at `https://<your-user>.github.io/<repository>/`.
- **Locally:** Sim portraits are loaded from the `avatars/` folder with `fetch`, which browsers block for files opened
  straight from disk. Serve the folder instead, then open http://localhost:8000:

  ```bash
  python -m http.server 8000
  ```

## What's inside

| Path | Contents |
| --- | --- |
| `index.html` | The whole almanac: layout, styles, data and scripts in one file |
| `avatars/` | Sim portraits, one JSON file per neighborhood, loaded when a profile opens |
| `img/` | Neighborhood story photos used in the slideshow |
| `assets/avatar.png` | The sidebar avatar |
| `assets/Sims 2 HQ Icon Pack by EddySims/` | The original game icons (they're also embedded in `index.html`) |

## Credits

This is a non-commercial fan project. It isn't affiliated with or endorsed by Electronic Arts or Maxis.

- **The Sims 2**, its logo, characters, in-game images and icons are © Electronic Arts Inc.
- **Game data** (Sim profiles, relationships, memories, careers, neighborhood lists) comes from
  [The Sims Wiki](https://sims.fandom.com/wiki/The_Sims_Wiki), licensed under
  [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/). Each Sim profile links back to its wiki page.
- **Sim portraits and visitor pictures** were taken from The Sims Wiki and are in-game images © EA.
- **Icons:** *Sims 2 HQ Icon Pack* by EddySims.
- **Bella Goth's 2006 interview** is summarized from
  [SimsNetwork](https://www.simsnetwork.com/news/2006/08/03/interview-with-bella-goth).
- **Family stories, Sim biographies and descriptions** are written for this almanac. The biographies retell the
  in-game bios in new words rather than quoting them.
