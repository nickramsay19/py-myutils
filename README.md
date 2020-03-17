# My Python Utilities - py-myutils

## Usage
```py
    from myutils import utils

    data = [1, 2, 3, 5, 6, 7, 8, 9, 11]
    print(utils.standardise_population_data(data))
```

## Methods
```py
    float_range(precision: int, min: int or float = 0, max: int or float = 1, inclusive: bool = False) -> list

    map2range(value: int or float, inMin: int or float, inMax: int or float, outMin: int or float, outMax: int or float) -> int or float

    standard_deviation_population(data: list) -> float

    standard_deviation_sample(data: list) -> float

    mean(data: list) -> float

    standardise_population_data(cls, data: list) -> list

    standardise_sample_data(cls, data: list) -> list
```