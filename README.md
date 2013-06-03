curlie
------

A repository for storing bash scripts to facilitate using curl with browser cookies.

pre-reqs
--------

A mac running curl/sqlite and standard install of firefox, chrome or safari browser.  
Note: The executable files (below) must be executable!

usage
-----

./curlie -c domain:port/path  # chrome web browser -> curl {cookies} domain:port/path  
./curlie -f domain/path       # firefox web browser -> curl {cookies} domain/path  
./curlie    # default options are: chrome, localhost:3000 and no path specified will redirect to root  

Browser Specific:  
  ./churl domain:port/url_path  
  ./furl domain:port/url_path  
  ./surl domain:port/url_path  
