# Analysis of Mobile Price Data

## Description
This project analyzes a dataset containing various details about mobile phone hardware, specifications, and prices. The main objective is to build and evaluate classification models that predict **mobile phone price ranges** based on different features.

## Dataset
The dataset includes multiple attributes related to mobile phone specifications. Below is an explanation of each column:

| Column       | Description |
|-------------|-------------|
| battery_power | Total energy a battery can store in one time (mAh) |
| blue         | Bluetooth availability (1: Yes, 0: No) |
| clock_speed  | Speed at which the microprocessor executes instructions |
| dual_sim     | Dual SIM support (1: Yes, 0: No) |
| fc           | Front camera megapixels |
| four_g       | 4G connectivity (1: Yes, 0: No) |
| int_memory   | Internal memory (GB) |
| m_dep        | Mobile depth (cm) |
| mobile_wt    | Mobile phone weight (g) |
| n_cores      | Number of processor cores |
| pc           | Primary camera megapixels |
| px_height    | Pixel resolution height |
| px_width     | Pixel resolution width |
| ram          | Random access memory (MB) |
| sc_h         | Screen height (cm) |
| sc_w         | Screen width (cm) |
| talk_time    | Maximum talk time (minutes) |
| three_g      | 3G connectivity (1: Yes, 0: No) |
| touch_screen | Touchscreen availability (1: Yes, 0: No) |
| wifi         | Wi-Fi connectivity (1: Yes, 0: No) |
| price_range  | Target variable (0: Low, 1: Medium, 2: High, 3: Very High) |

## Objectives
- Preprocess the dataset and perform exploratory data analysis (EDA).
- Train classification models to predict the mobile phone price range.
- Evaluate model performance using various metrics.

## Technologies Used
- Python
- Pandas & NumPy (Data handling)
- Matplotlib & Seaborn (Visualization)
- Scikit-learn (Machine Learning)

## How to Use
1. Clone the repository.
2. Install required dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook to execute the analysis and train models.

## Results & Findings
The project evaluates different classification models and compares their accuracy and performance.

## Author
Quynh Nhi (Callanth) Vu

