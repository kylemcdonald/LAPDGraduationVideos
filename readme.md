# LAPD Graduation Videos

[https://vimeo.com/inboundfilmsproductions](https://vimeo.com/inboundfilmsproductions) hosts videos of LAPD graduations.

This code downloads relevant videos and saves headshots.

0. Create a file `.access_token` that includes your Vimeo API access token.
1. Setup your Python environment according to `download-metadata.ipynb` and run the notebook.
2. The file `lapd-videos.csv` was hand-edited after it was initially output by the above notebook.
3. Run `process-videos.ipynb` to process all the videos and save images into `images/`.
