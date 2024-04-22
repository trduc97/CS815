This repo uses evolutionary algorithms on S&P 100 stocks between the period of 2016 to the end of 2019 to find a portfolio that maximizes the Sharpe-ratio, measuring the combination of return/risk of 

To achieve this, we need to perform 2 tasks:

(1) Determine the optimal 10-stock combination from the list of 100 stocks

(2) Determine the optimal weight combination of the 10 stocks

Overall we achieved multiple approaches that outperform the S&P100 on both the training and testing dataset 

During the training period, the optimal portfolio with optimal weight performs the best as intended
![training_results](https://github.com/trduc97/CS815/assets/52210863/5c6f689f-f323-49bb-9639-0dfd976177d5)

![training_performance](https://github.com/trduc97/CS815/assets/52210863/111dbbc7-ddb3-43a1-b0a1-02c7c0231abf)


But checking on the test period, while all the portfolios outperform the index, and optimal weights do perform better than equal weights, the optimal portfolio does not outperform a random portfolio
![testing_results](https://github.com/trduc97/CS815/assets/52210863/432022ab-5f5e-4de2-8c2b-0da52c1a9906)

![testing_performance](https://github.com/trduc97/CS815/assets/52210863/7e239087-2d48-4a45-83f7-d0c4114a95b9)


Evolutionary algorithms is a good solution for portfolio optimization for several reasons:

1. **Flexibility**: They adapt to various investment goals and constraints.
2. **Non-linearity Handling**: Efficiently capture complex asset interactions.
3. **Robustness**: Avoid getting stuck in suboptimal solutions.
4. **Diversity**: Offer a range of portfolio options for decision-makers.
5. **Constraint Adaptation**: Easily incorporate practical investment guidelines.
6. **Scalability**: Handle large portfolios efficiently.
7. **Complex Search Exploration**: Discover novel portfolio combinations.
8. **Dynamic Adaptation**: Adjust portfolios to changing market conditions.

In short, evolutionary algorithms provide a versatile, robust, and efficient approach to portfolio optimization, capable of navigating the complexities of financial markets effectively.
