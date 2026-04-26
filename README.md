# Facebook Sentiment Analysis (Neutral Feedback)

## 📌 Objective

To perform sentiment analysis and extract only neutral feedback from social media-like data.

## 📊 Dataset

No external dataset was used.
A sample dataset was created directly inside the code using a Python dictionary.

It contains:

* User names
* Comments
* Dates

## 🛠️ Tools Used

* Python
* Pandas
* TextBlob
* Google Colab

## ⚙️ Method

1. Created dataset inside the notebook
2. Applied sentiment analysis using TextBlob
3. Used polarity threshold (-0.1 to 0.1) for neutral classification
4. Filtered neutral comments

## 📁 Files

* sentiment_analysis.ipynb

## 📈 Output

Neutral comments such as:

* "It is okay, nothing special"
* "Average performance"
* "It works fine"

## ✅ Conclusion

The model successfully identifies neutral feedback using a defined polarity range.

## 🚀 Future Work

* Use VADER for better accuracy
* Use real-world datasets
