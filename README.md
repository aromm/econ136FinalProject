# econ136FinalProject
Final project for Econ 136. Completed by Hamza Khan, Drew Summy, and Anthony Romm.
This leverages the Interactive Brokers API and `ib_insync` python wrapper to return a single option contract.

# What's Inside
`getOption.py` features a function to return a single option contract based on provided parameters. 
In order to select your contract, users must provide an ib object, `ticker`, `strike`, and some sort of expiry date.
Expiry dates can either be represented with `<int>` parameters `year`, `month`, and `day` or `date`. Specifications on the formats of these variables are provided in the file.
Optional parameters include `exchange`, `currency`, and `optType` which default to `'SMART'`, `'USD'`, and `'C'` respectively.
An example program is included in the file.

# How to Run
Simply import the file into your project using `from getOption import *` and then you can use the `getOption()` function.
