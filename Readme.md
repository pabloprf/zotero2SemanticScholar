# Zotero to semantic scholar

Zotero and SemanticScholar are very powerful. I personally use the first to manage my bibliography and generate bibtex for my own notes and the second as an alternative to Google Scholar to alert me on the latest papers. 
However, it can be boring to enter his bibliography in each site, even more when it's composed of hundred of different papers ! Therefore, I made this project __to send the bibliography from Zotero to SemanticScholar and to add alert on articles__.

## How to send data to SemanticScholar

In Zotero export the library in __format CSV__ (File/Export Library), then launch the gui. Filled the login and password input select the csv file you export just before. Finally click on _Send data to SemanticScholar.com..._, wait for a minute... that's it ! 🙂 

There is a save system, to know which papers has been sent to semanticScholar. Therefore, if you need to send a new part of your library to semanticScholar it'll only send the new articles. Likewise, if the application crash your progression will be saved.

## Building

1. You need to have [python 3](https://www.python.org/downloads/) installed.
2. You need the following package : `pandas, csv, tkinter, distance, and selenium`
To install them use this command in the project folder :
```
pip install -r requirements_dev.txt
```
For windows os skip to step 4. 
3. You need the driver firefox for selenium that are available [here](https://github.com/mozilla/geckodriver/releases). Moreover, the folder downloaded here need to be in path.
4. Finally build `main.py` file.

I didn't try the project elsewhere than on windows, but I think it could works on linux or macOS, it may require additional installations.

## Potential improvements

- Test it on other OS than Windows.
- Make a script to automatize the installation.
- Package the script in an executable.
- Switching from an external gui to a zotero add-on integrated directly in zotero.

## Issues

If you have some issue with the application, do not hesitate to put them in [github issue](https://github.com/davidAlgis/zotero2SemanticScholar/issues).

