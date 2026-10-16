\# Lab 5: Static Code Analysis — Issue Table



| No. | Tool | Issue identified | Type / Severity | Fix applied |

|---:|---|---|---|---|

| 1 | Pylint | Mutable default argument `{}` in `add\_device()` | Code quality / potential bug | Changed the default to `None` and initialized an empty dictionary inside the function. |

| 2 | Pylint | Missing module and function docstrings | Code quality | Added docstrings describing the module and functions. |

| 3 | Pylint | Function and argument naming did not follow Python naming conventions | Code style | Updated names to use `snake\_case`. |

| 4 | Pylint | Inconsistent return values in `toggle\_device()` | Code quality | Made the function return a consistent type of result for successful and unsuccessful operations. |

| 5 | Pylint | File opened without explicitly specifying its encoding | Code quality / portability | Added `encoding="utf-8"` to the `open()` call. |

| 6 | Bandit | Use of `subprocess` with `shell=True` | High severity | Removed the unsafe subprocess usage. |

| 7 | Bandit | Hub bound to `0.0.0.0` | Medium severity | Changed the hub host to `127.0.0.1` for loopback access. |

| 8 | Bandit | Hardcoded password in source code | Low severity | Removed the hardcoded password. |

| 9 | Bandit | Import of `subprocess` | Low severity | Removed the unused import along with the unsafe subprocess code. |

| 10 | Flake8 | Whitespace before a colon (E203) | Formatting | Corrected the whitespace. |

| 11 | Flake8 | Incorrect blank-line spacing (E302) | Formatting | Corrected function spacing. |

| 12 | Flake8 | Incorrect spacing before an inline comment (E261) | Formatting | Corrected the comment spacing. |

| 13 | Flake8 | Line exceeded the configured maximum length (E501) | Formatting | Split the long line across multiple lines. |



\## Verification



\- Pylint score improved from 4.80/10 to 10.00/10.

\- Bandit reported no issues after the fixes.

\- Flake8 reported no remaining violations after the fixes.



The updated program was executed to verify that it still produced the expected demo output.



