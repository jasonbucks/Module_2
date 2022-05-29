# Module_2_Challenge - Loan Qualifier Application

"This is a python command-line interface application that allows users to see qualifying loans from lenders quickly and easily. The application works by taking in a `daily_rate_sheet` of loan criteria from various loan providers, asking the user a number of questions to evaluate their loan eligibility, and then returning to them a list of qualifying loans." 

The preceding quote was taken from the solution for an earlier exercise.  The `daily_rate_sheet` will be in CSV format.  The main criteria for determining loan eligibility will be the loan applicant's credit score and debt-to-income ratio, plus the size of the loan as well as the loan-to-home_value ratio.

This application has been updated from the original to allow the user the option to create an output file and, if so, name the output file themselves.

---

## Technologies

This project leverages python 3.9.7 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

The preceding lines were taken from the solution for an earlier exercise, edited only to reflect a slightly newer version of Python being employed.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
```

---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```

Upon launching the loan qualifier application you will be greeted with the following prompts:

![Loan Qualifier Prompts](images/app_user_input_screenshot.png)

If there are no qualifying loans available to the user, the screen will look similar to this:

![Loan Qualifier Prompts](images/app_user_input_screenshot_3.png)

If there are qualifying loans, the screen will look either like this, if an output file is chosen by the user:

![Loan Qualifier Prompts](images/app_user_input_screenshot_2.png)

...or like this, if no output file was selected:

![Loan Qualifier Prompts](images/app_user_input_screenshot_4.png)

---

## Contributors

Brought to you by the instructors and assistants of the UW FinTech Boot Camp, with edits made by Jason Buckholt allow for output file usability.

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.

For now, only a License to Ill is needed.
