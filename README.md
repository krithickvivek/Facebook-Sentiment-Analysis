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

## 📊 Sample Dataset

| user         | comment                          | date       |
| ------------ | -------------------------------- | ---------- |
| Arun Kumar   | This product is amazing!         | 2026-01-01 |
| Priya Sharma | It is okay, nothing special      | 2026-01-02 |
| Rahul Verma  | Worst experience ever            | 2026-01-03 |
| Sneha Iyer   | Average performance              | 2026-01-04 |
| Vikram Singh | I love it                        | 2026-01-05 |
| Anjali Mehta | Not bad, not great               | 2026-01-06 |
| Karthik Raj  | Could be better                  | 2026-01-07 |
| Neha Gupta   | Absolutely fantastic!            | 2026-01-08 |
| Rohan Das    | It works fine                    | 2026-01-09 |
| Divya Nair   | Service was neither good nor bad | 2026-01-10 |


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
