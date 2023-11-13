# Simple-Agent-Dog-
The dog will perform actions like moving, eating, drinking, and barking as it encounters objects in the park. The simulation ends when there is no more food, water, or people in the park or when the dog is no longer alive.

defines a few classes:
  Thing: Represents any physical object in the environment.
  Agent: A subclass of Thing with a required program function that takes percepts and returns actions.
  Environment: An abstract class that represents the environment and contains methods to define percepts, execute actions, and run the environment.

Then defines specific classes for objects in the park, including Food, Water, Tree, and Person.

Defines a specific environment class called Park, which is a subclass of Environment. This class is responsible for defining percepts and executing actions specific to the park environment.

A BlindDog class is defined, which is a subclass of Agent representing the dog. The BlindDog has methods to move, eat, drink, and bark, based on its percepts.

The program function defines the dog's behavior based on its percepts. It makes the dog eat, drink, or bark when it perceives food, water, or a person, respectively.
