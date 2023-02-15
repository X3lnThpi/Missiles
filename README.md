# Missiles
The game includes a Plane with different Missiles, which have been designed using the Model-View-Controller (MVC) pattern. The MVC pattern provides a clear separation between the model, which represents the data and logic of the game, the view, which displays the game, and the controller, which handles user input and updates the model and view accordingly.

The score update functionality has been implemented using the Observer pattern. This pattern allows objects to be notified when a change occurs in another object, without requiring the objects to have direct knowledge of each other. In this case, the score display object observes the score update object and updates itself accordingly when the score changes.

To provide flexibility in controlling the game, you have implemented the Command pattern to switch between touch and Gyro control. This pattern allows you to encapsulate requests or actions as objects, which can be passed as parameters, stored, or executed at any time. This enables you to easily change or customize the control mechanism of the game by modifying the commands.

Finally, the Object Pooling technique has been implemented to store missiles. This technique allows you to reuse a pool of pre-allocated objects rather than creating and destroying them as needed. This reduces the overhead of object creation and destruction, resulting in improved performance and smoother gameplay.

Overall, by utilizing these design patterns, you have created a well-structured and efficient game that is easy to extend and maintain.
