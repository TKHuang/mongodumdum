## mongodumdum
Dump your MongoDB in a range of days

It's a nodejs script, please install nodejs first.

## How to use
```
Usage: mongodump [options]

  Options:

    -h, --help                                              output usage information
    -V, --version                                           output the version number
    -u, --user <user>                                       mongo user
    -p, --password <password>                               password
    -d, --database <database>
    -c, --collection <collection>
    -ad, --authenticationDatabase <authenticationDatabase>  default is admin
    -s, --start //2012/06/01 <start>                        which time do you want to start
    -e, --end //2012/12/31 <end>                            which time do you want to end
    -h, --host <host>
    -o, --output <output>                                   choose your path to save file
```
ex:
```shell
./mongodump -u root -p yourpassword -h localhost:27017 -s 2015/01/01 -e 2015/10/01
 ```
