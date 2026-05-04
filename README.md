# Veterinary Pathology Tools Showcase

A collection of interactive HTML demos and tools for veterinary pathology taxonomy integration, including:

- **GBIF API Demo** - Live species lookup against GBIF database
- **Catalogue of Life Demo** - Taxonomic hierarchy viewer
- **Combined Taxonomy Demo** - Integrated view of multiple taxonomic sources
- **Standardized Taxonomy Demo** - Normalized taxonomy for veterinary pathology

## Structure

```
├── index.html                    # Main dashboard/landing page
├── col_simple_demo.html          # Catalogue of Life simple demo
├── combined_demo.html            # Combined taxonomy view
├── combined_demo_v2.html         # Combined view v2
├── combined_demo_v3.html         # Combined view v3
├── combined_demo_v5.html         # Combined view v5
├── gbif_api_demo.html            # GBIF API demo
├── gbif_live_lookup.html         # GBIF live species lookup
├── standardized_taxonomy_demo.html  # Standardized taxonomy demo
├── attempt1.html                 # Initial attempt/prototype
├── data/                         # JSON data files
│   ├── CoL_taxonomy.json
│   ├── generic_taxonomy.json
│   └── taxonomy_glossary.json
└── netlify.toml                  # Netlify deployment config
```

## Local Development

Open any `.html` file in a browser, or use a local server:

```bash
# Python 3
python -m http.server 8000

# Node.js (if you have npx)
npx serve .
```

Then visit `http://localhost:8000`

## Deployment

This site is auto-deployed to Netlify via GitHub integration. Pushes to the `main` branch trigger automatic deployments.

## Data Sources

- [GBIF](https://www.gbif.org/) - Global Biodiversity Information Facility
- [Catalogue of Life](https://www.catalogueoflife.org/) - Comprehensive taxonomic database

## License

Public data repository - see individual data sources for their respective licenses.
