% Facts: bird(Name, CanFly).
bird(sparrow, yes).
bird(penguin, no).
bird(eagle, yes).
bird(ostrich, no).
bird(parrot, yes).
bird(kiwi, no).

% Rule to check if a bird can fly.
can_fly(Bird) :-
    bird(Bird, yes),
    write(Bird),
    write(' can fly.'),
    nl.

% Rule to check if a bird cannot fly.
cannot_fly(Bird) :-
    bird(Bird, no),
    write(Bird),
    write(' cannot fly.'),
    nl.
