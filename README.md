# score

## About
Get the score information
Score is a simple python script for viewing scores information. Information is scraped from [**livescore.com**](http://www.livescore.com) 
It is written in python and needs `python3`.

## Dependency
- `beautifulsoup` is used to parse the scraped html.
    ```bash
    pip3 install beautifulsoup4
    ```

- `pip3` is used for install python packages
    ```bash
    sudo apt-get install python3-pip
    ```

## Usage
livescore can be run from terminal by executing the python script **livescore.py**.  
The script can be used directly or with optional parameters.

#### optional parameters
```bash
livescore.py [-s]/[--search] <searchname>
```

*`-s`* or *`--search`*
search options for searching according the club/team name specified

*`-h`* or *`--help`*
help options
