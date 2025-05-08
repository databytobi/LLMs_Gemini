# Image Analysis Using Gemini

This project focuses on leveraging **Gemini** and advanced prompting techniques to analyze images and uncover valuable insights. By utilizing the **Gemini-2.0-flesh** model, the project demonstrates how state-of-the-art AI can be applied for detailed image analysis.

---

## Overview

The project is designed to:
- Analyze images using **Gemini-2.0-flesh**.
- Extract meaningful insights from images through prompting techniques.
- Showcase the capabilities of AI-driven image analysis.

Gemini, with its advanced natural language understanding and image processing capabilities, forms the backbone of this project.

---

## Libraries and Tools Used

The project utilizes the following libraries and tools:
- **Core Libraries**:
  - `os`
  - `time`
  - `glob` (from `fglob`)
  - `datetime`
  - `warnings`
- **Image Processing**:
  - `PIL` (Pillow) for image manipulation
- **Visualization**:
  - `IPython.display` (for Markdown and displaying images)
- **Gemini Model**:
  - **Gemini-2.0-flesh**: The core model used for image analysis
- **Prompting Techniques**:
  - Advanced prompting methodologies to effectively query the model for insights

---

## Features

- **Image Analysis**: Analyze images and extract insights using the Gemini model.
- **Prompt-Based Insights**: Use tailored prompts to uncover specific details and insights from images.
- **Customizable Queries**: Flexible prompting for user-defined analysis goals.

---

## Installation

### Prerequisites

To run this project, ensure you have access to the **Gemini-2.0-flesh** model and the necessary API keys or permissions.

1. Clone this repository:
   ```bash
   git clone https://github.com/databytobi/image-analysis-using-gemini.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up access to the Gemini model by configuring your API key in the environment variables:
   ```bash
   export GEMINI_API_KEY="your_api_key_here"
   ```

---

## Usage

1. Run the main script to analyze images:
   ```bash
   python main.py --image_path path/to/your/image.jpg
   ```
2. Use custom
