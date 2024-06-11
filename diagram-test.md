```mermaid
classDiagram
    Car : +String color
    Car : +String make
    Car : +String model
    Car : +startEngine()
    Car : +stopEngine()
    Car <|-- SportsCar: Inheritance
    Car <|-- FamilyCar: Inheritance
    SportsCar : +int topSpeed
    SportsCar : +goFast()
    FamilyCar : +int seats
    FamilyCar : +fitManyPeople()
```