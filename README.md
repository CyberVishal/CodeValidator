# CodeValidator

![Code Runner Status](https://github.com/CyberVishal/CodeValidator/actions/workflows/run_code.yml/badge.svg)

## About

CodeValidator automatically runs all your scripts (Python, C, C++, Java) in the `scripts/` folder.  
It proves that your code is working without requiring anyone to run it locally.

**Note:** Scripts that require interactive input (like `input()`) **must be modified to use a test value** for the workflow to run successfully. GitHub Actions cannot provide input interactively.

## How to Test Your Code

1. Add your script to the `scripts/` folder.  
2. Push changes to GitHub.  
3. GitHub Actions will automatically run your code.  
4. Check the Actions tab for logs or see the badge above for live status.
