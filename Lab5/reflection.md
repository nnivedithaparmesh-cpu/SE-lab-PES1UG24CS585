\# Lab 5: Static Code Analysis — Reflection



\## 1. What did you learn from this lab?



I learned that static code analysis helps identify potential bugs, security vulnerabilities, and formatting problems without requiring the program to be executed. Pylint checks code quality, Bandit focuses on security issues, and Flake8 checks Python style and formatting.



\## 2. Which issue was the most important to fix, and why?



The unsafe use of `subprocess` with `shell=True` was especially important because it can introduce command-injection risks. Removing the unsafe code reduced this potential security risk.



\## 3. How did the tools improve the program?



Pylint helped improve documentation, naming conventions, return consistency, and function design. Bandit helped identify unsafe coding patterns. Flake8 identified whitespace and line-length violations. After fixing the reported issues, the Pylint score increased from 4.80/10 to 10.00/10, and the final Bandit and Flake8 reports showed no issues.



\## 4. What difficulties did you encounter?



Some findings required understanding the reason behind a warning before changing the code. I also had to ensure that the fixes did not break the program's functionality. Running the tools again after making changes helped verify the results.



\## 5. How will you use static analysis in future projects?



I will use static analysis tools during development and before submitting code. Running these checks regularly can help identify problems early, improve maintainability, and reduce security risks.



