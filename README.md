# locationhistory
Reads json export from your google history and plots your past locations on an interactive map
To get this history do the following:
- Go to maps.google.com
- Click the sidebar on the left and click "Your Timeline"
- Hit the settings gear in the bottom right and click "download a copy of all your data". This will take you to Google Takeout
- Deselect all, scroll down to Location History, select it, and click "Multiple Formats" and select "json"
- Scroll down to the bottom and select "Next Step"
- Select "Create Export"
- Google will prepare your data which may take several minutes. When it is ready, it will appear on the same page
- Download this to your local drive, extrac the data and place it wherever you like
- Rename the top-level folder to "json"
- Put the jupyter notebook to the folder above "json" (or change myPath variable to the folder above "json")
