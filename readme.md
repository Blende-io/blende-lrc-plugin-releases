# Blende Lightroom Classic Plugin
This plugin enables direct exporting of photos from Adobe Lightroom Classic to the Blende platform. You can easily create and upload photo galleries with metadata directly to your Blende account.

## Features
- Direct export from Lightroom Classic to Blende
- Create new galleries with customizable title and description
- Set gallery privacy (public/private)
- Maintains photo metadata during upload
- Subscription status monitoring
- API connection status checking

## How It Works

The plugin creates a new export service in Lightroom Classic. When exporting photos, the plugin:

- Creates a new gallery on Blende with your specified title and description
- Uploads each selected photo to that gallery
- Includes all photo metadata in the upload
- Provides feedback on the upload process
- Offers to open your new gallery in a browser when complete

## Installation Instructions

### From GitHub Releases
- Go to the Releases page of this repository
- Download the latest BlendeLrC.zip file
- Extract the zip file to get the BlendeLrC.lrplugin folder
- Add the plugin to Lightroom Classic:
  - Open Lightroom Classic
  - Go to File > Plug-in Manager
  - Click Add and navigate to the extracted BlendeLrC.lrplugin folder
  - Click Done

### Manual Installation

If you want to use the latest development version:

- Clone this repository or download the source code
- Run the package.sh script to build the plugin
- Add the generated plugin to Lightroom Classic as described above

## Usage
- Select the photos you want to upload in Lightroom Classic
- Choose File > Export... or press Ctrl+Shift+E (Windows) or Cmd+Shift+E (Mac)
- In the Export dialog, select Blende from the export location dropdown at the top
- Enter your Blende API key
- Give your gallery a title and description
- Choose whether the gallery should be public
- Click Export to begin the upload process

## Getting Your API Key
- Log in to your Blende account at blende.io
- Go to your account settings
- Find and copy your API key

## Requirements
- Adobe Lightroom Classic (tested on version 10.0 and above)
- Active Blende account
- Internet connection

## Troubleshooting
- API Check Fails: Verify that your API key is correct and that you have an active internet connection
- Maximum Galleries Reached: You may need to upgrade your Blende subscription or delete some existing galleries
- Upload Failures: Check your internet connection and try again

## Support

For issues with the plugin, please open an issue on GitHub.

For questions about your Blende account or subscription, please contact Blende support.
