# Loan-approval-prediction-
Loan Approval Prediction is a machine-learning-based project that predicts whether a loan application is likely to be approved or rejected based on details such as income, credit score, loan amount, and employment status.
# Loan Approval Prediction

print("=== Loan Approval Prediction System ===")

income = float(input("Enter monthly income: ₹"))
credit_score = int(input("Enter credit score: "))
loan_amount = float(input("Enter loan amount: ₹"))
employment = input("Are you employed? (yes/no): ").lower()

# Simple prediction rules
if income >= 25000 and credit_score >= 650 and loan_amount <= income * 10 and employment == "yes":
    print("\nLoan Status: APPROVED ✅")
else:
    print("\nLoan Status: REJECTED ❌")
