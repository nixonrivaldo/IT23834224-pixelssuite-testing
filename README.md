# IT23834224 - ITPM Assignment 1 Option 2  
Playwright automation project for PixelsSuite Option 2.

This script verifies that a PNG image can be uploaded to the PixelsSuite image converter and that the preview area is displayed successfully.

---

## 📌 Prerequisites
- Python 3.11 or newer
- Google Chrome OR Playwright Chromium
- Internet connection

---

## ⚙️ Install Dependencies

```bash
python3 -m pip install -U pip
python3 -m pip install -r requirements.txt
python3 -m playwright install chromium

Run The Test
python image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --headless
Optional slower visible run:

python image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000
