# Annuity Illustration Tool

## Purpose

The Annuity Illustration Tool is a powerful financial planning resource designed to provide insights into annuity products. It aids clients and financial professionals in making informed decisions about their financial future.

## Instructions

### Opening the File

1. Download `ANNUITY_ILLUS.xlsm` and `BUSINESS_DATA.txt` files.
2. Right-click on `ANNUITY_ILLUS.xlsm` and select "Properties."
3. At the bottom of the Properties screen, tick the "Unblock" checkbox and click "Apply."
4. Open the `ANNUITY_ILLUS.xlsm` file.

### Using the Annuity Illustration Tool

On the "Annuity_Calc" spreadsheet, you can input specific parameters according to the client to preview the annuity payment stream, expected total payment, total payment duration, and age of the last payment. The annuity is preset to run from age 40 to age 110, but specifics can be changed in the "Formula" spreadsheet. There are 7 preset annuity plans:

1. **Fixed Payment:** Allows the client to determine the start and end age (Default Parameters: $15,000).
2. **Increasing Payment:** Has an initial payment value and increases by a fixed amount per year over the duration of the policy. Start and end age can be set by the company (Default Parameters: $25,000, $1,000, 65, 94).
3. **Fixed Payment (Lifetime):** Provides a fixed payment per year. The client determines the starting age, but it always goes to the maximum policy duration (Default Parameters: $7,200, 110).
4. **Age-Related Payment:** The client receives a payment value equivalent to the number of years they have been alive times a fixed value per year. Start and end age are determined by the company (Default Parameters: $1,000, 60, 100).
5. **Variable Payment:** The client receives a certain amount for the first half of the duration and a different amount in the second half. Start age and end age are determined by the client (Default Parameters: $19,000, $25,000).
6. **Fixed Total Payment:** The client receives a fixed total amount divided by equal payments across the policy duration. The client determines the start and end age (Default Parameters: $100,000).
7. **Biennial Payment:** A fixed amount of payment is made every 2 years, with the initial payment starting on the first year. The client determines the starting and ending age of the policy (Default Parameters: $30,000).

**Parameters of the policies can be changed under the "Formula" worksheet.**

### Importing Data

1. Go to the "Data_Sheet" spreadsheet where you will see an import button.
2. Click on the import button and select the `BUSINESS_DATA.txt` file.

### Automating Expected Payment Calculations for a Group

1. After importing the data, go to the "Group_Summary" worksheet.
2. Click on the "Expected Payment Calculation" button to generate expected calculations for each client in the group.
3. The "Reset" button will automatically delete all imported and generated data.
