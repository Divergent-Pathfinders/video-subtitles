# Video upload Python scripts

This is a small set of scripts to upload video to Vimeo from a local directory, to analyse that video with Azure Media Services and produce a closed caption file, then add that closed caption file to the uploaded video. It's designed to do this as quickly and easily as possible with minimal costs incurred.

## Why?

Adding closed captions to videos is hugely important for accessibility and for people engaging with your content online. However, it's time consuming and/or prohibitively expensive to implement. This script and the workflow behind it is intended to make it about as cheap and easy as possible.

It does the following:

- Upload a video to Vimeo from local storage
- Analyse the video by URL in Azure Media Services
- Download the created caption file to local storage
- Add that caption file to the video in Vimeo

## Usage

This script is intended to be run interactively from the command line. Relevant settings for your instance are in config.py. If you're using this with a repo, make sure to add it to your .gitignore file as it's where all the secrets live.

## Requirements

You'll need at least a Vimeo Pro subscription and an Azure Media Services subscription. You'll also need the Vimeo Python SDK and the Azure Python SDK.