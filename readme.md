# Video upload Python scripts

This is a small set of scripts to upload video to Vimeo from a local directory, to analyse that video with Azure Media Services and produce a closed caption file, then add that closed caption file to the uploaded video.

## Usage

This script is intended to be run interactively from the command line. Relevant settings for your instance are in config.py. If you're using this with a repo, make sure to add it to your .gitignore file as it's where all the secrets live.

You'll need a Vimeo app developers account and an Azure Media Services subscription.