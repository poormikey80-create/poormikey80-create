<p align="center">
  <img src="https://raw.githubusercontent.com/poormikey80-create/poormikey80-create/main/assets/header.svg" alt="Mikayla P. — Solo Game Dev" width="880"/>
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/poormikey80-create/poormikey80-create/main/assets/now.svg" alt="now" width="720"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Godot-4.x-478CBF?style=flat&logo=godotengine&logoColor=white" height="22"/>
  <img src="https://img.shields.io/badge/GDScript-2.0-355570?style=flat" height="22"/>
  <img src="https://img.shields.io/badge/Aseprite-pixel%20art-7D929E?style=flat" height="22"/>
  <img src="https://img.shields.io/badge/Python-3-3776AB?style=flat&logo=python&logoColor=white" height="22"/>
  <img src="https://img.shields.io/badge/Audacity-000000?style=flat&logo=audacity&logoColor=white" height="22"/>
</p>

---

Solo game dev in Austin, TX. I build small 2D games in Godot 4 and draw the art
myself in Aseprite, usually at 16x16, because that is the biggest canvas I can
actually finish in one sitting.

Time-poor, idea-rich. The ideas folder is currently winning 41 to 3.

Most of what I put here is jam leftovers that turned out to be useful on their
own: a movement controller I keep re-typing, a palette I keep re-importing, a
build script I keep re-writing at 1am. Now they have a home.

## Tools I actually use

- **Godot 4.x** — every project ships from here. GL Compatibility renderer, so
  builds run on the ten-year-old laptop under my desk.
- **GDScript** — statically typed where it helps, `class_name` on anything I
  reuse more than twice.
- **Aseprite** — sprites, tilesets, palettes. 16-colour ramps by default.
- **Python 3** — the glue: sheet packing, palette linting, zipping builds for
  itch uploads.
- **Tiled** — only when a level outgrows hand-placed tiles in the editor.
- **Git and GitHub** — one branch, small commits, no ceremony.
- **Audacity** — placeholder sound effects made with my own mouth. Sorry.

## Selected projects

**[jam-bunny](https://github.com/poormikey80-create/jam-bunny)**
A minimal Godot 4 hop-and-collect scene: variable-height jump, floaty hang
time, squash-and-stretch on takeoff. The skeleton I start every jam from.

**[pixel-pals](https://github.com/poormikey80-create/pixel-pals)**
My 16-colour Aseprite palette plus a Python packer that turns a folder of
frames into a sprite sheet and atlas, and yells at any pixel that drifted
off-palette.

**[gdscript-utils](https://github.com/poormikey80-create/gdscript-utils)**
Three dependency-free GDScript helpers I copy into every project: a tiny state
machine, a cooldown timer, and the math functions Godot does not ship with.

**[godot-shaders](https://github.com/poormikey80-create/godot-shaders)**
Three 2D shaders I re-typed across too many jams before I accepted they
deserved a repo: an outline shader for selection and glow, a palette-swap
shader for character variants without duplicate sprites, and a dissolve
shader for death animations that does not need an external noise texture.

**[sfx-kitchen](https://github.com/poormikey80-create/sfx-kitchen)**
A zero-dependency Python script that generates game SFX from basic waveforms
with ADSR envelopes and frequency sweeps. Exists because my mouth is not a
synthesizer, no matter how much Audacity insists it could be.

## Currently

Prototyping a one-room dungeon crawler where the room rotates instead of the
player. It is either a good idea or a motion sickness lawsuit. Progress is
slow and mostly happens on weekends.

Also slowly porting my old jam entries off a dying external drive, so a few
repos here will look suspiciously like 2019 code. They are.

## 📊 Activity

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=poormikey80-create&show_icons=true&theme=transparent&hide_border=true&count_private=true"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=poormikey80-create&layout=compact&theme=transparent&hide_border=true"/>
</p>
<p align="center">
  <img width="720" src="https://github-readme-activity-graph.vercel.app/graph?username=poormikey80-create&theme=github-compact&hide_border=true&radius=8"/>
</p>

## Contact

GitHub only. Open an issue on the relevant repo and I will get to it, usually
within a few days. Pull requests are welcome on anything tagged
`good first issue`, and honestly on anything else too, as long as it keeps the
zero-dependency rule.

I do not do email, Discord, or Twitter for project stuff. Nothing personal, I
just lose track of every inbox that is not this one.

## A note on licences

Everything I publish is MIT unless the repo says otherwise. Use the code in
your commercial game, no credit needed. The art is a different story: palettes
are free to use, but finished sprites are CC BY-NC unless we talk first.

---

<sub>Austin, TX. Mostly building things after the day job.</sub>
