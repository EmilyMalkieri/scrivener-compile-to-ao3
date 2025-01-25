# AO3 Compile Format

Custom Scrivener compile format for the AO3 HTML editor.

Compiling your fic with this compile format will create a text file (.txt) containing HTML code that will play well with the AO3 HTML editor. Simply open the file in your text editor of choice (simple ones like Notepad, TextEdit, etc. not Word) and copy-paste the contents into the AO3 HTML editor.

## Features

- Properly spaced paragraphs.
    - If you wrote a regular paragraph in Scrivener (only pressed enter once), you'll get a regular paragraph on AO3.
    - If you wrote a paragraph break with a blank line between, you'll get a blank line between on AO3.
- Automatic `<hr />` scene breaks between files. This is a proper horizontal line that should work well with screen readers.
- Blockquotes, italics, and bold text.

## Use this in five simple steps

1. Install this compile format.

    - Manual install (all platforms): Download the .scrformat file and import it in Scrivener's compile dialog via "..." → "Import Format..."
    - Automatic install via homebrew (Mac): `brew install EmilyMalkieri/tap/scrivener-compile-to-ao3`

2. Select this format in your compile dialog. First at the top of the screen select "Compile for: Plain Text (.txt)", then on the left select "AO3 Fanfic (for HTML editor)".

3. If necessary, assign your section layouts.

4. Compile!

5. Open the file and paste its contents into the AO3 HTML editor.

