# GuitarBot - Music Store Order Collection

GuitarBot is an automated service designed to collect orders for a music store using OpenAI's GPT-3.5-turbo. This project showcases the integration of OpenAI's conversational AI with a graphical user interface (GUI) created using the Panel library. GuitarBot interacts with customers to take orders for guitars and related accessories, providing a seamless and interactive shopping experience.

## Features

- Interactive conversational interface for collecting music store orders.
- Supports a variety of guitar models and accessories.
- Summarizes orders in JSON format for easy processing.
- User-friendly GUI with real-time interaction.

## Setup and Installation

### Prerequisites

- Python 3.7 or higher
- An OpenAI API key
- Virtual environment (optional but recommended)

### Installation Steps

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/GuitarBot.git
    cd GuitarBot
    ```

2. **Create and Activate Virtual Environment** (optional):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set Up Environment Variables**:
    Create a `.env` file in the project root directory and add your OpenAI API key:
    ```plaintext
    OPENAI_API_KEY=your_openai_api_key_here
    ```

## Usage

1. **Run the Application**:
    ```bash
    jupyter notebook GuitarBot.ipynb
    ```
    Open the Jupyter Notebook and run the cells to start the GuitarBot application.

2. **Interact with GuitarBot**:
    - Enter your text in the input field and click the "Chat!" button.
    - GuitarBot will respond and guide you through the order process.
