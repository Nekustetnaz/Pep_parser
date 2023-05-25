# PEP parsing service

## Description
This project parses information about PEP documentation from the Python website
It has several modes and output options.

## Run service:
To run the service, use the command with preferred options:
```
python main.py [mode] [options]
```
The service has the next modes:
```
whats-new  # shows the last changelog for the latest Python release
latest-versions  # shows statuses of the latest Python versions
download  # downloads an archive containing all the documents for the version of Python
pep  # shows status information for the all PEP documents
```

The service has the next options:
```
-c | --clear-cache  # clears the cache before parsing precess
-o pretty | --output pretty  # prints the result in an attractive ASCII form
-o pretty | --output file  # write the result in a .csv file
```

## Technologies
Python 3
BeautifulSoup4

## The author of the project
Anton Akulov - https://github.com/Nekustetnaz
