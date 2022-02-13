# RDJ Voting

Automatic voting for [RDJ](https://rdj.mg/).

RJD Automatic Voting, If you don't add any arguments, the script will vote one time for all the songs available on the site

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install rdj-voting-mgs.
```bash
pip install rdj-voting-mgs
```

## Usage
``` optional arguments:
  -h, --help            show this help message and exit
  -v, --verbose         increase output verbosity
  -n NUMBER, --number NUMBER
                        number of votes to cast
  -l LIST, --list LIST  song list, recoverable on the voting link on the site
  -i IDSONG, --idSong IDSONG
                        choose the id of the song to vote, if specified, the other filters are not taken into account

  -r, --random          make random votes
  -c CHOICE, --choice CHOICE
                        number of songs to vote randomly
```
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[GPL-3.0](https://choosealicense.com/licenses/gpl-3.0/)