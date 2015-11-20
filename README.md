# Heat

A tool for quickly eyeballing the values of numbers in text files and streams.

## Overview

Heat takes a pair of values and colorizes numbers in the input stream based on
where within that range the number falls. If it falls outside of the range, the
color will be clamped to the closest endpoint in the range. This makes it good
for visualizing data in a desired range, such as for accuracies.

## Installation

At the moment, just put the `heat` script file in your `PATH` and make it
executable.

## Usage

```
heat <lower> <upper>
```

## License

Heat is licensed under the MIT license. The full license is in the `LICENSE`
file.