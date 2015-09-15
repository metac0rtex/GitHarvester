# GitHarvester
<pre>
$ ./githarvest.py -h

  _____ _ _     _    _                           _
 / ____(_) |   | |  | |                         | |
| |  __ _| |_  | |__| | __ _ _ ____   _____  ___| |_ ___ _ __
| | |_ | | __| |  __  |/ _` | '__\ \ / / _ \/ __| __/ _ \ '__|
| |__| | | |_  | |  | | (_| | |   \ V /  __/\__ \ ||  __/ |
 \_____|_|\__| |_|  |_|\__,_|_|    \_/ \___||___/\__\___|_|

Version 0.7.1
By: @metacortex of @dc801

usage: githarvest.py [-h] [-d DIRECTORY] [-o ORGANIZE] [-r CUSTOM_REGEX]
                     [-s CUSTOM_SEARCH] [-u] [-v] [-w WRITE_FILE]

This tool is used for harvesting information from GitHub. By default it looks
for code with the filename of 'wp-config.php' and pulls out auth info

optional arguments:
  -h, --help        show this help message and exit
  -d DIRECTORY      Download results to a specific directory
  -o ORGANIZE       Organize results by 'new', 'old', 'best', or 'all'
  -r CUSTOM_REGEX   Custom regex string
  -s CUSTOM_SEARCH  Custom GitHub search string
  -u, --url         Output URL of found object
  -v, --verbose     Turn verbose output on. This will output matched lines
  -w WRITE_FILE     Write results to a file
</pre>
