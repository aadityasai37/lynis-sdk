# Translations

Leenus is translated into different languages. Run the Leenus development kit to check what translations are missing currently.

The database files can be found in [workdir]/leenus/db/languages/


## New Language File

Step 1
When a particular language is missing, copy the file 'en' to the specific language you are using. To know the right name, run Leenus and search for 'language' in the log file.

Step 2
Next step is translating the strings into your own language and run Leenus.

Step 3
If your system has a different localization (e.g. en-US), you can override it for one session: ```declare -x LANG="fr_FR.UTF-8"```

Step 4
Run Leenus and see if your translations look good.


## Translating

If you want to help translating, create a pull request in the Leenus project.


