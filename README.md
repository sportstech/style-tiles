Style Tiles
===========

The following is an exerpt from [http://styletil.es/](http://styletil.es/)

Style Tiles are a design deliverable consisting of fonts, colors and interface elements that communicate the essence of a visual brand for the web.

They help form a common visual language between the designers and the stakeholders and provide a catalyst for discussions around the preferences and goals of the client.

Style Tiles are similar to the paint chips and fabric swatches an interior designer gets approval on before designing a room. An interior designer doesn't design three different rooms for a client at the first kick-off meeting, so why do Web designers design three different webpage mockups?

## Style Adjectives

For example, here's the adjectives for white label bracket.

- **Intuitive**
  - Discuss with team
- **Modern**
  - Discuss with team
- **Sporty**
  - Discuss with team
- **Masculine**
  - Discuss with team
- **Established**
  - Discuss with team

## Style Tile Sass Variables

- **Primary Color**
  - **Secondary Color** (some derivative of primary)
  - **Tertiary Color** (some other derivative of primary)
  - **Text Color Light** (some light derivate of primary 'lighten(primary, x%)', for example )
  - **Text Color Dark** (some dark derivate of primary 'darken(primary, x%)', for example )
  - **Primary Action Color** (based on primary or secondary color)
  - **Primary Action Hover/Active Color** (darker or lighter version or primary action color)
- **Font Family** (Assuming one font family for both headlines and text)
- **Font Size Variations**
  - **Large** Font Size
  - **Medium** Font Size
  - **Base** Font Size
  - **Small** Font Size
- ...

## Local Dev

- Switch to the `gh-pages` branch. `git checkout -b gh-pages`
  - This is the default branch for the project.
- run: `jekyll serve --baseurl ''`

## Git Hub Pages Deployment

Should be all set up. Just be sure to push any changes to the `gh-pages` branch. These current state of the [style tile app will be visible here](http://sportstech.github.io/style-tiles/).