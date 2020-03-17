# My Python Utilities - py-myutils

## Usage
```py
    from myutils import utils

    data = [1, 2, 3, 5, 6, 7, 8, 9, 11]
    print(utils.standardise_population_data(data))

    #[-1.5146104004041459, -1.1975989212497897, -0.8805874420954337, -0.2465644837867214, 0.07044699536763473, 0.38745847452199084, 0.704469953676347, 1.0214814328307031, 1.6555043911394154]
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