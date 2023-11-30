# Flow Cars SmartContract

## Tech 
- Cadance Programming
- Object Oriented programming


### Properties
- `name`: A string representing the name of the car.
- `model`:  An unsigned 32-bit integer representing the model of the car.
- `price`: An unsigned 32-bit integer representing the price of the car.

### Initialize Product
- `init(name: String, model: UInt32 ,price: UInt32)`: Initializes a new `car` instance with the provided name , model  and price.

## MyContract

### Properties
- `cars`: A dictionary mapping string keys to `car` values, representing a collection of cars.

### Initialize MyContract
- `init()`: Initializes a new instance of `cars` and initializes the `cars` dictionary.

### Methods
- `addCar(_name: String,_model:UInt32, _price: UInt32)`: Adds a new car to the `cars` dictionary. Creates a new `car` instance with the provided name, model and price, and stores it in the dictionary using the name as the key.

### Accessing Products
- `getCar(_name: String): car`: Retrieves the `cacr` with the specified name from the `cars` dictionary. Returns the cars if found, or throws an exception if the item does not exist.


## Usage

1. Deploy the contract to the desired blockchain network.
2. Use the contract's functions to manage products:
   - Call `addCars` to add a new car by providing the name,model and price.
   - Call `getcar` to retrieve a car by providing its name.
3. Interact with the contract using your preferred Cadence-compatible blockchain development tools.
## Output
![image](https://github.com/ManiShanker43/Flow1/assets/130231291/5a8ad53c-a85d-41d7-86e4-4e017a265fc7)

