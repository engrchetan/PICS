# PICS
Pro In Calculating Stream (P.I.C.S) :: Work in Progress

GOAL
Define a simple general API to consume unbound stream of data and produce configured calculation outputs.

APPROACH
* Consume unbouned stream of data filtering pre-configured required data events only
* Allow definition of calculations in a connected/disconnected graph which can consume external data events and internal calculated values as intermediate data events. These dependent series of calculation would form parent child relationship.
* Calculation framework should reduce internal scheduling/blocking overheads 
