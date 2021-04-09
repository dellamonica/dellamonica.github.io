# Dellamonica's personal page

This repo contains the code of my personal page.

## Videos page

The videos page uses Azure Storage to host the videos as blobs. Videos were
encoded for the web (this means that the index is placed at the beginning of the
file rather than at the end--search for a discussion of the *moov atom* for
MPEG-4).

The video meta data is stored as a JSON file in the same blob container.