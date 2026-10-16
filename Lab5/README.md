\# Lab 5: Static Code Analysis



\## Objective

Analyze and improve the smart home Python program using Pylint, Bandit, and Flake8.



\## Tools Used

\- \*\*Pylint:\*\* Checks Python code quality, naming conventions, documentation, and potential errors.

\- \*\*Bandit:\*\* Identifies potential security issues.

\- \*\*Flake8:\*\* Checks Python style and formatting.



\## Files

\- `smart\_home.py` — corrected Python program.

\- `pylint\_before.txt` and `pylint\_after.txt` — Pylint reports.

\- `bandit\_before.txt` and `bandit\_after.txt` — Bandit reports.

\- `flake8\_before.txt` and `flake8\_after.txt` — Flake8 reports.



\## Results

\- Pylint score improved from 4.80/10 to 10.00/10.

\- Bandit reported no issues after the fixes.

\- Flake8 reported no remaining violations after the fixes.



\## Issues Addressed

\- Added module and function docstrings.

\- Improved naming conventions and return consistency.

\- Replaced a mutable default argument with `None`.

\- Specified file encoding.

\- Removed unsafe subprocess usage.

\- Changed the hub address to the loopback address.

\- Corrected whitespace and line-length issues.



\## Reflection

Static analysis helped identify code-quality, security, and formatting problems. Fixing these findings improved the readability and maintainability of the program and reduced potential security risks.



