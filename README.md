# http_load

My modification for http_load  http://www.acme.com/software/http_load/





    $ http_load -r 100 -s 60 urls 

    5997 fetches, 24 max parallel, 2.79964e+07 bytes, in 60 seconds
    4668.4 mean bytes/connection
    99.95 fetches/sec, 466607 bytes/sec
    msecs/connect: 4.76659 mean, 1256.03 max, 1.55 min
    msecs/first-response: 27.1605 mean, 313.85 max, 6.724 min
    5976 bad byte counts
    HTTP response codes:
      code 200 -- 5997

    Percentage of the requests served within a certain time (ms)
     50%    22
     66%    25
     75%    27
     80%    29
     90%    37
     95%    51
     98%    73
     99%    93
     100%   313 (longest request)
