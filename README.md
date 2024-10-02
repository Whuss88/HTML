# html and git workflow

## HTML

structure of your webste
browser made of elements

-tags (parts w/o the text)(the outside)
 -name
 -opening
 -optional closing
-structure
 - html contains all elements (usually the head or parent element)
 -head info that user will not see (metadata)
 -body info that the user will see
 -title displayed in broswer tab
    
-formatting rules
 -html files should be named in lowercase & seperated by hyphens
 -convert tabs to 2 spaces
 -avoid leaving trailing spaces(the spaces that come @ the end)
 -elements inside of other elemenets should be indented one time

- semantic elements - named based on what inside of them
 -header - top of the page, contains logos or inductory content, status/login bar, navi ... its the top bun
 -main - between header and footer (main content, products, etc) ... its the meat inbetween the burger
 -footer - contact info, special links, back to top link... its the bottom bun of every page
 -H1 thru H6 -- biggest thru smallest, *h1 is bigger than "header"... bigger the # the smaller the font 
 -nav -> how to navi the site
 -a -> hyperlink (anchor tag)
 -attributes -> (href,target,type, see web) gives addition info for the element (links, etc)
 - article/section -> <article> gives structure/organization
  -image 
  -ol/ul -> ordered list which is numbered/ unorder shows bullet points
  -p tags -> paragraph

non-semantic elements
  -divs-> avoid 
  -span-->???

advantages of semantic html
  -search engine optimization (SEO)
  -screen readers
  -working w humans 

comments do not display in the browser
ctrl/cmd / for commenting gotta highlight


in terminal command --- start filename.html to bring up in browser

-troubleshooting & debugging
  -test as you go start with 5-10
  -most common when missing closing tag
  -are there spelling errors
  -commentout certain parts of the code to find the broken code

Chrome Dev tools
  -function f12 or right clock & inspect
  -microsoft edge also has the same tools

Git Hub Workflow
  -Merge conflicts - happens when 2 people change the same file without pushing/pulling the changes first
  -Branches
    -git checkout -> change branches
      - -b <feature-name> -> create a new branch allows working on a new feature without affecting the main
      - very very very important process for working in groups
  -Pull request 
    - allows for 2nd set of eyes to check code for bugs
    -1st person - github - make a pull request
    -2nd perspn - github - review the commits on the pull
    Request - approve and merge or tell person 1 to make some changes
    