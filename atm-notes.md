# Notes

## General organization
- Center column is very narrow for embedded content
- Could we separate out the docs so that they're easy to remove from the site?
- Foregrounding the What and Why for using the project
- Remove unnecessary images
- Change the names of the demo images so they are easy to remove (using page names is confusing)
- How many of these layouts etc. are actually in use?
- Can you please add a github link somewhere on the menu or sidebar?


## Specific

- To get rid of the table of contents, you actually have to say "TOC: false" -- please specify in the docs
- Doesn't support relative URLs for images (it does on page, not in thumbnail gallery, probably because the image links default to relative)
- I don't think pagination is necessary (blog thing): deactivate to avoid confusion
- Too much space under images & figures? Is this because the 'fig caption' isn't connected with a figure?
- Wide class works, but the toc is also wide, which doesn't look great
- Can you get rid of the sidebar on a project page?


## Embedding

- iFrame issues: using variable 'code' is confusing because it could refer to so many things - why not 'embed_code' or something else?
- Option suggested in the docs: use it as a list element (this isn't good practice for accessibility purposes)
- Add 'view fullscreen' link (feature) for embedded content

## Docs

- Change the 'fork' language to 'use this template'