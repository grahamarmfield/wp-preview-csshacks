# wp-preview-csshacks
A CSS file that you can add to your WordPress theme. 

It flags up potential accessibility issues when your content authors preview the post or page that they have just added or amended. 

Site visitors who are not logged in will not see the potential issues.

Currently contains checks for:
* Images with empty alt attributes
* Links that open new windows
* Links that have a title attribute
* images that have no alt attribute
* images that have the title attribute
* svg files that don't have role="img"
* inline svgs that don't have role="img" 
* empty headings
* empty links
* empty buttons
* empty headings
* empty table header cells
* empty table data cells
