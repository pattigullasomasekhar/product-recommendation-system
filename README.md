# 🛒 Ecommerce Product Recommendation System

This project is a content-based recommendation system built using Python. It suggests similar products to users based on product titles using **TF-IDF Vectorization** and **Cosine Similarity**.

## 🔍 Features

* Uses Amazon dataset with product information.
* Recommends similar products using textual similarity.
* Interactive input to test recommendations.

## 📁 Dataset

The dataset used: `Amazon Dataset.csv`
Contains product names and metadata.

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn (TF-IDF, cosine similarity)
* Jupyter Notebook

## 📊 How it Works

1. Clean and preprocess product data.
2. Convert product titles into TF-IDF vectors.
3. Compute cosine similarity between vectors.
4. Return top similar products based on user input.

## 💡 Example Output

> **Input:** "Apple iPhone 11 (64GB)"
> **Recommendations:**
>
> * Apple iPhone 11 Pro Max
> * Apple iPhone XR
> * Apple iPhone 12 Mini

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/product-recommendation-system.git
   ```
2. Install requirements:

   ```bash
   pip install -r requirements.txt
   ```
3. Open `Product_Recommendation_System.ipynb` in Jupyter Notebook
4. Run all cells
5. Enter product name to see recommendations

## 📦 Requirements

Create a file `requirements.txt` and include:

```
pandas
numpy
scikit-learn
jupyter
```

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

## 🤝 Author

**Pattigulla Somasekhar**
🌐 [LinkedIn](https://www.linkedin.com/in/pattigulla-somasekhar-2b99142b8?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BcCsKYEoCQoGie%2BdM3zboDQ%3D%3D)
📧 [pattigullasomasekhar1972@gmail.com](mailto:pattigullasomasekhar1972@gmail.com)
