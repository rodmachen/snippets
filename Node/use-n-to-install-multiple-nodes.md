# Use N to install multiple versions of Node

First, make sure some version of Node is installed (mainly for the accompanying NPM capabilities.) I suggest using [Homebrew](http://brew.sh/).

    brew install node

Next, install n. (Use sudo if necessary.)

    npm install -g n

With n installed, there are several ways to install various versions of Node:

    n lts
    n stable
    n 0.12.10
    
To change versions, simply call n and arrow up and down to choose:

    n

      0.12.10
    ο 4.2.1
      5.6.0

## Backstory

I found myself needing an older version of Node for work and came upon this solution.

With a fresh install, I had gone with Node 5, but this project was using 0.12. The probably actually wasn't with Node itself, but with NPM. The newest versions of Node use NPM 3, but I needed NPM 2 due to its non-flattened folder structure, which this project used. After installed 0.12.10, I moved over to it, and had the NPM version I needed. 

### Reference

[github.com/tj/n](https://github.com/tj/n)
