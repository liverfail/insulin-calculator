# Insulin Calculator

This insulin calculator was made to help Type 1 diabetics determine their insulin dosage based on blood sugar level, goal blood sugar, sensitivity factor, insulin carb ratio, and planned carbohydrate intake.

## Features

- **Input Fields:**
  - **Blood Sugar (bs):** Current blood sugar level in mg/dL.
  - **Goal Blood Sugar (gbs):** Target blood sugar level in mg/dL.
  - **Sensitivity Factor (sf):** How much 1 unit of insulin lowers blood sugar (mg/dL/unit).
  - **Insulin Carb Ratio (icr):** How much 1 unit of insulin covers carbohydrates (g/unit).
  - **Carbs to Eat (cte):** Planned carbohydrate intake in grams.

- **Calculation Formula:**
  ```
  Insulin Dose = (bs - gbs) / sf + cte / icr
  ```

- **Usage:**
  1. Enter your current **Blood Sugar**, **Carbs to Eat**, and prescribed details from your doctor.
  2. Click "Calculate" or similar button to compute the recommended insulin dose.
  3. Follow your healthcare provider's recommendations for insulin dosing adjustments.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript

## Usage

Simply go to the production website [here](https://liverfail.github.io/insulin-calculator).

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to [Mikkel Ofrim](https://github.com/Mikkelof) for (inspiration)[https://github.com/Mikkelof/InsulinCalc].
- Additional resources are from [Font Awesome](https://fontawesome.com/) and [Tailwind CSS](https://tailwindcss.com/)