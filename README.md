# Dynamic Certificate Generator

This project automates the generation of certificates using Python. It takes a list of names and generates personalized certificates based on a provided template.

## Features

- Dynamically generates certificates with custom names.
- Uses a certificate template and positions text accurately.
- Outputs certificates as `.png` images.
  
## Prerequisites

- Python 3.x
- Pillow library

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/the-main-method/Dynamic-Certificate-Generator.git
   ```

2. Navigate into the project folder:

   ```
   cd Dynamic-Certificate-Generator
   ```

3. Install the required Python packages:

   ```
   pip install pillow
   ```

## Usage

1. Place your certificate template (e.g., `certificate_template.png`) and font file (e.g., `arial.ttf`) in the root directory.
2. Add the list of names in `names.txt`, with each name on a new line.

3. Run the script:

   ```
   python generate_certificates.py
   ```

   This will generate a certificate for each name in the list and save them in the `certificates` folder.

## Customization

- **Font size**: Modify the font size in the `generate_certificate` function by adjusting the `font` argument in the script.
- **Text position**: The text is automatically centered, but you can modify the `position` variable to customize placement.

- ## Example

Here’s an example of how the certificate will look:

![Certificate Example](example.png)



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

