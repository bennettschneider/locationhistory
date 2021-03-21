# locationhistory
Reads json export from your google history and plots your past locations on an interactive map

# Instructions to get you data from Google
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

# Instructions to set up python environment
- If you don't already have it download Anaconda python
- In the anaconda navigator, create a new python3.8 environment
- In the anaconda prompt, activate this environment using "conda activate [your environment name]"
- cd to the repo location
- Run "conda install --file requirements.txt" to install the prerequisits
- Run "jupyter notebook", also in the anaconda prompt (if you've moved the ipynb file out of the repo, cd to the new directory first)
- Open the ipynb file in your browser
