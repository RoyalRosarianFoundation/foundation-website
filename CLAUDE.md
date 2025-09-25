# Royal Rosarian Foundation Website Redesign

*Project documentation for Claude Code assistance*

## Project Overview

Redesigning the Royal Rosarian Foundation website as a modern static site hosted on GitHub Pages. The foundation is a Portland-based 501(c)(3) organization focused on community service, education support, and Rose Festival participation.

## Current Environment

- **Platform:** macOS (Darwin 25.0.0)
- **Working Directory:** `/Users/matthewclark/Desktop/projects/rrf`
- **Git Status:** Not a git repository (yet)
- **Static Site Generator:** Jekyll (Ruby-based)
- **Deployment Target:** GitHub Pages
- **Ruby Version:** Setting up rbenv with Ruby 3.1.0

## Project Structure

```
rrf/
├── CLAUDE.md                    # This file - project documentation
├── PRD.md                       # Product Requirements Document (formatted)
├── content.md                   # Scraped website content from original site
├── actor_worksheet.md           # User personas, task flows, journey maps
├── website_script.md           # HTML structure and navigation specifications
└── assets/                     # Media files and images
    ├── images/                 # Image assets to be downloaded
    └── README.md               # Asset organization guide
```

## Key Project Files

- **PRD.md** - Complete project requirements with timeline (Feb-July 2025)
- **content.md** - All content from original royalrosarianfoundation.org site
- **actor_worksheet.md** - 3 user personas (Nancy, Anette, Chris) with detailed UX research
- **website_script.md** - Technical HTML structure and semantic markup specifications

## Objectives

### Primary Goals
1. Create user-friendly platform that increases community involvement
2. Improve transparency and showcase measurable impact
3. Optimize donation and volunteer engagement funnel
4. Ensure WCAG 2.1 AA accessibility compliance
5. Mobile-first responsive design

### Target Users
- **Nancy** (Data-Driven Advocate) - Long-time supporter wanting transparency and metrics
- **Anette** (Community Builder) - Active volunteer focused on education initiatives  
- **Chris** (Curious Newcomer) - Portland native exploring community involvement

### Key Features for Launch
- Clear navigation and information architecture
- Impact metrics and testimonials
- Accessible donation system (Stripe integration)
- Mobile-responsive design
- Search functionality

## Development Setup

### Ruby Environment
```bash
# Install rbenv and Ruby
brew install rbenv
rbenv install 3.1.0
rbenv global 3.1.0
eval "$(rbenv init -)"

# Install Jekyll
gem install bundler jekyll
```

### Development Commands
```bash
# Development server (with local config)
export PATH="$HOME/.rbenv/bin:$PATH" && eval "$(rbenv init -)"
bundle exec jekyll serve --config _config.yml,_config_dev.yml --port 4001

# Build for local testing (empty baseurl)
bundle exec jekyll build --config _config.yml,_config_dev.yml

# Build for production deployment (with /foundation-website baseurl)
bundle exec jekyll build
```

### Configuration Files
- `_config.yml` - Main configuration with production settings
- `_config_dev.yml` - Development override (sets `baseurl: ""` for local testing)
- Use both configs for local development to ensure working links

## Content Strategy

- Mission: Supporting Portland community and Rose Festival participation  
- Programs: Field Trip Project, Annual Auction, Rose Garden Contest, Milk Carton Boat Race, Christmas for Kids
- Contact: PO Box 8956, Portland OR 97207-8956, info@royalrosarians.org

## Success Metrics
- Increase online donations (+25% in 6 months)
- Increase traffic and engagement (+20% in 6 months)
- Improve contact form utilization
- Better survey feedback scores

## Timeline
- **Phase 1:** Research and Planning (Complete by February 2025)
- **Phase 2:** Design and Prototyping (March 2025) 
- **Phase 3:** Development (April-May 2025)
- **Phase 4:** Testing and Launch (June 2025)
- **Phase 5:** Post-Launch Support (July 2025+)

## Team
- **Matthew Clark:** Project Lead
- **Barbara Brennan:** Content Strategist  
- **Meghan Jimenez:** UX Designer

---

*Last updated: August 29, 2025*