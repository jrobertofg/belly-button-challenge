# belly-button-challenge

##Background


"In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare."

Eve though the analyisis is important the important thing in this challenge is the web dashboard excersice using JAVA, HTML and JSON
The dashboard allows the user to explore interactive charts that display the data, including a demographic info panel, a bar chart of top bacterial cultures found, and a bubble chart of bacteria cultures per sample.
The user will be able to Select the information by subject and prove a change of information shown in the dashboard. 
When mouse is on top of the graph a label will be shown for the user to know what data he is observing. 

## Features
As mentioned before it includes the following:
- **Interactive Dropdown Menu**: Select a test subject ID to view their specific data.
- **Demographic Info Panel**: Displays demographic information about the selected test subject.
- **Bar Chart**: Shows the top 10 bacterial cultures found in the selected test subject's navel.
- **Bubble Chart**: Displays the bacteria cultures per sample for the selected test subject.

## Setup Instructions

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/belly-button-biodiversity.git
    cd belly-button-biodiversity
    ```

2. **Ensure you have Python or Node.js installed**:
    - Python (for a simple HTTP server)
    - Node.js (for http-server)

3. **Start a Local Server**:

    - **Using Python**:
        ```bash
        python -m http.server 5500
        ```

    - **Using Node.js (http-server)**:
        ```bash
        npm install -g http-server
        http-server -p 5500
        ```

4. **Open your browser** and navigate to:
    ```
    http://localhost:5500
    ```

## Usage

1. **Select a Test Subject**:
    - Use the dropdown menu to select a test subject ID. The charts and demographic info panel will update to reflect the selected test subject's data.

2. **Explore the Data**:
    - The demographic info panel displays information about the selected test subject.
    - The bar chart shows the top 10 bacterial cultures found in the selected test subject's navel.
    - The bubble chart visualizes all bacterial cultures per sample for the selected test subject.

## File Structure


![image](https://github.com/jrobertofg/belly-button-challenge/assets/27827806/24381514-2984-4378-878e-5648fcb9528a)

![image](https://github.com/jrobertofg/belly-button-challenge/assets/27827806/4df42472-173e-43fa-b6ac-39a377bfc2a4)

