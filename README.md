# Home Loan Repayment Calculator (Variable)

## Description

A **Home Loan Repayment Calculator** designed to calculate various aspects of a home loan including **minimum repayment amount**, **required offset balance**, **principal allocation**, **interest allocation**, **total interest payable**, and **total loan & interest amount**. This tool is for educational purposes and provides users with a simple way to estimate their loan repayment schedules based on customizable inputs.

### Key Features:
- Calculates the **minimum repayment amount** based on loan amount, interest rate, and loan term.
- Allows users to include the **current offset account balance** to calculate adjusted repayments.
- Supports **weekly**, **fortnightly**, and **monthly** repayment frequencies.
- Displays detailed breakdowns of:
  - **Weekly interest rate**
  - **Number of payments**
  - **Principal allocation**
  - **Interest allocation**
  - **Total interest payable**
  - **Total loan and interest amount**

### Steps to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/home-loan-repayment-calculator.git

2. **Navigate to the project folder:**
   ```bash
   cd home-loan-repayment-calculator
3. **Open the index.html file in your browser.**

## How It Works

The **Home Loan Repayment Calculator** uses the standard **loan amortization formula** to calculate the minimum repayment amount, based on the input parameters like loan amount, interest rate, loan term, and offset balance. The application is built with **Vue.js** for reactivity, and it computes the various formulas for loan calculations.

### Main Formulas Used

1. **Loan Amortization Formula**:
   - Formula: `M = P * (r * (1 + r)^n) / ((1 + r)^n - 1)`
   - Where:
     - M = Minimum repayment amount
     - P = Loan amount (principal)
     - r = Interest rate per period
     - n = Number of repayments

2. **Required Offset Balance**:
   - Formula: `Required Offset Balance = Loan Amount - Adjusted Loan Balance`
   - Adjusted Loan Balance is calculated using a specific formula based on repayment amount and interest rate.

3. **Principal Allocation**:
   - Formula: `Principal Allocation = Minimum Repayment - Interest Allocation`
   - Interest Allocation = P * r

4. **Interest Allocation**:
   - Formula: `Interest Allocation = P * r`

5. **Total Interest Payable**:
   - Formula: `Total Interest Payable = (Minimum Repayment * Number of Periods) - Loan Amount`

6. **Total Loan & Interest Amount**:
   - Formula: `Total Loan & Interest Amount = Loan Amount + Total Interest Payable`

## Usage

### Input Fields:
- **Loan Amount**: The total amount of the home loan.
- **Annual Interest Rate**: The annual interest rate for the loan.
- **Loan Term (Years)**: The number of years for which the loan is taken.
- **Current Repayment Amount**: The current repayment amount.
- **Current Offset Account Balance**: The balance of your offset account.
- **Repayment Frequency**: Choose between **weekly**, **fortnightly**, and **monthly** repayment frequencies.

### Results:
After entering the data, click **Calculate** to see the breakdown of the loan repayment details:
- Minimum Repayment Amount
- Required Offset Balance
- Weekly Interest Rate
- Number of Weekly Payments
- Principal and Interest Allocation
- Total Interest Payable
- Total Loan & Interest Amount

## Technologies Used
- **Vue.js** (2.6.14)
- **HTML5** & **CSS3** for structure and styling

### Customization

- The calculator can be customized for different loan types or added features (such as displaying repayment schedules).
- You can update the design and user interface according to your needs.

## Contribution

Contributions are welcome! To contribute:

1. Fork this repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

## Feedback

If you have suggestions or find bugs, please open an issue on GitHub or contact us at [dasitha.abeysinghe@gmail.com].

---

Thank you for using the Home Loan Repayment Calculator! 🚀

---
