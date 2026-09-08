# Test Questions
**Company:** Optiver
**Profile:** Software Engineering

One big class-implementation question.

**Question**

There is a squirrel who stores nuts in locations.

The class is initialised with a `dict[str, int]`, where the key is the `location_id`
of the storage and the value is the number of levels in that location.

The location has a cone shaped object with n levels (n from the dictionary). The
bottom-most level has 1 position for hiding a nut, the level above that has 2, the
level above that 3 - i.e. each level can hide the corresponding Fibonacci number of
nuts, the sequence being 1, 2, 3, 5, ...

Timestamps are floating point numbers - the number of seconds passed since some
date in 1970, with 4 digits of precision for milliseconds. Weights are floating
point numbers in grams with precision to milligrams.

**`hide_nut`** (returns `bool`), taking `timestamp`, `weight`, `nut_id`,
`location_id`, `time_to_expire`:
Given a `nut_id`, hide it in the `location_id`, filling a position in the deepest
level possible (filling upwards). If a `location_id` is invalid or full, return
false. `timestamp + time_to_expire` is the exact time when the nut expires. If the
nut has already been hidden, return false.

**`retrieve_nut`** (returns a list of `nut_id`), taking `timestamp`, capacity of the
squirrel, `location_id`:
If the location id is empty, return `[]`. The capacity of the squirrel is the number
of nuts it can carry. The squirrel retrieves downwards, from the uppermost
non-empty level in the `location_id`. If the uppermost level is less than 50 percent
filled, the squirrel starts taking nuts from the level below. The squirrel always
chooses the heaviest nut in the level. If a nut that is picked up has expired, the
squirrel throws the nut away. Whenever a place becomes empty, the lightest nut from
the level above falls into it. If there is a tie in the weight of nuts, select the
one with the lexicographically smaller `nut_id`. Return the list in order of
retrieval.
