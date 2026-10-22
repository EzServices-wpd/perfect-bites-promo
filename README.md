# Perfect Bites Promo

**Everything is encapsulated.**

The perfect 1–2 bite of any dish. No mess. Known macros. Creative edible architecture.

This repository is set up so you can generate a short promotional launch video using the [latent-spaces/brag](https://github.com/latent-spaces/brag) skill.

## Concept
All products are fully encapsulated with edible coatings/skins (Foodberry-style). Cutaways reveal the perfect dish interior.

### Creative Renderings Included
- Sushi spheres (translucent / nori-black, geometric cutaways)
- Waffle cubes with grid-textured exteriors (chicken + strawberry/blueberry)
- Marbleized / gradient ice cream spheres
- Geometric burger & deli cubes (gallery-style, flavor-hint coatings)
- Floating mini coffee spheres
- Artistic variety arrangement of mixed shapes

## 20-Second Promo Video Storyboard (for /brag)
1. **0-3s**: Dark luxurious open → "Everything is encapsulated" text + floating sushi spheres with cutaway reveal.
2. **3-7s**: Quick cuts: waffle cube with grid skin + berry burst → marble ice cream sphere cracked open.
3. **7-12s**: Geometric deli/burger cubes on pedestals → floating coffee spheres with dramatic reveal.
4. **12-17s**: Artistic variety lineup of all shapes → packaging glimpse.
5. **17-20s**: Tagline lockup: "Perfect Bites. Zero mess. Known macros." + logo.

## How to Generate the Video with brag

1. Clone this repo:
   ```bash
   git clone https://github.com/EzServices-wpd/perfect-bites-promo.git
   cd perfect-bites-promo
   ```

2. Add the product rendering images into an `images/` or `assets/` folder (the creative encapsulated shots from the conversation).

3. Install the brag skill (choose one):
   - Claude Code: `/plugin marketplace add latent-spaces/brag` then `/plugin install brag@brag`
   - Or: `npx skills add https://github.com/latent-spaces/brag --skill brag`
   - Or use `/brag-slim` for leaner version.

4. In your agent (Claude Code, Codex, etc.), from this directory run:
   ```
   let's /brag
   ```
   Or: `/brag --tone "premium food launch, luxurious, no-mess perfection"`

5. Output appears in `brag-output/brag.mp4` plus share copy.

### Alternative: letsbrag.app
Host a simple GitHub Pages site or landing page from this repo, then paste the URL at [letsbrag.app](https://letsbrag.app) for a hosted 20s video.

## Next Steps
- Drop the high-quality rendering images into the repo.
- Run the skill to generate the shareable launch video.
- Customize tone or add voiceover if desired (`/brag --voice`).

Everything is encapsulated. Now go brag.
