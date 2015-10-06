# histo

## demo

    $ histo -xn
    demo: distr = normal, transf = (none)
    num_blanks = 0
           (-2.6357, -2.1251)    ***
           (-2.1251, -1.6145)    ****
           (-1.6145, -1.1039)    *****************
           (-1.1039, -0.5933)    ***********************
           (-0.5933, -0.0827)    ********************************************
            (-0.0827, 0.4279)    **********************************************
             (0.4279, 0.9385)    *******************************
             (0.9385, 1.4491)    ******************
             (1.4491, 1.9597)    *******
             (1.9597, 2.4703)    *****

## help

    $ histo -h
    usage: histo [-h] [-b [num_bins]] [-f [l/s/n]] [-o [1/0]] [-x [n/e/u]]
                 [infile]
    
    quick cmd-line histogram plotter
    
    positional arguments:
      infile         input file object
    
    optional arguments:
      -h, --help     show this help message and exit
      -b [num_bins]  number of bins
      -f [l/s/n]     nonlinear transf to apply (l = log, s = sqrt, n = negative
                     reciprocal)
      -o [1/0]       omit header row (ignored in demo mode)
      -x [n/e/u]     run with demo data (n = normal, e = exp, u = unif)

