kde store cursor uploads
========================

structure
---------
each subfolder here = one cursor set, ready to submit.

  kde-store-uploads/
    <theme-name>/
      <theme-name>.tar.gz   <- the file you upload to store.kde.org
      preview.png           <- screenshot to attach on the submission form (take one yourself before uploading)

how to upload
-------------
1. go to https://store.kde.org
2. log in (or create account)
3. click "Upload" -> "Add Product"
4. category: "Cursors" (under Plasma / Artwork)
5. fill title, description, license (Creative Commons Attribution for runescape-dragon2h)
6. upload the .tar.gz as the main file
7. upload preview.png separately in the Screenshots tab
8. publish

notes
-----
- license for runescape-dragon2h: CC-BY (attribution required, link back to http://www.rw-designer.com/cursor-set/runescape-dragon2h)
- original author: PhilEvil
- the tarball extracts to ~/.icons/<theme-name>/ when users install via KDE settings
- "Inherits=Adwaita" is set as fallback for cursor types not in the set

adding a new set
----------------
just drop another subfolder here with its own .tar.gz and preview.png.
