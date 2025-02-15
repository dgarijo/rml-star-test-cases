## SOMEF use case
The software metadata extraction framework (SOMEF) extracts key metadata from a software source code repository based on its readme documentation. As a result, a JSON is produced. Each field can be extracted with a series of techniques (supervised classification, header analysis, regular expressiones, etc.) and has a certain confidence.

This folder contains:
- The mapping (rml-map.ttl) transforming the JSON format in SOMEF into RDF-star
- A sample input (sample_input.json) with an artificial entry with most of its fields complete.
- Results (result.nt) containing the results of transforming the input into RDF-star
- A zip file (oeg_json.zip) with 237 JSON files obtained after applying SOMEF to the oeg-upm GitHub organization
- A folder with the zip uncompressed (oeg_json)
