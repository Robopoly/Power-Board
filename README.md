# Power board

![Power board](https://raw.github.com/Robopoly/Power-Board/master/power.png)

The Power board is intended to work with the EPFL Robotics club robotics platform [PRismino](https://github.com/Robopoly/PRismino) and the [Robopoly shield](https://github.com/Robopoly/Robopoly-Shield).

## Characteristics

The Power board provides a constant 5V up to 3A. It features a standard 10 pin female rack to connect components and an on-off switch.

There's a footprint in parallel with the switch to add a switch if the one on the board isn't accessible.

A LED indicates the power state of the board, like with the switch there's a footprint to solder the wires of a LED away from the board, but if it's used the on-board LED has to be removed.

The regulator is the [TPS62133](http://www.ti.com/product/tps62133) step-down converter, is accepts input between 5V and 17V and features short-circuit protection. The circuit on the board is the same as on figure 43 in the datahsheet (page 24).

## Assembly

The assembly of the PRismino is [documented on the Robopoly's website](http://robopoly.epfl.ch/prisme/assemblage).

## Licence

The Robopoly shield is published under [Creative Commons Attribution license](http://creativecommons.org/licenses/by/3.0/).

[![Creative Commons License](http://i.creativecommons.org/l/by/3.0/88x31.png)](http://creativecommons.org/licenses/by/3.0/)
