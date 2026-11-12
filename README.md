# The Castor Family Atlas
Interactive genealogy redesign. Development is on \`interactive-tree-redesign\`; deployed \`main\` remains unchanged until review and approval.

## Features
- Horizontal, zoomable, pannable relationship network
- Search, regional filtering, individual profile panel
- Marriage and partnership index
- Regional map and migration notes
- Historical timeline, source/method page, sitemap
- Responsive navigation and layout
- Living-person birth dates displayed at year-level only

## Files
- \`index.html\`: site structure and navigation
- \`style.css\`: parchment and modern styling
- \`data.js\`: people, regions, relationships, places and timeline
- \`app.js\`: D3 graph and interactions
- \`sitemap.xml\`: crawler sitemap

## Run locally
Serve this folder using a local static server (for example \`python -m http.server 8000\`) and open the local URL.

## Genealogy safeguards
Relationship edges are only included where the existing notes support them. Edward Castor of Pittsburgh is not connected to Hans Georg Gerster because parentage is not established. Family-record entries are not independently verified. Regional map pins are broad reference points, not precise ancestral addresses.

External libraries: D3.js v7, Leaflet 1.9.4 and OpenStreetMap tiles.