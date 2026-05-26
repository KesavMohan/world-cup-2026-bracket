# FIFA World Cup 2026 Bracket Explorer

A comprehensive, interactive schedule and bracket explorer for the FIFA World Cup 2026, featuring all 104 matches across 16 host cities in the USA, Canada, and Mexico.

## Features

- **All Matches View**: Browse all 104 matches with filtering by team, city, and round
- **Team Permutations**: Explore potential bracket paths for each team
- **City Schedule**: See which matches are hosted in each city
- **Group Stage**: View group compositions and matchups

## Analytics

This project uses [Vercel Web Analytics](https://vercel.com/analytics) to collect privacy-friendly traffic insights. The analytics are cookie-free and do not track personal information across sites.

## Development

### Prerequisites

- Node.js and npm installed

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/KesavMohan/world-cup-2026-bracket.git
   cd world-cup-2026-bracket
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the analytics bundle:
   ```bash
   npm run build
   ```

### Project Structure

- `index.html` - Main application page
- `privacy.html` - Privacy policy
- `analytics.js` - Vercel Web Analytics initialization
- `dist/analytics.min.js` - Bundled analytics script (generated)
- `package.json` - Project dependencies and build scripts

### Scripts

- `npm run build` - Bundles the Vercel Analytics script using esbuild

## Deployment

The site is deployed to GitHub Pages and can be accessed at [worldcupschedule.world](https://worldcupschedule.world).

To deploy updates:

1. Build the analytics bundle: `npm run build`
2. Commit and push changes to the `main` branch
3. GitHub Pages will automatically deploy the updates

## License

ISC

## Privacy

See [privacy.html](./privacy.html) for our complete privacy policy, including information about Vercel Web Analytics and Google AdSense.
