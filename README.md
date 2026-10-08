# PHA Skill Index

Index of PHA skills published in open GitHub repositories.

This repository does not contain the skills themselves. It only contains the list and URLs needed to find, choose, and install them.

## Available skills

### digitarq-get
Description: Downloads high-resolution page images from Digitarq / the Portuguese National Archive (Torre do Tombo).
Repository: https://github.com/joaquimrcarvalho/digitarq-get
Skill: `.`
License: MIT

### bnp-digital-download

Description: Downloads high-resolution page images from the Portuguese National Digital Library (purl.pt / permalinkbnd.bnportugal.gov.pt).
Repository: https://github.com/joaquimrcarvalho/get-bnd-purl
Skill: `skills/bnp-digital-download`
License: MIT

## For agents

Read this README and return the list of skills with name, description, URL, skill path, and license.
Always ask which one the user wants to install/use.
Do not invent skills, URLs, or paths that are not in this index.

If the user writes something like:
> Show me which additional skills are available to use at this address: <repository URL>

then return the skill list above and ask the user to choose.

## Installation
Clone the repository and use the folder defined in Skill.
Example: git clone --depth 1 <repository_url>

## Updating
Publish the new skill in an open GitHub repository.
Add it to this README.
Commit and push.
