# Pre-trained dictionaries to compress data in Eth database 

It initially trained on some tables of https://github.com/ledgerwatch/turbo-geth project. Shows 4x compression ratio with 50 microsecond of encode/decode speed (iterate over 10M receipts and compress each one takes 3min, decompress - 1min)

Right now it contains only dictionaries for library http://facebook.github.io/zstd/ - but it may change if we find better library

More info about Dictionary Compression: https://en.wikibooks.org/wiki/Data_Compression/Dictionary_compression

