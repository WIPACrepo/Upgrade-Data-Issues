# Introduction

This repository is an initial landing zone for issues discovered with Upgrade data.  These issues will be triaged and assigned TBD (likely Monday Operations and/or Thursday Commissioning calls).

## Creating New Issues

Create a new issue with sufficient evidence to identify it in data and/or recreate it.  For specific instances of problems, include at least:
* Run number
* Event number (exclude if using hitspool data)
* Module (string-position-channel PLUS ICM ID)
For general problems, try to include an example instance.  For bad OMs/channels, include `string-position-channel (ICM ID)` in the issue title. Optionally assign tags and delegate assignees.

## Triaging Issues

Identify the appropriate systems affected, then finalize labels and assignee delegations.  Add the 'TRIAGED' label.

## Closing Issues

Issues should be closed when fully resolved, meaning the issue was fixed, found to be a duplicate, found unreproducible, or moved to a different issue tracker (e.g. IceTray).  When closing the issue, add a comment describing the resolution and, if moving to a different issue tracker, a link to the new issue.
