[<- Back](index.md)

## <a name="node"></a>Node.js

Node.js is an open-source, cross-platform JavaScript run-time environment for executing JavaScript code server-side. Historically, JavaScript was used primarily for client-side scripting, in which scripts written in JavaScript are embedded in a webpage's HTML, to be run client-side by a JavaScript engine in the user's web browser. Node.js enables JavaScript to be used for server-side scripting, and runs scripts server-side to produce dynamic web page content before the page is sent to the user's web browser.

Consequently, Node.js has become one of the foundational elements of the "JavaScript everywhere" paradigm,[5] allowing web application development to unify around a single programming language, rather than rely on a different language for writing server side scripts. (source: [Wikipedia](https://en.wikipedia.org/wiki/Node.js))

### Installing Node.js

Here at CodeClub we are using the LTS version (6.11.2) of Node.

Quick Install:
- MacOS
  - Homebrew: `brew install node`
  - Download:
    - [tar.xz](https://nodejs.org/dist/v6.11.2/node-v6.11.2-darwin-x64.tar.gz)
    - [.pkg](https://nodejs.org/dist/v6.11.2/node-v6.11.2.pkg)
- Linux
  - Debian/Ubuntu:
    1.  `curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -`
    2. `sudo apt-get install nodejs`
    3. `sudo apt-get install -y build-essential`
  - Arch:
    - `pacman -S nodejs npm`
  - Fedora:
    1. `curl --silent --location https://rpm.nodesource.com/setup_6.x | sudo bash -`
    2. `sudo yum -y install nodejs`
  - Download: [tar.xz](https://nodejs.org/en/download/) ([64-bit](https://nodejs.org/dist/v6.11.2/node-v6.11.2-linux-x64.tar.xz))([32-bit](https://nodejs.org/dist/v6.11.2/node-v6.11.2-linux-x86.tar.xz))
- Windows
  - Chocolatey: `cinst nodejs.install`
  - Scoop: `scoop install nodejs`
  - Download: [.msi](https://nodejs.org/en/download/) ([64-bit](https://nodejs.org/dist/v6.11.2/node-v6.11.2-x64.msi))([32-bit](https://nodejs.org/dist/v6.11.2/node-v6.11.2-x86.msi))
    - [How to install for windows](http://blog.teamtreehouse.com/install-node-js-npm-windows)

Source:
- [Installing Node.js via package manager](https://nodejs.org/en/download/package-manager/#windows)
    <br>
    [<- Back](index.md)
