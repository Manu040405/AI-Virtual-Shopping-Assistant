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
📊 Dataset
Custom dataset: person.csv

Currently supports 100 items.

To expand the dataset:

Open getDataset.py

Add more items to the item list.

Delete person.csv and dataset.csv

Run:

bash
Copy
Edit
python3 getDataset.py
🚀 Usage
Clone the repository:

bash
Copy
Edit
git clone https://github.com/riti1302/AI-Based-Shopping-Assistant
cd AI-Based-Shopping-Assistant
Run the main script:

bash
Copy
Edit
python3 main.py
To expand the item database, add more data files to the data/ directory.

🎯 Output
<p align="center"> <img src="output.gif" alt="Demo Output" /> </p>
