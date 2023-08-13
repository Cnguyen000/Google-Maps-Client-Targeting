# Google Maps Client Targeting Project

Address Extraction Automation for Google Maps Queries

This project involves the an automated solution to extract addresses from Google Maps queries. By using Google Maps API, the project streamlines the process of collecting and organizing address information for specific queries. The automation is achieved through Python, enabling data retrieval and processing. This project showcases skills in API integration, data manipulation, and automation, contributing to the field of location-based data processing.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone repository to local machine using command:
git clone https://github.com/Cnguyen000/GeorgiaHPI.git

2. Navigate to project directory:
cd GeorgiaHPI

3. Install the required dependencies:
pip install -r requirements.txt


4. Obtain Google Maps API key by following the instructions [here](https://developers.google.com/maps/gmp-get-started#create-project).

5. Create a file named `config.py` in the project directory and add your API key:
```python
# config.py
API_KEY = "your-google-maps-api-key"

## Usage

Run the script by executing the following command:

python extract_addresses.py
Follow the on-screen prompts to provide the necessary information for the Google Maps query.

The script will automate querying Google Maps, extracting addresses, and saving the results in a structured format.

The addresses will be saved to an output file (e.g., output_addresses.xlsx) in the project directory.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and test them.
Commit your changes with descriptive messages.
Push your changes to your forked repository.
Create a pull request detailing your changes.

## License

This project is licensed under the MIT License.

Contact: cgnuyenjobs@gmail.com
