# Mortgage Repayments Calculator

This project is a **Mortgage Repayments Calculator** built using **Streamlit**. It allows users to calculate their mortgage payments and visualize the repayment schedule over time.

## Features

### Inputs
- **Home Value**: Total value of the property.
- **Deposit**: Initial down payment made by the user.
- **Interest Rate**: Annual interest rate of the mortgage.
- **Loan Term**: Duration of the mortgage in years.

### Outputs
- **Monthly Repayments**: Fixed monthly payment amount.
- **Total Repayments**: Total amount paid over the life of the loan.
- **Total Interest**: Total interest paid on the loan.
- **Visualization**: A line chart showing the remaining balance at the end of each year.

## Technologies Used
- **Streamlit**: Web application framework for creating interactive dashboards.
- **Pandas**: For data processing and manipulation.
- **Matplotlib**: For plotting and visualizations.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/mortgage-calculator.git
   cd mortgage-calculator
   ```

2. Install the required Python libraries:
   ```bash
   pip install streamlit pandas matplotlib
   ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```

4. Open the provided URL in your browser to access the calculator.

## Application Workflow

1. Enter the following inputs:
   - **Home Value**: e.g., $500,000
   - **Deposit**: e.g., $100,000
   - **Interest Rate**: e.g., 5.5%
   - **Loan Term**: e.g., 30 years

2. The app calculates:
   - Monthly repayment amount
   - Total repayments
   - Total interest paid

3. Visualize the repayment schedule through a line chart displaying the remaining balance by year.

## Project Files
- `app.py`: Main application script.
- `README.md`: Documentation file.
- `requirements.txt`: List of dependencies.

## Example
For a loan with the following inputs:
- **Home Value**: $500,000
- **Deposit**: $100,000
- **Interest Rate**: 5.5%
- **Loan Term**: 30 years

The outputs would be:
- **Monthly Repayments**: $2,271.16
- **Total Repayments**: $817,618
- **Total Interest**: $417,618

### Visualization
The line chart will display the decreasing remaining balance over time.

## Author
**Prabhu Shankar**  
Email: prabhushankargv@gmail.com  

