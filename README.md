# PhotoProcessor Project

## Overview

The PhotoProcessor project consists of several Java classes that demonstrate key Java concepts such as constructors, exception handling, string manipulation, GUI handling with `JOptionPane`, and interactions with an external library (`cmsc131PictureLib`). This project serves as a practical application of these concepts through a photo processing system and its associated functionalities.

## Project Structure

The project is divided into the following classes, each focusing on different Java topics:

### Address.java

**Java Topics Covered:**
- **Constructors**: Implements default, parameterized, and copy constructors.
- **Exception Handling**: Throws `IllegalArgumentException` for invalid address arguments.
- **String Manipulation**: Trims whitespace from strings.
- **Encapsulation**: Uses private fields and public getter methods.
- **Object Comparison**: Overrides the `equals` method to compare `Address` objects.

**Description:**
This class represents an address with street, city, state, and zip code fields. It provides various constructors for different initialization scenarios, methods to get the address details, and a method to check equality of two addresses.

### PhotoProcessingSys.java

**Java Topics Covered:**
- **Constructors**: Implements default and parameterized constructors.
- **Exception Handling**: Handles invalid address arguments.
- **String Manipulation**: Uses `StringBuffer` to store transaction history.
- **GUI Handling**: Uses `JOptionPane` for user interactions in graphical mode.
- **Encapsulation**: Uses private fields and public getter methods.

**Description:**
This class represents a photo processing system with functionalities to process various image tasks such as displaying, clearing, and applying effects to images. It maintains a transaction history and balance for the processing tasks.

### PictureManager.java

**Java Topics Covered:**
- **Static Methods**: Implements static methods for different picture processing tasks.
- **GUI Handling**: Uses `JOptionPane` for user interactions in graphical mode.
- **Interaction with External Library**: Uses `cmsc131PictureLib` for image processing tasks.
- **Boolean Flags**: Manages graphical mode state with a boolean flag.

**Description:**
This class provides static methods to perform various picture processing tasks such as displaying pictures, clearing the screen, displaying the last picture, and applying black and white or posterize effects. It supports both graphical and non-graphical modes.
