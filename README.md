# Brand Sustainability Analysis

## Overview

This is a Streamlit web application that allows users to analyze the sustainability of their favorite brands. The application utilizes the Google Gemini-Pro AI model to gather and process information from various sources, including corporate sustainability reports, news articles, and online reviews. The analysis highlights the brand's efforts in areas such as energy efficiency, waste reduction, and ethical sourcing, enabling users to support environmentally responsible companies.

## Features

1. **Chatbot Interface**: The application features a chatbot-like interface where users can input their questions or prompts about a specific brand. The Gemini-Pro AI model will then provide a detailed analysis of the brand's sustainability practices.

2. **Sustainability Score**: The application calculates a sustainability score for the brand based on the information gathered by the AI model. This score is displayed in a gauge meter, providing a visual representation of the brand's environmental impact.

3. **Customizable Prompts**: The initial prompt used to generate the brand analysis can be customized to suit the user's specific needs or preferences.

4. **Responsive Design**: The application is designed to be responsive, ensuring a seamless user experience across different devices and screen sizes.

## Usage

1. **Set up the Development Environment**:
   - You can use the provided development container configuration to set up the development environment with the necessary dependencies.
   - Alternatively, you can create a virtual environment and install the required packages manually.

2. **Obtain the Google API Key**:
   - To use the Google Gemini-Pro AI model, you'll need to obtain a valid API key.
   - Update the `GOOGLE_API_KEY` variable in the `Hello.py` file with your API key.

3. **Run the Application**:
   - Start the Streamlit server by running the following command in your terminal:
     ```
     streamlit run Hello.py
     ```
   - The application will open in your default web browser, and you can start analyzing brands.

4. **Interact with the Chatbot**:
   - In the chatbot interface, enter the name of the brand you want to analyze.
   - The Gemini-Pro AI model will generate a detailed analysis of the brand's sustainability practices, and the sustainability score will be displayed in the gauge meter.

## Dependencies

The application relies on the following Python libraries:

- `streamlit`: For building the web application.
- `google.generativeai`: For accessing the Google Gemini-Pro AI model.
- `plotly.graph_objects`: For creating the sustainability score gauge meter.
- `re`: For parsing the sustainability score from the Gemini-Pro response.

These dependencies are listed in the `requirements.txt` file, which can be used to install the necessary packages.

## Customization

You can customize the application by modifying the following elements:

1. **Initial Prompt**: The `initial_prompt` variable in the `Hello.py` file contains the initial prompt used to generate the brand analysis. You can modify this prompt to suit your specific needs or preferences.

2. **Sustainability Score Calculation**: The code that parses the sustainability score from the Gemini-Pro response can be modified to adapt to any changes in the response format.

3. **UI Customization**: You can further customize the user interface by modifying the Streamlit settings and components, such as the page title, favicon, and layout.

## License

This project is licensed under the [Apache License, Version 2.0](LICENSE).
