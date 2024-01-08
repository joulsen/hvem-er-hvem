# Hvem er hvem
Script for building custom inserts for *Guess Who?* (*Hvem er Hvem?*).

# Building
* Install [nanDECK](https://www.nandeck.com/) (only for Windows)
* In nanDECK press `Open deck` and select `guess-who.txt`
* Press `Validate deck`, `Build deck` and finally `PDF` on the left sidebar
* Do the same for the file `guess-who-yellow.txt`

# Customising
* Ensure that card size matches. They are defined on line 5 of each `.txt` file in millimetres.
* Add characters by adding new images to `resources/` in `.png` format
* Edit `data.txt` and add the name of the character followed by the filename without file extension
* Do not delete the first line of `data.txt`
