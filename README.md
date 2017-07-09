# OOP-with-PHP

## What we have learned
### Class

### Interface

### Polymorphism

### Design Pattern
#### Factory

#### Singleton

## HW
You should make the files inside `hw` folder!
* Remeber: * all properies should be `private`
### What to do
1. Please create a new interface called `IElectronicPart` with the following signatures:
    * getSpecs()

2. Please create a new class called `ElectronicPart` with the following properties:
    * $manufacturer;
    * $price;
    * $model;
    * priceAfterTax();

3. Please create a new class called `Screen` that extends `ElectronicPart` and implements `IElectronicPart` with the following properties:
    * $size;
    * $panel;

4. Please create a new class called `Mouse` that extends `ElectronicPart` and implements `IElectronicPart` with the following properties:
    * $isWired;

5. Please create a new class called `Keyboard` that extends `ElectronicPart` and implements `IElectronicPart` with the following properties:
    * $isWired;

6. Please create a new class called `Computer` that extends `ElectronicPart` and implements `IElectronicPart` with the following properties:
    * $motherboard;
    * $processor;
    * $hardDrive;
    * $ram;
    * $graphicCard;

7. Please create a new class called `purchase` with the following properties:
    * $screen;
    * $mouse;
    * $keyboard;
    * $computer;
    * getFullPurchaseDetails();

### Use the tester!
You can find the main tester as the file `tester.php`, inside `hw` folder.

### Results expected
```
Screen manufacturer: Samsung, model: S24F350FH, Price: 0, Size: 24
Mouse manufacturer: Microsoft, model: Mobile Mouse 1850, Price: 0, Is wired: 
Keyboard manufacturer: Microsoft, model: , Price: 0, Is wired: 1
Computer manufacturer: GIGABYTE, model: , Price: 0

Screen manufacturer: Samsung, model: C27F591FD, Price: 0, Size: 27
Mouse manufacturer: LogiTech, model: M185, Price: 0, Is wired: 1
Keyboard manufacturer: Microsoft, model: , Price: 0, Is wired: 1
Computer manufacturer: Intel, model: , Price: 0

Screen manufacturer: Philips, model: 273V5LHAB, Price: 0, Size: 27
Mouse manufacturer: LogiTech, model: MX Master, Price: 0, Is wired: 
Keyboard manufacturer: Corsair, model: , Price: 0, Is wired: 1
Computer manufacturer: GIGABYTE, model: , Price: 0

Screen manufacturer: Samsung, model: S22F350FH, Price: 0, Size: 21.5
Mouse manufacturer: Microsoft, model: Mobile Mouse 1850, Price: 0, Is wired: 
Keyboard manufacturer: Logitech, model: , Price: 0, Is wired: 1
Computer manufacturer: AMD, model: , Price: 0

```

php -S localhost:8000