# Overview

This is a demo repo showing how one might load remote content into the Packer documentation website.

Specifically, this demo repo shows the loading of a nested docs section.

## Next Steps

- [ ] Automatically resolve and add `filePath` values in `_nav-data.json`
  - Currently these values need to be manually entered
  - It might be nice to have an embedded GitHub Action that would...
    1. Ensure files exist for each `_nav-data.json` node
    2. Automatically resolve "named" vs "index" files
