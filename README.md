# NASDAQPortfolioConstructor
This Portfolio Constructor streamlines investment strategies by employing hybrid optimization for NASDAQ-100 index emulation, optimizing investment costs and accuracy. This approach enhances portfolio performance, offering investors a cost-effective solution for market trend alignment and strategic asset allocation.

### Project Overview
The project embarked on developing an Index Fund Emulator to efficiently track the NASDAQ-100 index using a reduced set of stocks. Spanning analysis over two years, it utilized 2019 data for constructing portfolios and 2020 data to evaluate performance, aiming to reconcile cost efficiency with accurate index tracking.

### Objectives
- **Strategic Stock Selection**: Develop a method to select a subset of stocks that mimics the NASDAQ-100 index closely.
- **Balance Accuracy with Efficiency**: Navigate the trade-off between tracking accuracy and operational costs, optimizing for a lean yet effective investment strategy.

### Approach and Methodology
- **Data Utilization**: Leveraged 2019 stock returns and correlation matrices for portfolio construction; 2020 data assessed the emulation accuracy.
- **Traditional Optimization**: Applied Integer and Linear Programming to select stocks and allocate weights, maximizing similarity to the index.
- **Mixed-Integer Programming (MIP)**: A novel approach integrating stock selection and weight allocation, optimizing across all stocks with constraints on non-zero weights to ensure cost-effective emulation.

### Time Period of Analysis
The meticulous analysis relied on detailed stock price data from 2019 for constructing portfolios and 2020 for performance evaluation against the NASDAQ-100 index.

### Performance Evaluation and Results
- **Tracking Performance**: Both Traditional and MIP approaches effectively tracked the NASDAQ-100 index, with nuanced differences in computational efficiency and accuracy.
- **Diminishing Returns**: Incremental analysis revealed diminishing returns on accuracy beyond a certain portfolio size, indicating an optimal range for stock inclusion.
- **Computational Insights**: Despite higher computational demands, the MIP approach showed promise in selecting and weighting stocks for emulation.

### Insights and Recommendations
- **Optimal Portfolio Construction**: Identified an optimal number of stocks that balance tracking accuracy with investment costs, suggesting a strategic portfolio size for emulation.
- **Adaptive Strategy**: Highlighted the importance of ongoing model updates to adapt to market dynamics, ensuring sustained emulation effectiveness.
- **Investment Strategy Guidance**: Advised investors on employing a balanced selection of stocks, optimizing for cost while closely tracking the NASDAQ-100 index.
