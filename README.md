# Law Identifier

A collection of regular expressions to identify references to state laws within the United States.

There is one file for each state, containing both a regular expression and a textual description of what that regular expression does, and how it was derived. These are, by design, naïve regular expressions—they make no attempt to recognize that `§ 18.2-100–18.2-105` describes a range of six sections in all, but instead would only pick up on `§ 18.2-100` and `§ 18.2-105`.

## TO DO
* Create a JSON file containing all PCREs, with the state's abbreviation serving as the key.
