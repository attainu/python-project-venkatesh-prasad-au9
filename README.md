Parking Lot Project (Python)
## 1. Problem Statement
Design a Parking lot which can hold n number of cars. Every car assigned a slot based on distance to entrance. The system returns some information as follows:

- Registration numbers of all cars of a particular colour.
- Slot number in which a car with a given registration number is parked.
- Slot numbers of all slots where a car of a particular colour is parked.

## 2. Solution Approach
A car has three attributes, Reg. Number, Colour and Parking Slot number. Likewise, our Parking Lot consists of slots. For not making it complex, a python dictionary for storing cars on slots was chosen and implemented with the functionalities accordingly.

## 3. Supported Commands
- `create_parking_lot` <`n`> 
  To create a Parking lot. Where n is the size of the parking lot.

- `park` <`registration_number`> <`colour`> 
  To park the car in the parking lot and prints the allocated slot in the parking lot. Where registration_number is given registration number for the car and colour is colour of the car.

- `leave` <`slot`>
  To vacate the parking slot and prints the leaving slot. given slot number. Where slot is given slot number

- `status`
  To check the status of Parking Lot.

- `slot_numbers_for_cars_with_colour` <`colour`> 
  To prints the registration number of the cars for the given colour. Where color is given colour

- `slot_number_for_registration_number` <`registration_number`>
  Prints the slot number of the cars for the given number. Where registration_number is given registration number.

- `registration_numbers_for_cars_with_colour` <`colour`>   
  To prints the slot number of the cars for the given colour. Where colour is given colour.

## 4. Running Application

#### 4.1 Running the application in File mode:
./ParkingLot.py input.txt

#### 4.2 Running the application in Interactive mode:
./ParkingLot.py