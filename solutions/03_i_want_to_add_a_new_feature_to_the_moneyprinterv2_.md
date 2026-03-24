# I want to add a new feature to the MoneyPrinterV2 tool, but I don't know how to write unit tests for it.

_Write unit tests for a new feature in the MoneyPrinterV2 tool using the unittest framework._

## Steps

1. First, create a new test file in the 'tests' directory with a name that matches the feature you're testing, such as 'test_my_feature.py'.
2. Import the unittest framework and the feature you're testing by adding `import unittest` and `from moneyprinter import my_feature` to the top of the test file.
3. Create a new test class that inherits from unittest.TestCase by adding `class TestMyFeature(unittest.TestCase):`.
4. Define a test method that tests the feature by adding a method with a name that starts with 'test_' and contains an assertion, such as `def test_my_feature(self): self.assertEqual(my_feature(), 'expected_output')`.
5. Run the tests by executing the command `python -m unittest discover` in the project's root directory.

## Pitfalls

- Forgetting to inherit from unittest.TestCase can cause the tests to not be discovered by the unittest framework.