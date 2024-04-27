ASSIGNMENT
Your manager noticed that there's a lot of repetitive code in the "Age of Dragons" code base. She asked you to update the fight_soldiers function so that the DPS (damage-per-second) calculation is only written once.

Notice how these two lines are practically identical:

soldier_one_dps = soldier_one["damage"] _ soldier_one["attacks_per_second"]
soldier_two_dps = soldier_two["damage"] _ soldier_two["attacks_per_second"]
Copy icon
Create a new function called get_soldier_dps that takes a soldier and returns its DPS using the same logic as the lines above. Then, replace the two lines above with calls to get_soldier_dps.
