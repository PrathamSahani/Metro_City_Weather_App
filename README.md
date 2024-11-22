# Metro_City_Weather_App
🌆 With this web app stay updated with real-time weather updates for your city, right at your fingertips! 🌦️

Welcome to **Real-Time Data Processing System for Weather Monitoring**! This project fetches real-time weather data, processes it, and provides rollups and aggregates for efficient monitoring. Follow the steps below to set up and run the project.
- Extract the folder into an empty directory of your choice.

1. **Install Python**  
   Make sure Python is installed on your system. Download it from the [official Python website](https://www.python.org/downloads/).

   ```bash
   # Check if Python is installed
   python --version

2. **setup Django**

 ```bash
   #  Django is installed
   pip install django

   # Verify the installation
   django-admin --version
```

### 2️⃣ Set Up Your Virtual Environment (Optional)
To avoid dependency issues, it is recommended to create a virtual environment. Here's how:
1. Open the extracted folder in **VS Code**.
2. In the terminal, create the virtual environment:
   ```bash
   python -m venv env
   ```
3. Activate the virtual environment:
   ```bash
   .\env\Scripts\activate.ps1
   ```

### 3️⃣ Install Dependencies
Once inside the virtual environment, install Django:
```bash
pip install django
```

### 4️⃣ Navigate to the Project Directory
Change to the `weather_monitor` directory where the `manage.py` file is located:
```bash
cd weather_monitor
```

### 5️⃣ Migrate the Database
Apply database migrations using the following commands:
```bash
python manage.py makemigrations
python manage.py migrate
```

### 6️⃣ Create a Superuser 
You can create a superuser to manage the database via Django's admin panel: 
```bash
python manage.py createsuperuser
```
- Follow the prompts to add a username and password of your choice. To access the admin panel you can visit to http://127.0.0.1:8000/admin/ url and see database.

## 🌐 Real-Time Weather Monitoring

- The system retrieves real-time temperature data from **OpenWeatherAPI** every five minutes. To obtain the temperature of any metro city, simply click the corresponding city button, and the weather report will be displayed automatically.

![1](https://github.com/user-attachments/assets/69d2a8c6-8c6b-4451-a405-633d84c15658)

-The summary data is updated dynamically each time the page is refreshed. By clicking the View All Summary button, you can view a summary of the temperatures for the various cities displayed below.

![2](https://github.com/user-attachments/assets/346834a9-9e89-455c-9f0b-65f4e1004462)

---
- By clicking on the **Alerts** button we can know the Temperature is execced or not.

![alerts](https://github.com/user-attachments/assets/f2c073a9-1c58-4a0b-a4f6-1f6417608d40)

By following these steps, you can successfully set up and run the weather monitoring system with real-time data and efficient processing. 

## 📽️ Troubleshooting
If you face any issues during the setup, please refer to the project video tutorial for further assistance.

---

Feel free to enhance the project and explore its capabilities! 😊


