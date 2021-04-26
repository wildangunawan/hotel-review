# Hotel Review Sentiment Analysis

## Overview

In this project I'm trying to deploy a trained model with Streamlit. This model already trained with ~4.000 sentences that is balanced (1:1 ratio) between each class. Language used for this is Bahasa Indonesia but I used BERT multilingual instead since there may be some English review.

I also published an article on how to implement this in my Medium [here](https://wildangunawan.medium.com).

## Usage

It's easy to deploy this on your own. All you have to do is:
1. Clone this project
2. Inside that folder, run `pip install -r requirements.txt`
3. When done, run `streamlit run app.py`.

Streamlit will take care the rest and will automatically open a new tab in your favorite browser.

## License

This project is licensed under [MIT License](LICENSE).
