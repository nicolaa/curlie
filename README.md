curlie
------

A repository for storing bash scripts to facilitate using curl with browser cookies.

pre-reqs
--------

A mac running curl/sqlite and standard install of firefox, chrome or safari browser.  
Note: The executable files (below) must be executable!

usage
-----

./curlie {browser} {url} {curl options}  

Examples:    
  ./curlie -c domain:port/path -d {data} # uses chome cookie store with curl -d option  
  ./curlie -f domain/path                # uses firefox cookie store 
  
  ./curlie      
  # default options are: chrome, localhost:3000 and no path specified will redirect to root  

Browser Specific:  
  ./churl {url} {curl options} # chrome    
  ./furl {url} {curl options}  # firefox  
  ./surl {url} {curl options}  # safari  
