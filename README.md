IT23587106 - ITPM Assignment 1 Option 2
Playwright automation project for PixelsSuite Option 2.

This script verifies that a PNG image can be uploaded to the PixelsSuite image converter and that the preview area is displayed.

Prerequisites
Python 3.11 or newer
Google Chrome, or Playwright Chromium
Install Dependencies
python -m pip install -U pip
python -m pip install -r requirements.txt
python -m playwright install chromium
Run The Test
python image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --headless
Optional slower visible run:

python image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000
Output
After execution, the project writes:

execution_results.csv with the test result row
results/preview_pass.png when the preview is detected
results/preview_fail.png or results/preview_error.png if the test fails
The expected successful result is one CSV data row with status equal to PASS.
