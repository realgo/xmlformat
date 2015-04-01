# xmlformat

This program reads XML from stdin, strips out any comments, and sorts the
order of children nodes and attributes.  Each tag is on it's own line, and
attributes of tags are also sorted.  The results are written to stdout.

The goal is to produce a format that can easily be run through diff to see
what has changed from one XML file to another.
