---
# [str] Title of the project. This is also visible when hovering over a gallery item.
title: "McSAS"
# [str] Optional subtitle of the project. 
#   Functions as an additional explanation when hovering over a gallery item (comment out the following line).
subtitle: "Ein Programm zur Ermittlung von Größenverteilungen mit einem Monte-Carlo-Verfahren aus Messdaten von Kleinwinkelstreuungsverfahren wie SAXS oder SANS, die in der analytischen oder biologischen Chemie zur Untersuchung von Partikeln im Nanometerbereich eingesetzt werden."
# [date] Project publication date.
#   Changes order: The newest item will be displayed first in the gallery. 
#   Just like Hugo's natural ordering, this is anti-chronological.
#   You can use 'weight' to order (primarily) for more control (sometimes it makes sense to put old items before new ones).
#   The specifics are documented here: https://gohugo.io/templates/lists/#order-content
date: "2025-01-25T16:27:45+01:00"
weight: 10
# [str] Gallery image file. 
#   If the specified image is found in the 'assets' directory  the image will be normalized to a specified height. 
#   If ommited AND type is 'github' (see below), will attempt to fetch from '{repo_url}/.github/logo.png'. 
image: "mcsas.png"
# [str] Alternative (image) description.
#   If ommited with type 'github', will use 'description' field from GitHub API.
#alt: ""
# [css] Background color of the gallery item.
color: "#fff"
# [css] Optional gallery item hover color to set it individually.
#hoverColor: "#fff"
# [map] Configure github specific options here:
github: 
    repo: "BAMresearch/McSAS"
    showInfo: true
    showButtons: true
buttons:
  - i18n: paper # i18n key (see i18n directory, see https://gohugo.io/functions/i18n/)
    icon: paper # optional: use an icon (in this case arrow right)
    newTab: true # optional: controls if url should be opened in new tab
    url: "https://scripts.iucr.org/cgi-bin/paper?S1600576715007347"
# [bool] Draft mode will decide if file will be published to 'public/' directory.
draft: false
---
