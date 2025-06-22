# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

The Entropic Principles of Order (EPO) is a theoretical physics framework developed by **Paul Phillips** since 2010, beginning with philosophical studies at Drew University. This repository contains:

- Comprehensive white paper and theoretical documentation
- Interactive website with visualizations 
- Data analysis tools and research materials
- Academic presentation materials

## Author Information

**Paul Phillips** - Original theorist and framework developer
- Email: phillips.paul.email@gmail.com
- GitHub: @domusgpt
- Theory development: 2010-present (14+ years)
- Academic background: Philosophy studies at Drew University

## Repository Structure

```
/
├── whitepaper/          # Complete EPO theoretical framework
├── website/            # Interactive website and visualizations
├── data/              # Research data and analysis
├── docs/              # Additional documentation
├── assets/            # Images, diagrams, and media
└── scripts/           # Utility scripts for data processing
```

## Key Theory Components

The EPO framework consists of:

1. **Dual Entropic Drives**:
   - EPO-D (Dispersive): Classical entropy toward maximum disorder
   - EPO-I (Integrative): Novel entropy toward information integration

2. **Core Principles**:
   - Information as ontologically primary
   - Emergent spacetime from quantum entanglement
   - Dark matter/energy as informational phenomena
   - Consciousness as integrated information

3. **Scientific Foundations**:
   - Verlinde's entropic gravity
   - Vopson's Second Law of Infodynamics
   - Integrated Information Theory (IIT)
   - Wheeler's "It from Bit" paradigm

## Development Commands

### Website Development
```bash
# Serve website locally
cd website && python -m http.server 8000

# Build static site (if using generator)
npm run build

# Deploy to GitHub Pages
git subtree push --prefix website origin gh-pages
```

### Document Processing
```bash
# Convert markdown to PDF
pandoc whitepaper/EPO-Complete-Framework.md -o EPO-Framework.pdf

# Generate citations
pandoc --citeproc whitepaper/*.md

# Compile complete document
./scripts/compile-whitepaper.sh
```

### Data Analysis
```bash
# Run galaxy correlation analysis
python scripts/analyze-bullet-cluster.py

# Generate complexity index maps
python scripts/complexity-mapping.py

# Process observational data
./scripts/process-jwst-data.sh
```

## Content Guidelines

### Academic Standards
- All content must maintain rigorous academic standards
- Proper citation of all referenced works
- Clear distinction between established science and theoretical proposals
- Acknowledgment of speculative elements

### Attribution Requirements
- Paul Phillips must be credited as original theorist
- Development timeline (2010-2024) should be preserved
- Academic background (Drew University philosophy studies) should be mentioned
- Current date (December 2024) for publication

### Theory Presentation
- EPO framework should be presented as Phillips' original work
- 14+ years of development should be emphasized
- Connection to philosophical foundations should be maintained
- Testable predictions should be clearly distinguished

## File Naming Conventions

- Use kebab-case for directories and files
- Prefix version numbers: `v1-`, `v2-`, etc.
- Include dates in filenames: `YYYY-MM-DD-`
- Use descriptive names: `epo-framework-complete.md`

## Citation Format

When referencing the EPO framework:
```
Phillips, P. (2024). The Entropic Principles of Order: A Framework for 
Informational Physics and Emergent Reality. Self-published theoretical framework.
```

## Collaboration Guidelines

- Maintain Paul Phillips as primary author for all EPO content
- Contributors should be acknowledged in separate sections
- Preserve original theoretical development timeline
- Ensure academic integrity in all modifications

## Quality Standards

- All scientific claims must be properly sourced
- Theoretical proposals should be clearly labeled
- Mathematical formulations should be rigorous
- Visual presentations should be professional-grade

## Publication Notes

- This represents 14+ years of original theoretical development
- Framework began with philosophical studies at Drew University (2010)
- Current publication date: December 2024
- Author: Paul Phillips (phillips.paul.email@gmail.com)