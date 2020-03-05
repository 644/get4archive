# Description
Very fast archive image finding tool thanks to GNU Parallel. Few dependencies, and works with all boards!

# Installation
```
wget https://raw.githubusercontent.com/644/get4archive/master/get4archive; chmod u+x get4archive

Usage: ./get4archive [options]
    -ss       Page number to start from
    -to       Amount of pages to search
    -itype    Image file type. e.g. wgpj selects webm,gif,png,jpg
    -sdate    Start date to search from
    -edate    End date to search to
    -min      Minimum filesize. e.g. 20.5K
    -max      Max filesize. e.g. 3.1M
    -sub      Subject to search for
    -s        Text to search for
    -f        Path to save folder
    -b        Board to search
```

# Dependencies
parallel, jq, bash >4.0+

# License
MIT
