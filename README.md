# Radio anaconda recipes
Bunch of files to install common radio interferometry software on Mac-OSX 10.12+ (x64) and Linux (x64, tested on SL7)

### Usage:

`conda create --name <env> --file <file>`

where you replace `<env>` with name of an environment e.g. `kittens` and `<file>` with a file from this repository

You can enter that environment and use that software using `source activate <env>` and leave that environment using `source deactivate`

### Current recipes
* wsclean=2.4.0 & 2.5.0 (<https://sourceforge.net/p/wsclean/wiki/Home/>)
* aoflagger=2.9.0 (without rfigui at the moment) (<https://sourceforge.net/p/aoflagger/wiki/Home/>)
