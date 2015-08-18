# GitHarvester


  _____ _ _     _    _                           _
 / ____(_) |   | |  | |                         | |
| |  __ _| |_  | |__| | __ _ _ ____   _____  ___| |_ ___ _ __
| | |_ | | __| |  __  |/ _` | '__\ \ / / _ \/ __| __/ _ \ '__|
| |__| | | |_  | |  | | (_| | |   \ V /  __/\__ \ ||  __/ |
 \_____|_|\__| |_|  |_|\__,_|_|    \_/ \___||___/\__\___|_|

Version 0.5
By: @metacortex of @dc801

usage: githarvest.py [-h] [-r CUSTOM_REGEX] [-s CUSTOM_SEARCH] [-v] [-w WRITE_FILE]

This tool is used for harvesting information from GitHub. By default it looks
for code with the filename of 'wp-config.php' and pulls out auth info

optional arguments:
  -h, --help        show this help message and exit
  -r CUSTOM_REGEX   Custom regex string
  -s CUSTOM_SEARCH  Custom GitHub search string
  -v, --verbose     Turn verbose output on
  -w WRITE_FILE     Write results to a file
  
  
  Git Harvester also has support for custom search terms and regex strings. If you wanted to pull out just passwords from wp-config.php files found on GitHub you can use the following command:
  
  $ githarvest.py -r "define\(\'DB_PASSWORD.*;" -s "filename:wp-config.php"
