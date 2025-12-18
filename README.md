# Manhattan Neighborhoods Quiz

A beautiful, interactive quiz game to test your knowledge of Manhattan's neighborhoods.

## How to Play

1. Open `index.html` in a web browser, OR
2. Run a local server (recommended for best compatibility):

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (npx)
npx serve
```

Then visit `http://localhost:8000` in your browser.

## Game Features

- **40 Manhattan neighborhoods** to identify
- **Detailed SVG map** with accurate neighborhood boundaries
- **Dark, elegant NYC-themed design** with golden accents
- **Smart answer matching** - accepts common abbreviations and variations
- **Timer** to track your speed
- **Score tracking** with letter grades (S, A, B, C, D)
- **Missed neighborhoods list** shown at the end

## Neighborhoods Included

- **Downtown:** The Battery, Battery Park City, Financial District, Tribeca, Civic Center, Two Bridges, Chinatown, Little Italy, Hudson Square
- **Village Area:** SoHo, NoLita, NoHo, Greenwich Village, West Village, East Village, Meatpacking District
- **Midtown:** Chelsea, Flatiron District, Gramercy, Kips Bay, Murray Hill, Turtle Bay, Koreatown, Garment District, Diamond District, Theater District, Sutton Place, Midtown, Hell's Kitchen
- **Upper Manhattan:** Upper East Side, Upper West Side, Yorkville, Stuyvesant Town, Alphabet City, Lower East Side
- **Uptown:** Morningside Heights, Harlem, East Harlem
- **Islands:** Roosevelt Island, Randall's Island

## Controls

- **Type** the neighborhood name and press **Enter** to submit
- **Skip** button reveals the answer and moves to the next one
- Skipped neighborhoods count against your score

## Tips

- Common abbreviations work: UWS, UES, LES, FiDi, SoHo, NoHo, NoLita, HK
- Alternative names accepted: "El Barrio" for East Harlem, "The Village" for Greenwich Village, "Clinton" for Hell's Kitchen
- The highlighted neighborhood appears in red

## Files

- `index.html` - Main game file (fully self-contained with embedded SVG map)
