# 🛍️ AI-Based Shopping Assistant  
Its main goal is to create an **AI-powered recommendation system** for online shopping using **unsupervised machine learning** (clustering).

## 🧠 Project Overview
- Uses **clustering** to group items based on a user's purchase history.
- When a user searches for a product, the model:
  - Identifies the most relevant cluster.
  - Recommends similar items from that cluster under the **"Things You May Like"** section.
- Additionally, it also displays results for variations of the searched item (not part of the core recommendation logic, but added for better UX).

---

## ⚙️ Requirements
- **Python 3.6**
- Libraries:
  - [NumPy](http://www.numpy.org/)
  - [Pandas](https://pandas.pydata.org/)
  - [OpenCV](https://pypi.org/project/opencv-python/)
  - [scikit-learn](https://scikit-learn.org/stable/)
  - [matplotlib](https://matplotlib.org/)

Install dependencies using pip:
```bash
pip install numpy pandas opencv-python scikit-learn matplotlib
```

## 📊 Dataset
**Custom dataset:** `person.csv`  
Currently supports **100 items**.

To expand the dataset:
1. Open `getDataset.py`
2. Add more items to the `item` list.
3. Delete `person.csv` and `dataset.csv`
4. Run:
```bash
python3 getDataset.py
```

## 🔑 API Configuration
This application uses the Anthropic API for its intelligent shopping assistant chat feature.

1. Sign up for an API key at [Anthropic's website](https://www.anthropic.com/).
2. Create a file named `.env` in the project root directory.
3. Add your API key to the file:
```
ANTHROPIC_API_KEY=your_api_key_here
```
4. The application will automatically load this key when running the chat interface.

## 🚀 Getting Started
Clone the repository:
```bash
git clone https://github.com/Manu040405/AI-Virtual-Shopping-Assistant
cd AI-Based-Shopping-Assistant
```

Run the main script:
```bash
python3 main.py
```

To expand the item database, add more data files to the `data/` directory.

## 📸 Output
<p align="center">
  <img src="https://github.com/Manu040405/AI-Virtual-Shopping-Assistant/blob/main/ai.png" alt="Output" />
  <img src="https://github.com/Manu040405/AI-Virtual-Shopping-Assistant/blob/main/next.png" alt="Output" />
</p>

## 💬 Chat Interface
The application features an AI-powered chat interface where users can:
- Ask for product recommendations
- Get detailed product information
- Compare different products
- Receive personalized suggestions based on their browsing history

The chat interface is powered by Anthropic's API, providing natural and helpful responses to enhance the shopping experience.
