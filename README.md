# Warning


Alex Miller points out that he is working on an official installer for windows and asks that my project clearly differentiate itself from the official installers.

see https://groups.google.com/d/msg/clojure/nw66LtqsaWU/rMv1GWEfDAAJ)

I am doing this:

THIS IS NOT THE OFFICIAL  installer for clojure and cli tools on windows



# Clojure installer and CLI tools for 	windows (* NON-OFFICIAL*)

this is  for installing the clojure  CLI tools on windows 
see cli https://clojure.org/guides/getting_started


## Installation
1. Download the latest release from https://github.com/frericksm/clj-windows/releases
2. Extract it to some `<local-path>`
3. Execute `<local-path>`\windows-clojure-tools-1.9.0.391\install.exe


## Build from source
### Prerequisites
1. Install https://golang.org/
2. install maven https://maven.apache.org/

### Steps 
1. Checkout https://github.com/frericksm/clj-windows.git
2. change directory to clj-windows/clojure
3. run "go build "
4. change directory to clj-windows/clj
5. run "go build "
6. change directory to /clj-windows/install
7. run "go build"
8. change directory to /clj-windows
9. run "mvn package"
10. see clj-windows/target for build results  an follow the installation task above

