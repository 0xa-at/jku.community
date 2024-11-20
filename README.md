# jku-community
Static website with all communities at JKU.


## How to add a new club? 

Fork the repo and add a new `INSERT_YOUR_CLUB_NAME_HERE.md` file in:
- `content/clubs` for clubs at the JKU
- `content/linz` for clubs in Linz

The format for the file looks like this: 
```markdown
+++
title = "Cool Club"      # Insert the name here
description = ""         # Optional description

[extra]
link_to = "https://google.com/"    # Link to the website
category = ["tech"]                # List of categories
+++
```
