# DSCI-Phishing-Email-Detection

1. How to run:

Our project is coded in Jupyter Notebook. It is already configured to run fully and build the two models (puncuation and vocabulary NLP). Simply select all of the cells and run it to generate a model.
To use the model, copy the one-off sample code at the bottom of each notebook. You can then run the oneOff test and see its return.

2. Challenges:
    - Data:
      - No pictures or links were included, making the dataset limited and unrealistic
      - Dirty data, sometimes crashing Excel
      - Potentially needing to expand beyond emails, such as from text messages and phone call logs
    - Project Development:
      - Punctuation is not understood as vocabulary
      - Our model doesn’t work really well with tests outside the dataset as phishing is more and more complex
