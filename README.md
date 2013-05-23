A branch of TreeMappa (http://code.google.com/p/treemappa)

Released under the LGPL license (as is the original code).

This port was based on the r9 revision and concentrated on rewriting SVG output to add a some different uses/features for [visualizations produced at the Oxford Internet Institute]](http://www.oii.ox.ac.uk/vis/?tool=TreeMappa).

This port is focused on running from terminal/command line. Example forthcoming...

Changes from upstream include:

*Remove quotations surrounding fields in CSV files (Still todo: do not split on a comma within a quoted field)
*Allow creation of svg without display of panel/user interaction
*SVG output changes
**Allow user to specify font to be used
**Use rect instead of polygon in svg
**Allow for rounded corners on rect
**Restrict font size to one of three sizes
**Allow user option to hide labels that would be smaller than smallest of three font sizes (LabelAll option)
**Allow user to specify 'base' font size
**Place all labels in the lower-left corner of leaf nodes
**Allow for branch nodes to have a fill color (svg only)
**Started on allowing a strange option to create treemaps with leaves as circles, but this is incomplete and should be removed. (And not something I personally like)


