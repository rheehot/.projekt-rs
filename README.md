.projekt Solver
===============

# How to use
```
> cargo run
      .-' Y       O '-.
O .-'   |           |    '-.
 |      |           |       | X
 |  YZ  |           |  XZ   |
 |    .-'           '-.     |
 |.-'       .-'-.   Z    '-.|
 Z     .-'         '-.
        '-.       .-'
            '-.-'
Put XZ plain (# for black, _ for white, double return to end)
_***_
_*_*_
_***_
_*___
_*___

Put YZ plain (# for black, _ for white, double return to end)
*____
*__*_
****_
*__*_
*____

     y + · · · · +
      / · · · · ·
     / · · · · ·
    / · · · · ·
   # · * * * ·
z 0---#-#-#-+ x
  |  y + · · · · +
  |   # · * · · ·
  |  / · · · · ·
  | / · · · · ·
  |# · * · * ·
z 1---#---#-+ x
  |  y + · · · · +
  |   # · * · · ·
  |  # · * · · ·
  | # · * · · ·
  |# · * * * ·
z 2---#-#-#-+ x
  |  y + · · · · +
  |   # · * · · ·
  |  / · · · · ·
  | / · · · · ·
  |# · * · · ·
z 3---#-----+ x
  |  y + · · · · +
  |   / · · · · ·
  |  / · · · · ·
  | / · · · · ·
  |# · * · · ·
z 4---#-----+ x
```