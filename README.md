# Pymake


Prerequisites

- ```pip install PyQt6 PyQt6-WebEngine pyinstaller``` |For 1.0 Full Release onwards.

- ```pip install PyQt5 PyQtWebEngine pyinstaller```  |For 1.0 Pre-Release (Legacy)

- **Or** run the included batch script (If you are on Windows).

---
# Usage

1) Run Pymake ```python Pymake.py```
2) Enter the app name and the URL of the website you want to convert to a Web Application.
3) When prompted to build the executable, type Y (if you want to get a .exe file).
4) Navigate to the `webapps` folder inside your build directory to access your freshly built app.

**Pymake is provided in both .py and .exe forms.**

  ---

  Your filetree should look like this

  | buildfolder |

   -> webapps

  In the "webapps" folder you have your exe, and a py file (which contains the source code) upon script generation.

## Notes from devs:

1)**Be aware that Pymake is by no means perfect, but it will improve. We are struggling with getting all the sites to display properly, but most of them are already "usable"** (for the _most part_ at least).

- Hopefully it works for you!
