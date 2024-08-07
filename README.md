# Bond Valuation and Duration Calculator

## Description

This Python program calculates the value of a bond, its Macaulay duration, and its modified duration based on user-provided inputs. The program queries the user for pertinent bond parameters such as coupon rate, term to maturity, yield to maturity (YTM), par value, and compounding frequency. It then computes and displays the bond's value and its duration metrics.

## Key Features
- **Bond Value Calculation**: Computes the present value of the bond based on coupon payments and the par value.
- **Macaulay Duration**: Calculates the weighted average time until cash flows are received, in years.
- **Modified Duration**: Adjusts the Macaulay duration to account for the bond's yield, providing a measure of the bond's interest rate sensitivity.

## How It Works
1. **User Input**: Prompts the user for the coupon rate, term to maturity, YTM, par value (with a default option of $1,000), and compounding frequency (with a default option of semiannual).
2. **Bond Value Calculation**: Uses the provided inputs to calculate the bond's present value.
3. **Duration Calculation**: Computes the Macaulay and modified durations using the present value and cash flow timings.
4. **Output**: Displays the bond's value, Macaulay duration, and modified duration.