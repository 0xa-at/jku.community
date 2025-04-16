# jku-community
Static website with all communities at JKU.


## How to edit your club info or add a new club? 

Fork the repo and add a new `INSERT_YOUR_CLUB_NAME_HERE.md` file in:
- `content/clubs` for clubs at the JKU
- `content/linz` for clubs in Linz

Edit your club file information such that it fits the following format:
```markdown
+++
title = "Cool Club"      # Insert the name here
description = ""         # Optional description

[extra]
link_to = "https://google.com/"    # Link to the website
category = ["tech"]                # List of categories
+++
```
Once you are done, open a pull request. As soon as the changes are merged (done by 0xA Team), view your updated club info at [jku.community](https://jku.community/)
