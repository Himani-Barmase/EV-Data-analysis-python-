# Electric Vehicle (EV) Data Analysis Project

## Project Overview

This project involves a thorough analysis of an electric vehicle (EV) dataset to uncover meaningful insights, perform hypothesis testing, and provide actionable recommendations. The core objective is to understand various aspects of EVs, from pricing and performance to energy consumption and range, and to build a recommendation system for potential buyers.

## Dataset

The analysis is performed on the `FEV-data-Excel.xlsx` dataset. This dataset contains various features related to electric vehicles, including:

* **Car full name**: The full name or designation of the vehicle, often combining make, model, and variant.
* **Make**: The brand or manufacturer of the car.
* **Model**: The specific model or version of the car.
* **Minimal price (gross) [PLN]**: The minimum retail price of the car, in Polish złoty (PLN).
* **Engine power [KM]**: The car's engine power, measured in horsepower (KM in Polish).
* **Maximum torque [Nm]**: The peak torque the engine can produce, measured in Newton-meters (Nm).
* **Type of brakes**: The braking system used, such as disc or drum brakes.
* **Drive type**: The drivetrain configuration, like FWD (front-wheel drive), RWD (rear-wheel drive), or AWD (all-wheel drive).
* **Battery capacity [kWh]**: Total energy capacity of the car's battery, measured in kilowatt-hours (kWh).
* **Range (WLTP) [km]**: Estimated driving range on a full charge under WLTP standards, in kilometers.
* **Wheelbase [cm]**: The distance between the front and rear axles, in centimeters.
* **Length [cm]**: The overall length of the car, in centimeters.
* **Width [cm]**: The car's width, in centimeters.
* **Height [cm]**: The car's height, in centimeters.
* **Minimal empty weight [kg]**: The car's minimum weight when empty, measured in kilograms.
* **Permissible gross weight [kg]**: Maximum legally allowed weight, including passengers and cargo, in kilograms.
* **Maximum load capacity [kg]**: The maximum weight the car can carry, in kilograms.
* **Number of seats**: The number of passenger seats in the car.
* **Number of doors**: The number of doors on the car.
* **Tire size [in]**: The tire size, measured in inches.
* **Maximum speed [kph]**: The top speed of the car, in kilometers per hour.
* **Boot capacity (VDA) [l]**: Trunk or cargo space capacity, measured in liters according to VDA standards.
* **Acceleration 0-100 kph [s]**: Time taken to accelerate from 0 to 100 kilometers per hour, in seconds.
* **Maximum DC charging power [kW]**: The highest charging power supported when using a DC fast charger, in kilowatts (kW).
* **Mean - Energy consumption [kWh/100 km]**: Average energy consumption per 100 kilometers, in kilowatt-hours (kWh).

## Project Tasks and Deliverables

The project addresses several key analytical tasks:

### Task 1: Budget and Range Filtering
* Filtering EVs that meet specific customer criteria: a budget of 350,000 PLN and a minimum range of 400 km.
* Grouping the filtered EVs by manufacturer (Make).
* Calculating the average battery capacity for each manufacturer in the filtered set.

### Task 2: Outlier Detection in Energy Consumption
* Identifying outliers in the `Mean - Energy consumption [kWh/100 km]` column to find EVs with unusually high or low energy consumption.

### Task 3: Battery Capacity vs. Range Relationship
* Creating a suitable plot to visualize the relationship between `Battery capacity [kWh]` and `Range (WLTP) [km]`.
* Highlighting insights derived from this visualization.

### Task 4: EV Recommendation Class
* Building a Python class that allows users to input their budget, desired range, and battery capacity.
* The class returns the top three EVs matching the user's criteria.

### Task 5: Inferential Statistics - Hypothesis Testing
* Conducting a two-sample t-test (using `ttest_ind` from `scipy.stats`) to determine if there is a significant difference in the average `Engine power [KM]` between vehicles manufactured by Tesla and Audi.
* Drawing insights, recommendations, and conclusions from the test results.

## Technologies Used

* Python
* Pandas
* NumPy
* SciPy
* Matplotlib (for visualizations)
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


