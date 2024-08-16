Div for number of coins
=
Use // (Div) operator to determine the number of coin to give.
example:
```
  #You could fully fill 2 egg cartons if you had 28 eggs.
  egg_count = 28
  egg_carton_size = 12
  egg_cartons_needed = egg_count // egg_carton_size   # result: 2
```


Mod for coins left over
=
Use % (mod) operator to determine the amount of change stil owed after giving them some number of coin.
example:
```
  #You would have 4 eggs left over after filling 2 egg cartons if you had 28 eggs.
  egg_count = 28
  egg_carton_size = 12
  egg_left_over = egg_count % egg_carton_size    # result: 4
```