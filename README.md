# FMR

## TODO

* Implement Router
* Explore cell movement stategy

## Done

* Write and debug parser

## Ideas

* Net Optimizer
  * Graph --[MST]-> Tree --[Cut-leave]-> Core Tree
* Ripup and Reroute
  * from center to edge, k \times A*
* Cell Movement
  1. choose multiple pins, which are bad according to "optimal region"
  2. use net to choose "distant pins"