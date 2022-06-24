# Computer-Class-Inheritance

This task implements the class hierarchy for a computer business, and here are the created classes and support: 

- Keyboard  class that contains: 

  manufacturer - string property for the name of the manufacturer 

      responseTime - number property for the response time of the Keyboard 

- Monitor class that contains: 

      manufacturer - string property for the name of the manufacturer 

      width - number property for the width of the screen 

      height - number property for the height of the screen 

- Battery class that contains: 

      manufacturer - string property for the name of the manufacturer 

      expectedLife - number property for the expected years of the life of the battery 

- Computer – an abstract class that contains: 

      manufacturer - string property for the name of the manufacturer 

      processorSpeed - a number property containing the speed of the processor in GHz 

      ram - a number property containing the RAM of the computer in Gigabytes 

      hardDiskSpace - a number property containing the hard disk space in Terabytes 

- Laptop - class extending the Computer class that contains: 

      weight - a number property containing the weight of the Laptop in Kilograms 

      color - a string property containing the color of the Laptop 

      battery - an instance of the Battery class containing the laptop's battery. There should be a getter and a setter for the property and validation that the passed-in argument is an instance of the Battery class. 

- Desktop - concrete class extending the Computer class that contains: 

      keyboard - an instance of the Keyboard class containing the Desktop PC's Keyboard.
There should be a getter and a setter for the property and validation that the passed-in argument is an instance of the Keyboard class. 

      monitor - an instance of the Monitor class containing the Desktop PC's Monitor. There should be a getter and a setter for the property and validation that the passed-in argument is an instance of the Monitor class.
