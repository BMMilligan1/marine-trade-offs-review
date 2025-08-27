# Marine Governance Trade-offs: A Functional Analysis of Global Management Approaches

This repository contains the source code and content for the research report "Marine Governance Trade-offs: A Functional Analysis of Global Management Approaches" by Phil James and Ben Milligan from the UNSW Centre for Sustainable Development Reform.

## Access the Report

- **[Read online](https://bmmilligan1.github.io/marine-trade-offs-review/)** - Interactive web version
- **[Download PDF](https://bmmilligan1.github.io/marine-trade-offs-review/marine-trade-offs.pdf)** - Print-ready version

## About

This report presents a functional typology that deconstructs marine governance systems—including Ecosystem-Based Management, Marine Spatial Planning, and Integrated Coastal Zone Management—into their fundamental design features. Through comparative analysis of governance approaches across 15 national and sub-national case studies, we identify critical mismatches between governance architectures and trade-off types that explain systematic policy failures.

## Development

This report is built using [Observable Framework](https://observablehq.com/framework/), a static site generator for data apps.

### Prerequisites

- Node.js (version 18+)
- npm

### Setup

```bash
# Clone the repository
git clone https://github.com/BMMilligan1/marine-trade-offs-review.git
cd marine-trade-offs-review

# Install dependencies
npm install
cd pdf-export && npm install && cd ..

# Start development server
npm run dev
```

The site will be available at http://localhost:3000

### Building

```bash
# Build the site
npm run build

# Generate PDFs
npm run pdf:export
```

## Citation

James, P. & Milligan, B. (2025). Marine Governance Trade-offs: A Functional Analysis of Global Management Approaches. UNSW Centre for Sustainable Development Reform.

## License

© 2025 Phil James and Ben Milligan, UNSW Centre for Sustainable Development Reform. All rights reserved.