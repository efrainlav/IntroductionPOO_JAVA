# IntroductionPOO_JAVA

IntroductionPOO_JAVA is a JAVA project excercises that contain 6 kind of classes with their attribute, constructors and methods.

## Installation

Just cpoy-paste the file repository on your NETBEANS project directory.
Teh local directory used was: 
```bash
C:\Users\XXXXX\Documents\NetBeansProjects\IntrodutionObjetcs
```

## Classes
```mermaid
classDiagram
      class Person{
          
          + setName(String name)
          + getName(): String
          + name: String
          + lastName1: String
          + lastName2: String
          + dateBirth: Date
          + height: float 
      }

      class Fruit{
          - setColor(String name)
          - getColors(): ArrayList<String> 
          - getName()
          + name: String
          - averageWeight: float 
          + colors: ArrayList<String>
          + String color
      }

      class BankAccount{
          + setActivated(boolean activated)
          + getActivated(): boolean
          - accountNumber: int
          # activated: boolean 
      }
```

```mermaid
classDiagram
   
      class Ball{
          + radio: float 
          + weight: float 
          + obtenerRadio()
          + obtenerPeso()
      }

      class Car{
          + idCar: int 
          + weight: double 
          + height: double 
          + size: double 
          + numberDoor: int 
          + model: String 
          + speed: int 
          + getIdCar()
          + setIdCar(int idCar)
          + getModel()
          + setModel(String model)
          + increaseSpeed(int increment)
      }

      class Pet{
          + name: String 
          + species: String 
          + age: int 
          + play()
          + pet()
          + bark(String specie)
      }
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)