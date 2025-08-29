# CodeValidator

![Code Runner Status](https://github.com/CyberVishal/CodeValidator/actions/workflows/run_code.yml/badge.svg)

## About

CodeValidator automatically runs all your scripts (Python, C, C++, Java) in the `scripts/` folder.  
It proves that your code is working without requiring anyone to run it locally.

**Note:** Scripts that require interactive input (like `input()` in Python) **must be modified to use a test value** for the workflow to run successfully. GitHub Actions cannot provide input interactively.

## How to Test Your Code

1. Add your script to the `scripts/` folder.  
2. Rename files to avoid extra dots/spaces:  
   - Examples: `CTest.c`, `C++test.cpp`, `Test.java`, `test_trigger.py`  
3. Make sure **Java class names match filenames** exactly.  
4. Push changes to GitHub.  
5. GitHub Actions will automatically run your code.  
6. Check the **Actions tab** for logs or see the **badge above** for live status.
