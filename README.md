# Temperature Converter (Java)

[![Language](https://img.shields.io/badge/Language-Java-orange.svg)](https://www.java.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A console-based Java temperature conversion exercise. The user enters a temperature and chooses the target unit, Celsius or Fahrenheit.

## Conversion Behavior

- Choose **F** to treat the entered value as Celsius and convert to Fahrenheit: `F = C × 9/5 + 32`.
- Choose **C** to treat the entered value as Fahrenheit and convert to Celsius: `C = (F − 32) × 5/9`.

The result is displayed to one decimal place.

## Project Structure

```text
temperature-converter-program/
└── MiniProject3.java
```

## Compile and Run

```bash
javac MiniProject3.java
java MiniProject3
```

Enter a temperature, then select `C` or `F` as the target unit.

## Concepts Practiced

- Console input with `Scanner`.
- String normalization with `toUpperCase()`.
- Conditional expressions (ternary operator).
- Numeric formatting.

## Limitations and Improvements

The prompt does not explicitly state the assumed source unit; it is inferred from the target choice. Also, any choice other than `F` currently follows the Celsius-conversion branch, so invalid units are not rejected. Add validation and make source and target units explicit.

## License

Licensed under the MIT License. See [LICENSE](LICENSE).
