randmtzig
=========

MLton bindings for an implementation of the MT19937 random number
generator with Marsaglia and Tang's Ziggurat algorithm to generate
random numbers from a non-uniform distribution.

MLton code Copyright 2013 Ivan Raikov.

randmtziglib.c Coded by Takuji Nishimura and Makoto Matsumoto.
This is a faster version by taking Shawn Cokus's optimization,
Matthe Bellew's simplification, Isaku Wada's real version.
David Bateman added normal and exponential distributions following
Marsaglia and Tang's Ziggurat algorithm.

Copyright (C) 1997 - 2002, Makoto Matsumoto and Takuji Nishimura,
Copyright (C) 2004, David Bateman

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:
   
    1. Redistributions of source code must retain the above copyright
       notice, this list of conditions and the following disclaimer;.
    2. Redistributions in binary form must reproduce the above copyright
       notice, this list of conditions and the following disclaimer in the
       documentation and/or other materials provided with the distribution.
    3. The names of its contributors may not be used to endorse or promote 
       products derived from this software without specific prior written 
       permission.
