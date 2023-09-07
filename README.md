# EXTRACT PHONE NUMBERS FROM IMAGES TO EXCEL

# Description

This project extract phone numbers from images. phone numbers must be in this pattern

pattern = r'\+?\d{1,3} \d{3,6} \d{3,6}'

starting with +
1-3 digit code
space
3-6 digit block
space
3-6 digit block

e.g.
+123 4567 8901

## Installation

1. Clone the repository:

   ```bash
   git clone [https://github.com/farrukh47/Img_2_Excel]
   ```
2. Navigate to the project directory:

   ```bash
   cd [Img_2_Excel]
   ```
3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the script, use the following command:

```bash
python main.py
```

## Contribution

Contributions are welcome! Please fork the repository and open a pull request to add enhancements or fix issues.

## License

[MIT](LICENSE)
