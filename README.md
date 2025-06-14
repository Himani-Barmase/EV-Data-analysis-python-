# EV-Data-analysis-python-
The project involves various data analysis techniques, including data filtering, grouping, aggregation, outlier detection, and statistical hypothesis testing. A key component is also the development of an EV recommendation system.
# Electric Vehicle (EV) Data Analysis Project

## Project Overview

This project involves a thorough analysis of an electric vehicle (EV) dataset to uncover meaningful insights, perform hypothesis testing, and provide actionable recommendations. The core objective is to understand various aspects of EVs, from pricing and performance to energy consumption and range, and to build a recommendation system for potential buyers.

## Dataset

[cite_start]The analysis is performed on the `FEV-data-Excel.xlsx` dataset. This dataset contains various features related to electric vehicles, including:

* [cite_start]**Car full name**: The full name or designation of the vehicle, often combining make, model, and variant.
* [cite_start]**Make**: The brand or manufacturer of the car.
* [cite_start]**Model**: The specific model or version of the car.
* [cite_start]**Minimal price (gross) [PLN]**: The minimum retail price of the car, in Polish złoty (PLN).
* [cite_start]**Engine power [KM]**: The car's engine power, measured in horsepower (KM in Polish).
* [cite_start]**Maximum torque [Nm]**: The peak torque the engine can produce, measured in Newton-meters (Nm).
* [cite_start]**Type of brakes**: The braking system used, such as disc or drum brakes.
* [cite_start]**Drive type**: The drivetrain configuration, like FWD (front-wheel drive), RWD (rear-wheel drive), or AWD (all-wheel drive).
* [cite_start]**Battery capacity [kWh]**: Total energy capacity of the car's battery, measured in kilowatt-hours (kWh).
* [cite_start]**Range (WLTP) [km]**: Estimated driving range on a full charge under WLTP standards, in kilometers.
* [cite_start]**Wheelbase [cm]**: The distance between the front and rear axles, in centimeters.
* [cite_start]**Length [cm]**: The overall length of the car, in centimeters.
* [cite_start]**Width [cm]**: The car's width, in centimeters.
* [cite_start]**Height [cm]**: The car's height, in centimeters.
* [cite_start]**Minimal empty weight [kg]**: The car's minimum weight when empty, measured in kilograms.
* [cite_start]**Permissible gross weight [kg]**: Maximum legally allowed weight, including passengers and cargo, in kilograms.
* [cite_start]**Maximum load capacity [kg]**: The maximum weight the car can carry, in kilograms.
* [cite_start]**Number of seats**: The number of passenger seats in the car.
* [cite_start]**Number of doors**: The number of doors on the car.
* [cite_start]**Tire size [in]**: The tire size, measured in inches.
* [cite_start]**Maximum speed [kph]**: The top speed of the car, in kilometers per hour.
* [cite_start]**Boot capacity (VDA) [l]**: Trunk or cargo space capacity, measured in liters according to VDA standards.
* [cite_start]**Acceleration 0-100 kph [s]**: Time taken to accelerate from 0 to 100 kilometers per hour, in seconds.
* [cite_start]**Maximum DC charging power [kW]**: The highest charging power supported when using a DC fast charger, in kilowatts (kW).
* [cite_start]**Mean - Energy consumption [kWh/100 km]**: Average energy consumption per 100 kilometers, in kilowatt-hours (kWh).

## Project Tasks and Deliverables

The project addresses several key analytical tasks:

### Task 1: Budget and Range Filtering
* [cite_start]Filtering EVs that meet specific customer criteria: a budget of 350,000 PLN and a minimum range of 400 km.
* [cite_start]Grouping the filtered EVs by manufacturer (Make).
* [cite_start]Calculating the average battery capacity for each manufacturer in the filtered set.

### Task 2: Outlier Detection in Energy Consumption
* [cite_start]Identifying outliers in the `Mean - Energy consumption [kWh/100 km]` column to find EVs with unusually high or low energy consumption.

### Task 3: Battery Capacity vs. Range Relationship
* [cite_start]Creating a suitable plot to visualize the relationship between `Battery capacity [kWh]` and `Range (WLTP) [km]`.
* [cite_start]Highlighting insights derived from this visualization.

### Task 4: EV Recommendation Class
* [cite_start]Building a Python class that allows users to input their budget, desired range, and battery capacity.
* [cite_start]The class returns the top three EVs matching the user's criteria.

### Task 5: Inferential Statistics - Hypothesis Testing
* [cite_start]Conducting a two-sample t-test (using `ttest_ind` from `scipy.stats`) to determine if there is a significant difference in the average `Engine power [KM]` between vehicles manufactured by Tesla and Audi.
* [cite_start]Drawing insights, recommendations, and conclusions from the test results.

## Technologies Used

* [cite_start]Python 
* [cite_start]Pandas 
* [cite_start]NumPy 
* [cite_start]SciPy 
* [cite_start]Matplotlib (for visualizations) 
* Any other relevant libraries used in the `python project.ipynb` notebook.

## How to Run the Project

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/EV-Data-Analysis-Project.git](https://github.com/YourUsername/EV-Data-Analysis-Project.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd EV-Data-Analysis-Project
    ```
3.  **Ensure you have Jupyter Notebook and the required libraries installed.** If not, you can install them via pip:
    ```bash
    pip install jupyter pandas numpy scipy matplotlib
    ```
4.  **Place the dataset:** Make sure the `FEV-data-Excel.xlsx` file is in the same directory as the `python project.ipynb` notebook.
5.  **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook python project.ipynb
    ```




[cite_start](Please note: The video is less than 5 minutes in length and clearly shows the presenter's face as per project guidelines.)

## Disclaimer

This project was completed as part of the Internshala Trainings program. [cite_start]Plagiarism is strictly prohibited and will result in penalties. [cite_start]The project is evaluated based on the quality of analysis, depth of insights, and feasibility of recommendations.
