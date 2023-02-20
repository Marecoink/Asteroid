# Asteroid
The classes Ship and Asteroid are subclasses of the abstract class Character. They both inherit the properties and methods of the Character class.

The Ship class represents a spaceship and is defined by a Polygon shape with three points that form a triangular shape. The constructor of the Ship class initializes the shape of the ship by calling the constructor of the parent Character class and passing in the Polygon shape with the initial position of the ship.

The Asteroid class represents an asteroid and is defined by a Polygon shape with four points that form a square shape. The constructor of the Asteroid class initializes the shape of the asteroid by calling the constructor of the parent Character class and passing in the Polygon shape with the initial position of the asteroid.

Both the Ship and Asteroid classes have the methods turnLeft(), turnRight(), move(), and accelerate() which can be used to control the movement and rotation of the respective objects. The turnLeft() and turnRight() methods change the rotation of the object by 5 degrees in the respective direction. The move() method updates the position of the object based on its current movement vector. The accelerate() method calculates a change in the movement vector based on the current rotation of the object and adds it to the current movement vector.

Overall, the Ship and Asteroid classes provide a simple implementation of movable and rotatable objects in a 2D space using JavaFX.
