# Create a human-readable Google Doc from a Google Tag Manager JSON export
Upload a Google Tag Manager JSON container export file and output a human-readable Google Doc describing tags, triggers and variables.

## How to use the CoLab
If you don't know anything about Google CoLab, [start here](https://colab.research.google.com/)

1. Click on prettify_GTM_JSON_export.ipynb, then click 'Open in CoLab' - this will open a copy owned by you
2. [Generate an export of a GTM container](https://support.google.com/tagmanager/answer/6106997?hl=en#:~:text=to%20multiple%20containers.-,Export%20a%20container,-In%20the%20top)
3. In CoLab, run the code cell below 'Imports and authentication' to import libraries and authenticate using a Google account - this is so you can create a Google Doc
4. Run the next code cell to upload your GTM export file. Click 'Choose Files' to find it on your local drive.
5. Run the next code cell to create an HTML version of the output. You can find the HTML file by clicking on the folder icon in the left bar. Files are not saved permanently in Colab, so you'll want to download it if you want a copy of the HTML version.
6. Run the last code cell to create a Google Doc version.
