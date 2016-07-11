birdcall
========
A library for the various lettered combinators.

This library supports experimentation of programming with basic combinatory
combinators. The full list is found below λogic

combinators
-----------
====== ==================== ==============
letter bird alias           implementation
====== ==================== ==============
B       Bluebird             λabc.a(bc)
B1      Blackbird            λabcd.a(bcd)
B2      Bunting              λabcde.a(bcde)
B3      Becard               λabcd.a(b(cd))
C       Cardinal             λabc.acb
D       Dove                 λabcd.ab(cd)
D1      Dickcissel	         λabcde.abc(de)
D2      Dovekies	           λabcde.a(bc)(de)
E       Eagle	               λabcde.ab(cde)
Ê       Bald Eagle           λabcdefg.a(bcd)(efg)
F       Finch                λabc.cba
G       Goldfinch            λabcd.ad(bc)
H       Hummingbird	         λabc.abcb
I       Identity Bird        λa.a
J       Jay                  λabcd.ab(adc)
K       Kestrel (True)	     λab.a
L       Lark                 λab.a(bb)
M       Mockingbird          λa.aa
M2      Double Mockingbird   λab.ab(ab)
O       Owl                  λab.b(ab)
Q       Queer Bird           λabc.b(ac)
Q1      Quixotic Bird        λabc.a(cb)
Q2      Quizzical Bird       λabc.b(ca)
Q3      Quirky Bird          λabc.c(ab)
Q4      Quacky Bird          λabc.c(ba)
R       Robin                λabc.bca
S       Starling             λabc.ac(bc)
T       Thrush               λab.ba
U       Turing               λab.b(aab)
V       Vireo                λabc.cab
W       Warbler	             λab.abb
W1      Converse Warbler     λab.baa
Y       Why Bird             λa.a(la)
I*      Identity Bird 1R     λab.ab
W*      Warbler 1R           λabc.abcc
C*      Cardinal 1R          λabcd.abdc
R*      Robin 1R	           λabcd.acdb
F*      Finch 1R             λabcd.adcb
V*      Vireo 1R	           λabcd.acbd
I**     Identity Bird 2R     λabc.abc
W**     Warbler 2R           λabcd.abcdd
C**     Cardinal 2R          λabcde.abced
R**     Robin 2R             λabcde.abdec
F**     Finch 2R             λabcde.abedc
V**     Vireo 2R             λabcde.abecd
KI      Kite                 λab.b
KM      Konstant Mocker      λab.bb
CKM     Crossed K Mocker     λab.aa
======= ==================== ==============

* = once removed
** = twice removed
