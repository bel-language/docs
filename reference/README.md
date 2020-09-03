## Data types

The four fundamental types:

* symbol
* pair
* char
* stream

Also the following predefined predicates:

* pair
    * proper
        * string
    * function
    * number
        * real
            * int
                * whole
                * pint
                * even
                * odd
* char
    * digit
    * breakc
    * signc
    * intrac
* simple

## Primitive functions

* id
* join, car and cdr
* type
* xar and xdr
* sym
* nom
* wrb and rdb
* ops and cls
* stat
* coin
* sys

## Special forms

* quote
* if
* where
* dyn
* after
* ccc
* thread
* (apply)

## Built-in functions

### General functions, for any value

no, atom, uvar, in, idfn, is, wait

### Functions on pairs

car, cdr, cadr, cddr, caddr, caris

### Functions on lists

all, some, reduce, map, proper, string, mem, find, begins, hug, keep, rem,
rev, snap, udrop, foldl, foldr, pairwise, fuse, match, split, pos, len,
runs, dups, tail, dock, last, drop, nth, first, cut, adjoin, dedup, insert,
sort, max, min

### Functions for building lists

cons, append, snoc, list, consif

### Functions on (kvs) alists

get, put, gets

### Functions on unary numbers

i<, i+, i-, i\*, i/, i^, factor, common

### Functions on rationals

r+, r-, r\*, r/

### Functions on signed rationals

sr+, sr-, srinv, sr\*, sr/, srrecip, sr<, srnum, srden, simplify

### Functions on complex numbers

c+, c\*

### Functions on numbers

litnum, number, numr, numi, rpart, ipart, real, inv, abs, buildnum,
recip, +, -, \*, /, inc, dec, floor, ceil, mod, ^w, clog2, randlen,
rand, even, odd, round

### Functions on chars

charn, nchar, whitec, digit, breakc, signc, intrac

### Functions on strings

tokens, prs

### Functions on queues

newq, enq, deq

### Functions on arrays

array, aref

### Functions on tables

table, tabref, tabloc, tabrem

### Functions on templates

inst, readas

### Comparisons

=, ~=, <, >, list<, bin<, >=, <=

### Predicates

symbol, pair, char, stream, proper, string, isa, function, real, int, whole,
pint, whitec, simple, digit, breakc, signc, intrac, source, even, odd

### Function-building functions

isa, con, compose, combine, cand, cor, of, upon, yc, flip, part, trap, only

### I/O functions

open, close, stat, peek, rdc, bitc, readall, load, readas

### Functions used in the evaluator

literal, variable, bel, mev, sched, ev, vref, inwhere, lookup, binding,
sigerr, evmark, formfn, parameters, if2, dyn2, evcall, evcall2, applym,
applyf, applylit, okenv, okstack, okparms, oktoparm, applyprim, applyclo,
pass, typecheck, destructure, applycont, protected

### Functions used in the reader

read, saferead, rdex, eatwhite, charstil, rdlist, rddot, hard-rdex, rdwrap,
rddelim, rdtarget, rdword, parseword, parsenum, validi, validr, validd,
parsei, parsesr, parsed, parseint, charint, parset, parseslist, parsecom,
parseno

### Functions used in the bquote expander

bqex, bqthru, bqexpair, spa, spd

### Functions used in the printer

print, namedups, cells, prc, ustring, prstring, presc, prsimple, prsymbol,
prnum, rrep, irep, intchar, prpair, prelts, prn, pr, prnice

## Built-in macros
## Built-in constants
## Reader syntax
## Built-in virtual function types
## Details of the evaluator
## Errors
