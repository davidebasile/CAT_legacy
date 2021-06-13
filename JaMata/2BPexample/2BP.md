2 Buyers protocol:
the following files (extension .data) describes the CA
	- B1 the buyer 1
	- B2 the buyer 2
	- S the seller
	- B1xB2xS  	the product computed by the tool
	- KS(B1xB2xS) the most permissive controller for strong agreement computed by the tool
				  this CA has mixed choice states and does not enjoy branching condition

The mapping from number to actions is:

1 : price
2 : quote1
3 : contrib
4 : ok
5 : nop
6 : delivery
7 : quote2

the corresponding requests have negative sign
