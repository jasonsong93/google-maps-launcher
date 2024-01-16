# google-maps-launcher

Script:
1. Gets a street address from the command line arguments or clipboard
2. Opens the web browser to the Google Maps page for the address

This means your code will need to do the following:

1. Read the command line arguments from sys.argv.
2. Read the clipboard contents.
3. Call the webbrowser.open() function to open the web browser.

---

Requirements:
- Have Python installed, and `pyperclip` dependency
- You can install `pyperclip` with `pip`: `pip install pyperclip`
- `pip` can be installed using `sudo apt install python3-pip`