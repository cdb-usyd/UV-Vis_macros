# UV-Vis_macros
These are two macros designed to process the data from Scanning Kinetics output.

## Installation

Add the two macros as individual modules. They can be stored in PERSONAL.XLSB for persistence. See [here](https://support.office.com/en-us/article/create-and-save-all-your-macros-in-a-single-workbook-66c97ab3-11c2-44db-b021-ae005a9bc790).

## Usage
Macros can be selected from the excel toolbar > View > Macros > View Macros. Shortcuts can also be assigned if desired. See [here](https://support.office.com/en-us/article/run-a-macro-5e855fd2-02d1-45f5-90a3-50e645fe3155).

Macro1 (first_processMultiscanUVVis()) should be run first, while in the sheet containing the raw output from the UV-vis scanning kinetics. The Macro removes the redundant Wavelength columns and plots the data for preliminary analysis.

Select the wavelength of interest from column 1 by clicking into the cell containing that wavelength. Then run Macro2 (second_oneWavelengthProcess()). A sheet will be made containing the data at that wavelength and a plot of the data.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)

Copyright (c) [2020] [Christopher Barnett]