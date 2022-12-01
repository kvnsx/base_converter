<!-- 
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages). 

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages). 
-->

# base_converter

```base_converter``` is a dart package that helps you add base quantities' converter functionality to your code. There are 7 basic quantities supported in this package. The Seven Basic Quantities supported in this package are ```Length```, ```Mass```, ```Time```, ```Temperature```, ```ElectricCurrent```, ```LuminousIntensity``` and ```AmountOfSubstance```. You can use all seven of them to convert a quantity from one unit to another.

## Usage
This is the example how you can use this package.
```dart
final TemperatureUnit originUnit = TemperatureUnit.celsius;
final TemperatureUnit destinationUnit = TemperatureUnit.fahrenheit;
final Temperature t1 = Temperature(10, originUnit);
final num result = t1.convertTo(TemperatureUnit.destinationUnit);
final Temperature t2 = Temperature(result, destinationUnit);
```

## Supported Units

### Length
* meter
* kilometer
* hectometer
* dekameter
* decimeter
* centimeter
* milimeter
* micrometer
* nanometer
* gigameter
* megameter
* angstrom
* inch
* foot
* yard
* mile
* nauticalMile

### Mass
* kilogram
* hectogram
* dekagram
* gram
* decigram
* centigram
* miligram
* microgram
* nanogram
* megagram
* gigagram
* ounce
* pound
* ton

### Time
* second
* minute
* hour
* day
* week
* month
* year
* decade
* century

### Time
* kelvin
* celsius
* fahrenheit
* reaumur

### Electric Current
* ampere
* kiloampere
* statampere
* miliampere

### Luminous Intensity
* candela (international),
* candela (German)
* candela (UK)

### Amount of Substance
* mole
* kilomole
* milimole
* pound mole