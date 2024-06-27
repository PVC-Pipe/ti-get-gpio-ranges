Example execution for the J722S:

```
$ python3 ti-get-gpio-ranges.py devicetree.dtsi
# main_gpio0
<&main_pmx0 0 0 32>,
<&main_pmx0 32 33 38>,
<&main_pmx0 70 72 17>;

# main_gpio1
<&main_pmx0 7 101 25>,
<&main_pmx0 42 137 5>,
<&main_pmx0 47 143 3>,
<&main_pmx0 50 149 2>;

# mcu_gpio0
<&mcu_pmx0 0 0 21>,
<&mcu_pmx0 21 23 1>,
<&mcu_pmx0 22 32 2>;
```