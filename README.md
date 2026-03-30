# Agroassist:Crop-Protection-system

**How To Run:**

3. Create Virtual Environment (Recommended)
```
python -m venv venv
```
Activate it:

Windows:
```
venv\Scripts\activate
```
Mac/Linux:
```
source venv/bin/activate
```
4. Install Dependencies

There is a requirements.txt file in the repo.
```
pip install -r requirements.txt
```
This installs all required libraries (Flask, requests, etc.).

5. Run the Project

The repo has:
```
app.py
app2.py
```
Start with:
```
python app.py
```
If that doesn’t work:
```
python app2.py
```
6. Open in Browser

After running, you’ll see something like:
```
Running on http://127.0.0.1:5000/
```
Open this in your browser:
```
http://127.0.0.1:5000/
```

**How to Use:**

Get Real-Time Weather Updates:

Input your location or allow location services to receive a detailed 5-day weather forecast. Check the forecast daily to plan planting, irrigation, or harvests accordingly.
Select Preferred Language:

Choose your language from the dropdown menu for easy accessibility. AgroAssist supports multiple languages to ensure that every farmer can use the platform comfortably.
Receive Crop Recommendations:

Enter details about your region and soil type to get AI-driven recommendations on which crops to plant. The system will suggest crops best suited to your land, climate, and local market trends.
Chat with AgroBot:

Have a farming-related question? Simply type it into the AgroBot chat. The chatbot will provide instant answers on topics ranging from crop care to pest management.
Monitor Your Soil Health:

Input soil test data into the soil health monitoring feature. AgroAssist will analyze the data and generate a report, offering actionable tips to improve your soil’s fertility and health.
Spraying and Pest Control Recommendations:

Based on your crops and local conditions, AgroAssist will generate a customized spraying schedule to help protect your crops from diseases and pests.
