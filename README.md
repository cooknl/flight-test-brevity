# flight-test-brevity

A port to Quarto of the Flight Test Brevity Guide

Available at GitHub Pages

<https://cooknl.github.io/flight-test-brevity/>

## How to update the Guide

### Zotero

The Zotero collection for Brevity is at <https://www.zotero.org/nathangs20/collections/USDKC26V>

To add a reference

1. Copy the file to the `flight-test-brevity` repo root folder
1. Add a new item to the Zotero collection, including information fields, and attach the file by uploading
1. Export collection as CSL-JSON
1. Rename to `zotero.json`
1. Delete the `{"items":` at the beginning and the `}` at the end to leave an array `[]`
1. Copy to `flight-test-brevity` repo root folder
1. Update `qmd` files with ids from new `json` file
1. Re-render the document
