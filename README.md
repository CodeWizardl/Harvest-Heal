# Harvest-Heal 🌿
#### Harvest-Heal is a user-friendly website employing Machine Learning (ML) and Deep Learning (DL) techniques to offer crop recommendations, fertilizer suggestions, and plant disease predictions, empowering farmers to make informed decisions for enhanced agricultural productivity.

## MOTIVATION 💪
- Agriculture plays a pivotal role in the economic growth of nations, particularly in countries like India where a significant portion of the population relies on it for sustenance.
- Leveraging modern technologies such as ML and DL can revolutionize agriculture by providing farmers with efficient tools to optimize yields and mitigate risks.
- Harvest-Heal aims to address these needs by offering tailored solutions in the form of crop recommendations, fertilizer suggestions, and disease detection for plants.

## DATA SOURCES 📊
- Crop recommendation dataset: Custom-built dataset sourced from [Kaggle](https://www.kaggle.com/atharvaingle/crop-recommendation-dataset).
- Fertilizer suggestion dataset: Custom-built dataset accessible [here](https://github.com/Gladiator07/Harvestify/blob/master/Data-processed/fertilizer.csv).
- Disease detection dataset: Acquired from [Kaggle](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset).

# Built with 🛠️
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

## How to use 💻
### Crop Recommendation System
- Input the soil's nutrient values, state, and city. Ensure the N-P-K (Nitrogen-Phosphorous-Potassium) values represent their respective ratios. [This website](https://www.gardeningknowhow.com/garden-how-to/soil-fertilizers/fertilizer-numbers-npk.htm) provides further guidance.
- Note: Use commonly known city names as remote areas might not be available in the [Weather API](https://openweathermap.org/) for fetching humidity and temperature data.

### Fertilizer Suggestion System
- Provide soil nutrient contents and the crop you intend to grow. The system will identify nutrient deficiencies or excesses and recommend suitable fertilizers accordingly.

### Disease Detection System
- Upload an image of a plant leaf. The system will determine the crop type and assess its health. If diseased, it will identify the ailment and offer suggestions for prevention or cure.
- Supported crops:
  - Apple, Blueberry, Cherry, Corn, Grape, Pepper, Orange, Peach, Potato, Soybean, Strawberry, Tomato, Squash, Raspberry.

## How to run locally 🛠️
1. Ensure you have [git](https://git-scm.com/download) and [Anaconda](https://www.anaconda.com/) or [miniconda](https://docs.conda.io/en/latest/miniconda.html) installed.
2. Clone the project repository using `git clone https://github.com/Gladiator07/Harvestify.git` or download and unzip the code.
3. Navigate to the cloned/downloaded directory.
4. For the updated deployment code, switch to the `deploy` branch:
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

## DEMO

- ### Crop Recommendation System

![demo](https://media.giphy.com/media/90JbjdAa5nDq3TJh5u/giphy.gif)

- ### Fertilizer Suggestion System

![demo](https://media.giphy.com/media/FLftUXMFo8N2bBjAXq/giphy.gif)


- ### Disease Detection System
![demo](https://media.giphy.com/media/NnMwEp2tGZdfnJbyjr/giphy.gif)

## Usage ⚙️
You can further develop and enhance this project, incorporating your contributions. Kindly attribute the original source and include a link to this repository in your reports/documentation.

## Conclusion 🌱
Harvest-Heal endeavors to bridge the gap between traditional farming practices and modern technological advancements. By leveraging the power of ML and DL, it offers farmers invaluable insights into crop management, fertilizer usage, and disease prevention. As we continue to refine and expand Harvest-Heal, we aspire to contribute to the sustainable growth of agriculture, ensuring food security and prosperity for generations to come.
