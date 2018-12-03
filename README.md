# Bar Graph

Using stats from Wikipedia, I created a JSON object for some notable players from the Liverpool Team between 2007 and 2010, compiling stats just as their number of appearances and goals scored.

The bar is a compilation of divs. Each bar is a div representing the maximum value of the stat (calculated via JavaScript) and contains another div whose height is calculated based on the stat vs the maximum stat.

The rest is basically JavaScript to change the dataset between Years, and between Goals and Appearances.

*Note: This does not work very well in Safari and IE.*
