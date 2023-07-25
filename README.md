# Garage Management System

**Description:**

This is a console-based Garage Management System that allows you to efficiently manage different types of vehicles in a garage. With this system, you can perform various actions such as adding new vehicles, updating vehicle status, inflating tires, refueling, and more.

**Getting Started:**

To run the Garage Management System, you will need a C# development environment or an IDE that supports C# code. The system consists of two main components: the GarageLogic library and the ConsoleUI application. First, let's take a look at the GarageLogic library, which contains the vehicle-related classes and logic.

**GarageLogic:**

The GarageLogic library contains the core classes and logic for managing vehicles.

- `EnumsProcedures.cs`: This file contains various enums used by the system.

- `EnergySource.cs`: This is an abstract class representing the energy source of a vehicle. It has two subclasses: `ElectricBasedVehicle` and `FuelBasedVehicle`.

- `ElectricBasedVehicle.cs`: This class represents an electric-based vehicle and is a subclass of `EnergySource`.

- `FuelBasedVehicle.cs`: This class represents a fuel-based vehicle and is a subclass of `EnergySource`.

- `ValueOutOfRangeException.cs`: This class defines a custom exception for handling value out-of-range errors.

- `Wheel.cs`: This class represents a wheel of a vehicle.

- `Vehicle.cs`: This is an abstract class representing a generic vehicle. It has three subclasses: `Car`, `Truck`, and `Motorcycle`.

- `Car.cs`: This class represents a car and is a subclass of `Vehicle`.

- `Motorcycle.cs`: This class represents a motorcycle and is a subclass of `Vehicle`.

- `Truck.cs`: This class represents a truck and is a subclass of `Vehicle`.

- `NewVehicleCreator.cs`: This class contains static methods for creating new instances of different vehicle types.

- `VehicleOwner.cs`: This class represents a vehicle owner and contains information about the owner and their vehicle.

- `Garage.cs`: This class represents the garage and manages the vehicles and vehicle owners.

**ConsoleUI:**

The ConsoleUI is the user interface component of the Garage Management System.

- `Program.cs`: This is the main entry point of the ConsoleUI application. It contains the main menu and handles user input.

**How to Use:**

To use the Garage Management System, follow these steps:

1. Compile and run the ConsoleUI application.
2. Follow the on-screen instructions to interact with the system.
3. Use the menu options to add new vehicles, update vehicle status, inflate tires, refuel vehicles, and more.
