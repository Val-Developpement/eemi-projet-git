# Validataurus

**Validataurus** is a powerful and flexible Python package designed to validate various types of data easily and efficiently. Whether you're building web applications, handling user input, or working with data pipelines, Validataurus ensures your data is clean, secure, and properly formatted.

---

## Features

- **Email Validation**: Verify the format and domain of email addresses.
- **Password Security**: Assess password strength with customizable security rules.
- **Phone Numbers**: Validate phone numbers for proper formatting and potential regions.
- **Birth Dates**: Ensure valid and realistic dates of birth.
- **Credit Card Validation**: Check the format and validity of credit card numbers.

---

## Installation

You can install Validataurus using pip:

```bash
pip install validataurus
```

---

## Usage

# TODO: Add usage examples

### Testing
Make sure the project is installed before running the tests:
```bash
make tests
```

---

## User Stories

>### User Story 1: Email Validation
>
>As a user, I want to verify if an email address is valid so that I can ensure it can be used for registrations or communications.
>
>Acceptance Criteria:
>	•	Valid Format: The email address must follow the standard format (e.g., user@example.com).\
>	•	Valid Domains: Domains must include a domain name and an extension (e.g., .com, .org).\
>	•	Invalid Values:\
>	  •	An empty string or one without @ should be considered invalid.\
>	  •	Emails without a domain extension should be rejected.

>### User Story 2: Password Strength
>
>As a user, I want to verify if a password meets security criteria to ensure my personal information is protected.
>
>Acceptance Criteria:
>	•	Minimum Length: The password must be at least 8 characters long.\
>	•	Complexity Requirements:\
>	  •	At least one uppercase letter.\
>	  •	At least one lowercase letter.\
>	  •	At least one digit.\
>	  •	At least one special character (e.g., @, !, %).\
> •	Weak Password: A password failing any of the above criteria is considered weak.

>### User Story 3: Phone Number Validation
>
>As a user, I want to verify if a phone number is valid and correctly formatted to ensure it can be used for calls or SMS.
>
>Acceptance Criteria:
>	•	International Format: The number must include a country code (e.g., +1, +33).\
>	•	Regional Validity: The number must follow the specific rules of the associated region.\
>	•	Invalid Values:\
>	  •	Empty strings or numbers without a country code should be rejected.\
>	  •	Numbers containing letters or non-numeric symbols should be rejected.

>### User Story 4: Birth Date Validation
>
>As a user, I want to verify if a birth date is valid to ensure it is realistic and can be used in forms or identification systems.
>
>Acceptance Criteria:
>	•	Valid Format: The date must be in the DD-MM-YYYY format.\
>	•	Realistic Date: The birth date cannot be in the future.\
>	•	Invalid Dates:\
>	  •	An empty string or a date in the wrong format (e.g., DD/MM/YYYY, YYYY-MM-DD) should be rejected.\
>	  •	Impossible dates (e.g., 2023-02-30) should be rejected.

>### User Story 5: Credit Card Validation
>
>As a user, I want to verify if a credit card number is valid to ensure it can be used for transactions.
>
>Acceptance Criteria:
>	•	Valid Format: The number must have between 13 and 19 digits, either with or without spaces between groups of 4 digits.\
>	•	Validity: The number must pass the Luhn algorithm test.\
>	•	Invalid Values:\
>	  •	Strings containing non-numeric characters should be rejected.\
>	  •	Card numbers failing the Luhn test should be rejected.
