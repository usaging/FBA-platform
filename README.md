# FBA-platform
The platform is a web-based application designed to provide FBA (Flux Balance Analysis) calculations and gene knockout prediction capabilities for metabolic networks. Users can use the built-in chassis cell model, upload a local SBML file, or download the model via the integrated BiGG interface. The results of the calculations will be presented in a visual form, helping the user to intuitively understand the analysis results.

# Features
- **Model management**: Users can upload local SBML model files, or download models through the BiGG database interface, and manage them on the platform.
- **FBA calculations**: Flux equilibrium analysis is performed on selected models to calculate metabolic flow distributions.
- **Gene knockout prediction**: Simulate the impact of knockout of specific genes on metabolic networks and predict system behavior changes.
- **Visualization of results**: The results of FBA calculation and gene knockout are displayed graphically for users to analyze and interpret.

# Technology Stack

# Directory structure

# Get started quickly
## Prerequisites
Install Docker and Docker Compose.

## Deployment steps

1. Clone the Repository

`git clone https://github.com/yourusername/fba-platform.git
cd fba-platform`

2. Start Services

Use Docker Compose to start the frontend and backend services along with related dependencies:

`docker-compose up --build`

3. Access the Application

Open `http://localhost:6666` in your browser to access the frontend interface.

# User Guide
## Model Management
Upload Model: On the "Model Management" page, click the "Upload Model" button, select a local SBML file to upload.

Download Model: On the "Model Management" page, enter the model ID from the BiGG database, click the "Download Model" button, and the system will automatically download and import the model from BiGG.

## FBA Calculation

On the "FBA Calculation" page, select an imported model, set the necessary parameters, and click the "Start Calculation" button. 
The system will perform FBA analysis and display the results.

## Gene Knockout Prediction

On the "Gene Knockout" page, select a model, specify the gene to be knocked out, and click the "Predict" button. 
The system will simulate the impact of the gene knockout and display the results.

## Results Visualization

All calculation results will be displayed in graphical formats on the corresponding pages, allowing users to intuitively view and analyze them.

# Contribution Guide
We welcome suggestions or code contributions to this project. Please follow these steps:
1. Fork the Repository
2. Create a Branch: git checkout -b feature/your-feature
3. Commit Changes: git commit -m 'Add some feature'
4. Push to Branch: git push origin feature/your-feature
5. Create a Pull Request

# License
This project is licensed under the MIT license.
