```
    $> ./downloadrecentxml
    $> ./convertxml -h
        usage: convertxml [-h] [-t {json,prettyjson,yaml,prettyyaml}] [-f FILE]

        optional arguments:
          -h, --help            show this help message and exit
          -t {json,prettyjson,yaml,prettyyaml}, --to {json,prettyjson,yaml,prettyyaml}
                                Specify the format for conversion to.
          -f FILE, --file FILE  Specify the input xml, if omitted will search for the
                                latest in a subdirectory named by version number.


    $> ./convertxml --to prettyyaml > my_cf_standard_names.yaml
```
