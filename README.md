# Agro-Infiltration Buffer Calculator v1.5

A client-side web tool designed for plant biologists to streamline the process of preparing agroinfiltration buffers and generating printable experimental data sheets. This calculator handles complex calculations for multiple buffer components, Agrobacterium cultures, and post-incubation additives, saving valuable time and reducing the potential for manual errors.

 
<img width="1596" height="1018" alt="image" src="https://github.com/user-attachments/assets/352b9f9c-8359-44d2-a64e-33fa13a84a36" />





---

## Features

-   **Dynamic Buffer Recipes:** Add, remove, and define any number of buffer components with their respective stock and target concentrations.
-   **Multi-Construct Calculation:** Automatically calculates the required volume for multiple Agrobacterium constructs, normalizing for different stock ODs and distributing the total volume evenly.
-   **Pre-Infiltration Additives:** Easily calculate the required amount of additives like Silwet L-77, supporting v/v %, w/v %, and molar concentrations.
-   **Printable Data Sheet:** Generates a clean, well-organized experimental data sheet that can be printed and taken to the lab bench.
-   **Save & Load Parameters:** Export your entire setup to a `.csv` file to save a specific protocol, and load it back in a single click.
-   **Integrated Stock Solution Calculator:** A handy modal to quickly calculate the mass of solute needed to prepare a stock solution, with an option to directly add it to the buffer recipe.

<img width="496" height="376" alt="image" src="https://github.com/user-attachments/assets/af2f2b69-3c10-4692-889c-4073f4df02d1" />


## How to Use

1.  **Open the web page at "https://anindya-karmaker.github.io/agroinfiltration_calculator".**
2.  **Set Global Parameters:** Enter the total final volume you plan to make.
3.  **Define Components:** Adjust the default buffer components or add new ones, specifying their stock and target concentrations.
4.  **Add Constructs:** For each Agrobacterium culture, enter its name, the target OD₆₀₀ for infiltration, and the measured stock OD₆₀₀.
5.  **Generate Sheet:** Click the "Generate Experimental Data Sheet" button.
6.  **Print or Save:** The results will appear on the right. You can review them, make adjustments, or print the sheet for your experiment.

## Technology Stack

-   **HTML5**
-   **CSS3** with **Bootstrap 5** for styling and layout.
-   **JavaScript (ES6)** for all calculations and DOM manipulation.

The tool is entirely client-side, meaning no data is ever sent to or stored on a server, ensuring data privacy.

## License

Developed by Anindya Karmaker. All rights reserved. Unauthorized copy or distribution of this application is strictly prohibited. For inquiries or feedback, please contact the [McDonald-Nandi Lab](https://mcdonald-nandi.ech.ucdavis.edu/).

-   **Developed by:** Anindya Karmaker, PhD Candidate, McDonald-Nandi Lab.
-   **Funding:** The development of this tool was supported by the National Science Foundation Partnerships for Innovation (PFI) program under Grant No. 2016563.
-   **License:** All rights reserved.
