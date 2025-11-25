# Knowledge of Resistor

Structure and how to use: [https://youtu.be/DYcLFHgVCn0?si=4pEe-w04MNtu5Tzv](https://youtu.be/DYcLFHgVCn0?si=4pEe-w04MNtu5Tzv)

# How to read resistor color codes

![Datasheet](resistor_color_codes_chart.png)

 - Identify the color bands: Most through-hole resistors have 4 or 5 color bands. The first 2 (or 3) bands represent significant digits, the next band is the multiplier, and the last band shows tolerance.
- Use the color chart: Match each color to its corresponding number. For example, Black = 0, Brown = 1, Red = 2, Orange = 3, Yellow = 4, Green = 5, Blue = 6, Violet = 7, Gray = 8, White = 9.
- Calculate the resistance: Combine the significant digits and multiply by the multiplier.
- Check the tolerance: The last band tells you the possible variation in resistance, e.g., Gold = ±5%, Silver = ±10%.
  
Example: A resistor with bands Red, Violet, Yellow, Gold → 2 7 × 10,000 Ω = 270 kΩ ±5%.

# How to Read SMD Resistor Codes

![Datasheet](SMD-Resistor-Code.gif)
![Datasheet](resistor_SMD_codes_2.png)

Identify the code: Most SMD resistors have 3 or 4 digits printed on them, sometimes with an R to indicate a decimal point. 3- or 4-digit codes:
```
3-digit: first 2 digits = significant, last digit = multiplier (number of zeros)
Example: 472 → 47 × 10² Ω = 4.7 kΩ
```

```
4-digit: first 3 digits = significant, last digit = multiplier
Example: 1001 → 100 × 10¹ Ω = 1 kΩ
```

```
R notation for decimals: R replaces the decimal point.
Example: 4R7 → 4.7 Ω, 0R22 → 0.22 Ω
```

EIA-96 codes (2 digits + letter): Small precision resistors may use this system. Look up the number in a standard EIA-96 table, then multiply by the multiplier indicated by the letter.

Tolerance: Sometimes a letter after the number indicates tolerance, e.g., J = ±5%, K = ±10%.
