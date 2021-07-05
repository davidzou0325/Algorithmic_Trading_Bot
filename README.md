# Algorithmic_Trading_Bot:

Step 1: Tune the training algorithm by adjusting the size of the training dataset
    By increaseing the training period size, the strategy return perfoms worse than the actual returns during year late 2018 to early 2020. But over performs actual returns after early 2020.
    
Step 2: Tune the trading algorithm by adjusting the SMA input features
    By increasing both SMA window (short and long), overall, Strategy Returns performs much worse than the Actual Returns. 
    
Step 3: Choose the set of parameters that best improved the trading algorithm returns.
    I will choose the original SMA window and training size since both strategy has their shortages compare to original strategy.
    
    
Conclusion of Comparison Between SVM Model and LogisticRegression Model:
    After comparison between SVM and LogisticRegression model, SVM model's strategy return seems pretty stable. On the other hand, LR model's strategy return in some time period, over performed to SVM model. But in 2021, it suddenly dropped and less than actual return. 