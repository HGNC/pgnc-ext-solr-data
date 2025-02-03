# Solr_data
This directory contains the Solr data files for the external stack. Solr is used as the search engine for indexing and querying content.

## Structure
- `conf/`: Configuration files for Solr
- `data/`: Persistent data storage for Solr indices

## Usage
The data in this directory persists between container restarts. Do not modify these files directly unless you know what you're doing.

## Maintenance
- Regular backups of this directory are recommended
- Refer to Solr documentation for data management best practices