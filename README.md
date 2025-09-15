Setup Instructions
Create a new directory for your project

Save the Python code as app.py

Create a templates folder and save the HTML code as templates/index.html

Install required dependencies:

text
                    pip install flask openai
Replace "your-openai-api-key-here" with your actual OpenAI API key

Run the application:

text
python app.py
Open your browser and go to http://localhost:5000

How It Works
The system loads inventory from inventory.json (creates a sample if not exists)

Users enter orders in natural language (e.g., "3 notebooks and 5 pens for John")

The app sends this text to OpenAI API to extract structured order information

The system generates a bill and updates the inventory

Users can download the bill as a CSV file

Sample Inventory
The system starts with a sample inventory:

Notebook: ₹25, Stock: 100

Pen: ₹10, Stock: 200

Pencil: ₹5, Stock: 150

Eraser: ₹5, Stock: 80

Sharpener: ₹8, Stock: 60

Next Steps for Production
Add proper authentication and user management

Implement a database instead of JSON files

Add more robust error handling

Implement voice input using speech-to-text APIs

Add more advanced inventory management features

Implement proper logging

Add tests

This prototype demonstrates the core VyaparAI functionality of converting natural language to bills while managing inventory!

# OpenAI-x-NxtWave-Buildathon
