---
layout: page
title: About
permalink: /about/
---

This website was built by Ryan Siu in the 2017-2018 season using Jekyll's Minima theme.

It is intended for use during competition to track teams' performances throughout the competition. Statistics that are not made publicly available until after the competition are included in match information.

## Usage

### Matches

This website is designed to make updating match information simple.

To start, copy the `2018-01-13-example.markdown` file and rename it
```
<yyyy>-<mm>-<dd>-match<##>.markdown
```
replacing the fields inside angle brackets with the specified information. Make sure that this file remains in the same directory, inside `_posts`. For playoff matches, `match<##>` can instead be `semis<##>` or `finals<##>` as appropriate.

Replace each field between the `---` marks at the beginning and end of the file with the appropriate information. For example, replace `blue_teams: "310, 479"` with `blue_teams: "123, 456, 789"` if teams `123`, `456`, and `789` are on the blue alliance for a match.

The `author` of the post should be the name of the scouter.

Any additional information can be written under the `### Comments` section as plaintext.

When you are finished with editing the file, commit it and push to GitHub to be deployed to the live site.

### Schedule

This page should be updated with the match schedule for our team. Edit the markdown table to reflect the schedule and bold our team number for each of our matches.
