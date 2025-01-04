planet('Mercury', 1, terrestrial, 0).
planet('Venus', 2, terrestrial, 0).
planet('Earth', 3, terrestrial, 1).
planet('Mars', 4, terrestrial, 2).
planet('Jupiter', 5, gas_giant, 79).
planet('Saturn', 6, gas_giant, 83).
planet('Uranus', 7, gas_giant, 27).
planet('Neptune', 8, gas_giant, 14).

planet_position(Name, Position) :-
    planet(Name, Position, _, _).

planet_type(Name, Type) :-
    planet(Name, _, Type, _).

planet_moons(Name, Moons) :-
    planet(Name, _, _, Moons).

planets_by_type(Type, Planets) :-
    findall(Name, planet(Name, _, Type, _), Planets).

planets_by_moons(MinMoons, Planets) :-
    findall(Name, (planet(Name, _, _, Moons), Moons >= MinMoons), Planets).
