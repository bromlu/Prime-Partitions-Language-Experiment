# Prime-Partitions-Language-Experiment

This is a project where I solve a problem in various different languages in order to better understand programming paradigms.

The problem I am solving is to find all the prime partitions of any number. A prime partition is defined as follows:

A prime partition of a positive integer n>=2 is a set of primes p which sum to n. For example, there are three prime partitions of 7:
```math
7 = 7
2 + 5 = 7
2 + 2 + 3 = 7
```

## Example input/output

```bash
Please enter a number (enter non-number to exit): 21
2 + 3 + 5 + 11
2 + 19
3 + 5 + 13
3 + 7 + 11
```

## Ocaml

### Install

Install instructions on Ocaml's [official website](http://www.ocaml.org/docs/install.html).

### Run

```bash
$ ocaml ocaml.ml
Please enter a number (enter non-number to exit):
```

## Perl

### Install

Install instructions on Perl's [official website](https://www.perl.org/get.html).

### Run

```bash
$ perl perl.pl
Please enter a number (enter non-number to exit):
```

## Ada

### Install

Install instructions on Ada's [official website](https://www.adacore.com/download).

Use gnatmake to compile the code.

```bash
$ /Users/<username>/opt/GNAT/2018/bin/gnatmake primeada.adb
gcc -c primeada.adb
gnatbind -x primeada.ali
gnatlink primeada.ali
```

### Run

```bash
$ ./primeada
Please enter a number (enter non-number to exit):
```

## Prolog

### Install

Install instructions on Prolog's [official website](http://www.swi-prolog.org/download/stable).

### Run

Run the file using swipl.

```bash
$ swipl prolog.pl
Welcome to SWI-Prolog (threaded, 64 bits, version 7.6.4)
SWI-Prolog comes with ABSOLUTELY NO WARRANTY. This is free software.
Please run ?- license. for legal details.

For online help and background, visit http://www.swi-prolog.org
For built-in help, use ?- help(Topic). or ?- apropos(Word).

1 ?- prime_partition(21).
2 + 3 + 5 + 11
true ;
2 + 19
true ;
3 + 5 + 13
true ;
3 + 7 + 11
true ;
false.
```

## Python

### Install

Install instructions on Python's [official website](https://www.python.org/downloads/).

### Run

```bash
$ python3 python.py
Please enter a number (enter non-number to exit):
```

## Rust

### Install

Install instructions on Rust's [official website](https://www.rust-lang.org/tools/install).

Compile using rustc.

```bash
$ rustc rust.rs
```

### Run

```bash
$ ./rust
Please enter a number (enter non-number to exit):
```

## Scheme

### Install

Install instructions for racket are on their [official website](https://docs.racket-lang.org/pollen/Installation.html).

### Run

```bash
$ racket scheme.scm
Please enter a number (enter non-number to exit):
```
