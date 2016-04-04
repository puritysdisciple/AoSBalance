# Rules
toughness * damage * 10 * movement + bravery/10

toughness = wounds * 6 / (save - 1)

damage = attacks * (7 - hit) / 6 * (7 - wound) / 6 * damage * (1 + (.16 * rend))

0.5 range > 5 && < 16
1.5 range >= 16

movement = 0.9 if move < 5
movement = 1 if move = 5
movement = 1.1 if move = 6
movement = 1.3 if move = 7-9
movement = 1.4 if move = 10
movement = 1.5 if move = 11+
        
### Example: Skeleton
toughness = 1 * 6 / (5 - 1) = 1.5
damage = 1 * (7 - 5) / 6 * (7 - 4) / 6 = .17
movement = .9

points = 1.5 * .17 * 10 * .9 + 10/10 = 3.30


### Example: Dryad
toughness = 1 * 6 / (4 - 1) = 2
damage = 1 * (7 - 3) / 6 * (7 - 4) / 6 * 1 = .33
movement = .9

points = 2 * .33 * 10 * .9 + 6/10 = 6.54

### Example: Blood Knight
toughness = 2 * 6 / (4 - 1) = 4
damage = 2 * (7 - 3) / 6 * (7 - 4) / 6 * 1 = .67
movement = .9

points = 4 * .67 * 10 * .9 + 6/10 = 24.72
