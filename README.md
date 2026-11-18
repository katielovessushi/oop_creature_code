# Creature Battle Project (OOP + Git Branching Practice)

This project is designed to help me learn **object-oriented programming** in Python — especially **inheritance** — while also practicing key **Git concepts** like branching, merging, conflict resolution, and version history.

I will begin with a base class (`Creature`) and create additional subclasses on separate Git branches to simulate a real development workflow.

---

## Learning Objectives

### Python / OOP
- Understand and implement **classes**
- Use **inheritance** to extend behaviors
- Override and extend methods (e.g., `attack()`)
- Practice writing simple test code in `main`

### Git / Version Control
- Create and switch branches
- Merge branches into `main`
- Resolve merge conflicts
- View commit history (`git log --graph --all`)


---

## Project Structure
oop_creature_code/
│
├── creature_simulation.py # Base class + subclasses
└── README.md

## Project Structure
### Creature (base class)

name, hp, attack_power : set in __ init__
attack(target) : Deals attack_power damage to target. A defeated creature cannot attack.
is_alive() : Returns True if hp > 0
__ str__() : Returns "Name (HP: n)" 

#### SwimmingCreature (subclass)

new attribute : depth
method : dive_to(new_depth), attack

#### FlyingCreature (subclass)

new attribute : altitude
method : fly_to(new_altitude), attack

#### FireCreature (subclass)

new attribute : fire_level
method : emit_fire(new_fire_level), attack

## How to test the code
To test and run the program I Compare each "should be" line with its "Actual" value to check that it is correct
