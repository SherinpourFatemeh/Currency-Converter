# Currency Convert Project

The Currency Converter Project is designed to be a practical application leveraging the Python programming language to create a tool that allows users to convert amounts between different currencies. This project utilizes the ExchangeRate-API for fetching real-time exchange rate data and provides an interface for users to specify the amount in one currency and get the equivalent amount in another currency. Additionally, the project features a user-friendly UI using Streamlit, making it accessible for non-technical users to perform currency conversions with ease.


A solution within this project is expected to deliver the following outcomes:

 - **Currency Exchange Rate Retrieval**: Users should be able to input two currencies (e.g., USD and EUR) and retrieve the current exchange rate between them using the ExchangeRate-API.
- **Currency Conversion**: Given an amount in one currency, users should be able to convert it to the equivalent amount in another currency. The program will apply the latest exchange rates to perform this calculation.
- **Graphical User Interface (GUI)**: Built a user-friendly GUI using Streamlit, enabling non-technical users to easily interact with the application and perform operations without needing command-line knowledge




## Requirements
To run this project, you will need the following:

- Python 3.x installed on your machine.
- An internet connection to access the ExchangeRate-API.
- An API key from https://api.exchangerate-api.com to authenticate requests.
- Installation of required Python libraries as listed in the `requirements.txt` file.


## Project Structure

The project is structured as follows:

- `README.md`: This file, which provides an overview of the project and instructions for setup and usage.
- `requirements.txt` : A file listing the dependencies required for this project
- `src` : A directory with all the source code related to that project.

```
.
├── README.md
└── src
    └── main.py
    └── streamlit_Dashboard.py
    
```