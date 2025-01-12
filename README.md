# Optimizing-Healthcare-Appointment-Scheduling-Insights-from-Medical-Appointments-Data
The notebook performs an Exploratory Data Analysis (EDA) on a medical appointments dataset.
he file contains a Jupyter notebook with Python code for exploratory data analysis (EDA) on medical appointments data. Based on the initial content, it includes imports for various libraries like pandas, numpy, matplotlib, seaborn, and others, which are typically used for data manipulation and visualization.

Libraries Used: The notebook imports essential libraries for data manipulation and visualization such as pandas, numpy, matplotlib, seaborn, and datetime.
Dataset: The data is loaded using pd.read_csv() from a file named 'Data.csv', containing columns such as PatientId, AppointmentID, Gender, ScheduledDay, AppointmentDay, Age, Neighbourhood, Scholarship, and various health-related conditions (e.g., Hypertension, Diabetes).
Data Inspection: The notebook begins by displaying the first few rows of the dataset using base_data.head(5) to examine the structure of the data.
Weekday Extraction: The code extracts the weekdays from the ScheduledDay and AppointmentDay columns to create new columns sch_weekday and app_weekday representing the weekday of each appointment.
This setup is foundational for further analysis and visualization, likely to explore trends, cancellations, and no-show rates across different weekdays, patient demographics, and health conditions.
