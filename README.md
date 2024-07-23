# Harvest-Heal 🌿

Harvest-Heal is a user-friendly website that leverages Machine Learning (ML) and Deep Learning (DL) to provide crop recommendations, fertilizer suggestions, and plant disease predictions, empowering farmers to make informed decisions and enhance agricultural productivity.

## Motivation 💪
Agriculture is a cornerstone of economic growth, especially in countries like India, where a large portion of the population depends on it for their livelihood. By utilizing modern technologies such as ML and DL, we can revolutionize agriculture, providing farmers with tools to optimize yields and mitigate risks. Harvest-Heal aims to address these needs by offering tailored solutions for crop recommendations, fertilizer suggestions, and plant disease detection.

## Data Sources 📊
- **Crop recommendation dataset**: [Kaggle](https://www.kaggle.com/atharvaingle/crop-recommendation-dataset).
- **Fertilizer suggestion dataset**: [GitHub](https://github.com/Gladiator07/Harvestify/blob/master/Data-processed/fertilizer.csv).
- **Disease detection dataset**: [Kaggle](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset).

## Built with 🛠️
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="30" src="https://github.com/tomchen/stack-icons/raw/master/logos/bootstrap.svg"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png"></code>

<code><img height="30" src="https://raw.githubusercontent.com/numpy/numpy/7e7f4adab814b223f7f917369a72757cd28b10cb/branding/icons/numpylogo.svg"></code>
<code><img height="30" src="https://raw.githubusercontent.com/pandas-dev/pandas/761bceb77d44aa63b71dda43ca46e8fd4b9d7422/web/pandas/static/img/pandas.svg"></code>
<code><img height="30" src="https://matplotlib.org/_static/logo2.svg"></code>
<code><img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1280px-Scikit_learn_logo_small.svg.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/pytorch/pytorch/39fa0b5d0a3b966a50dcd90b26e6c36942705d6d/docs/source/_static/img/pytorch-logo-dark.svg"></code>

## How to Use 💻

### Crop Recommendation System
1. Input soil nutrient values, state, and city. Ensure the N-P-K (Nitrogen-Phosphorus-Potassium) values represent their respective ratios. Refer to [this guide](https://www.gardeningknowhow.com/garden-how-to/soil-fertilizers/fertilizer-numbers-npk.htm) for more information.
2. Use well-known city names, as remote areas might not be available in the [Weather API](https://openweathermap.org/) for humidity and temperature data.

### Fertilizer Suggestion System
1. Provide soil nutrient contents and the crop you intend to grow.
2. The system will identify nutrient deficiencies or excesses and recommend suitable fertilizers.

### Disease Detection System
1. Upload an image of a plant leaf.
2. The system will identify the crop type and assess its health. If diseased, it will diagnose the ailment and offer prevention or cure suggestions.
3. Supported crops include Apple, Blueberry, Cherry, Corn, Grape, Pepper, Orange, Peach, Potato, Soybean, Strawberry, Tomato, Squash, and Raspberry.

## How to Run Locally 🛠️
1. Ensure you have [Git](https://git-scm.com/download) and [Anaconda](https://www.anaconda.com/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed.
2. Clone the project repository using `git clone https://github.com/Gladiator07/Harvestify.git` or download and unzip the code.
3. Navigate to the cloned/downloaded directory.
4. Switch to the `deploy` branch:
   ```
   git checkout deploy
   ```
5. Create and activate a virtual environment:
   ```
   conda create -n harvestify python=3.6.12
   conda activate harvestify
   ```
6. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
7. Run the project:
   ```
   python app.py
   ```
8. Access the project via the provided localhost URL in your web browser.

## Demo

### Crop Recommendation System
#### Before Prediction
![Before Prediction](https://github.com/user-attachments/assets/fad9a7bb-9bce-4aac-84b5-68695bbc975d)

#### After Prediction
![After Prediction](https://github.com/user-attachments/assets/5f5079ae-d694-486b-96fc-aa440ef81793)

### Fertilizer Suggestion System
![Fertilizer Suggestion](https://github.com/user-attachments/assets/c2388b8b-075a-4e81-9b98-bfe98de47ab3)

### Disease Detection System
#### Before Prediction
![Before Prediction](https://github.com/user-attachments/assets/7e7710ea-9575-4bad-8d38-d2a4cb6a5e70)

#### After Prediction
![After Prediction](https://github.com/user-attachments/assets/4311dd2f-d0a6-4d3a-b373-678ba53f46b9)

## Usage ⚙️
You can further develop and enhance this project, incorporating your contributions. Please attribute the original source and include a link to this repository in your reports or documentation.

## Conclusion 🌱
Harvest-Heal aims to bridge the gap between traditional farming practices and modern technological advancements. By leveraging the power of ML and DL, it offers farmers invaluable insights into crop management, fertilizer usage, and disease prevention. As we continue to refine and expand Harvest-Heal, we aspire to contribute to the sustainable growth of agriculture, ensuring food security and prosperity for generations to come.
