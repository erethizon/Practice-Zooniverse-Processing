---
editor_options: 
  markdown: 
    wrap: 72
---

## Overview

This repo is for working up the code to take a giant .csv file
downloaded from our [Zooniverse
Project](https://www.zooniverse.org/projects/barthelmess/north-country-wild)
so that we can extract the correct subset of data and can then determine
the ID of each set of images.

The .csv files created from the Zooniverse are much larger than github
likes to track, so we will use the `tidyverse` googledrive package to
access the csv from a google drive.

That way, we can all be using the same .csv file, but we don't need to
worry about having trouble with our github repo.
