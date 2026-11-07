# FPVCraft style guide

Visual and writing rules for everything FPVCraft: in-game UI and HUD, the CurseForge/Modrinth page,
logo, screenshots, banners and this repository.

## Direction

Neutral, technical, calm. FPVCraft should look like a well-made tool for pilots, closer to a radio
transmitter screen or Betaflight Configurator than a gaming ad.

**Do not use**

- Pink, magenta, purple or cyan neon, synthwave or "cyber" looks
- Glow, bloom, lens flares, glassmorphism, heavy gradients
- AI-generated images or backgrounds
- Emoji-heavy text, ALL-CAPS hype, "ultimate", "insane", "epic"

## Colors

Mostly greys with one accent color. Use the accent sparingly: active states, key numbers, links.

| Role | Hex | Use |
|---|---|---|
| Background | `#121417` | Page and HUD panels (HUD at ~70 % opacity) |
| Surface | `#1C1F24` | Cards, buttons, menu panels |
| Border | `#2E333A` | 1 px separators and outlines |
| Text | `#E6E8EB` | Main text |
| Muted text | `#9AA1AA` | Labels, secondary info |
| Accent | `#E8A33D` | Amber: armed state, highlights, links |
| OK | `#4CAF7A` | Good signal, battery OK |
| Warning | `#E0B341` | Low battery, weak signal |
| Danger | `#D9534F` | Critical battery, signal lost, crash |

Light-background variant (website, README images): background `#F5F6F7`, text `#1B1E22`,
same accent and status colors.

## Typography

- In-game: Minecraft's default font. No custom fonts in the HUD.
- Web and images: one sans-serif (Inter, or the system font). Two weights only: regular and semibold.
- Numbers in the HUD (voltage, throttle, altitude, speed) use tabular/monospace digits so they do not jump.

## In-game HUD (OSD)

- Follow real FPV OSD conventions: small white/light-grey text with a thin dark outline, in the
  corners, nothing in the center except the crosshair.
- Status color only where it carries meaning (battery, signal). Everything else stays neutral.
- Flight mode shown as plain text: `ACRO`, `ANGLE`, `DISARMED`.
- Keep it readable at GUI scale 2 and do not cover more than the edges of the screen.

## Logo and icon

- Simple flat mark: a drone silhouette or quad-X shape in one color on a dark square.
- Works at 64 × 64 px (CurseForge icon) and in monochrome.
- No glow, gradients, 3D effects or text inside the icon.

## Screenshots and banners

- Real in-game footage only, shot with shaders off or a neutral shader pack.
- Show the mod doing something: flying through terrain, the OSD, the controller setup screen.
- Banner text: mod name plus one short line, set in the text color on a plain dark area of the image.

## Writing

- Short, factual and friendly. Say what the feature does, not how amazing it is.
- English for the mod page and the repo. Use FPV terms (acro, angle, rates, OSD) correctly.
- Changelogs as plain lists: Added / Changed / Fixed.
