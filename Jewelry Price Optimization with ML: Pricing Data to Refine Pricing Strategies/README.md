 Business Overview/Problem

Business Problem I
Having recently expanded operations, Gemineye Emporium has grown from a relatively small jewelry provider to a large-scale jewelry designing and trading company. Although this is good news, this transition is a very fast one, and while it has gone well all things considered, there were some edge cases the company board did not see coming. One glaring instance is the product prices. This is actually the major pain point for the company at the moment.

Business Problem II

In the days where Gemineye was a small-scale holding, the price of any jewelry piece was very easy to determine or, in rare cases of confusion, ascertain. Now that operations have expanded exponentially, Gemineye finds itself not only importing pieces, but also manufacturing them in-house. With logistics concerns thrown into the mix, this becomes a more complicated system, and all these factors have two effects:

    A. Complicate the price determination process, and
    B. Inflate prices.

 

Business Problem III

Gemineye is in need of a means by which they can:

    A. Make the most profit from their investment, and
    B. Remain competitive by keeping their prices as affordable as possible.

 

In essence, they are in need of a way to maximize price to fill their pockets while minimizing it to suit the customers’ pockets. This is a tricky kettle of fish to boil!

 

Enter you, our intrepid data scientist. You have come up with the brilliant idea to leverage artificial intelligence (AI) for this task, which you have shared with the administrative team.

Business Problem IV

To be more specific, the specific challenges of interest are:

    A. Market Dynamics: The jewelry market is influenced by trends, fashion, and changing consumer preferences, making pricing decisions complex.
     
    B. Competitive Pricing: Setting prices that are competitive with other jewelry retailers while offering unique and high-quality pieces.
     
    C. Cost Management: Balancing the cost of materials, craftsmanship, and overhead expenses with market pricing is crucial for profitability.

Rationale for the Project

    More rationale for jewelry price optimization can be seen as follows:

     
        A. Profitability: Maximizing profits by balancing prices with costs and market demand
         
        B. Customer Satisfaction: Offering competitive prices for high-quality jewelry enhances customer satisfaction.
         
        C. Adaptability: The ability to adjust prices dynamically in response to market changes and trends.

Aim of the Project

The aims of the project are:

 

    A. Develop Price Optimization Models: Create machine learning models to predict optimal prices for different jewelry pieces based on market data and costs.
     
    B. Feature Selection (and Engineering): Identify (and engineer) relevant features that contribute to load capacity prediction accuracy.
     
    C. Ensure explainable predictions: Ensure that the developed price prediction models are explainable and can give insights to the business analysts as regards. This will help the business administration trust the model predictions even more.
     

Data Description

Data Description I

You have carte blanche to request whatever data you require. Based on your wealth of experience, you know you require:

    ✓ Jewelry Data: Detailed information about each jewelry piece, including gemstone type, metal type, weight, and craftsmanship details.
    ✓ Market Data: Historical market data, including jewelry market trends, competitor prices, and consumer preferences, and time of sales.

 

Data Description II

The features contained in the dataset are:

    ✓ Order datetime (The time at which the order was placed)
    ✓ Order ID (Identifiers for the different orders placed)
    ✓ Purchased product ID (Identifiers for the different product ordered for)
    ✓ Quantity of SKU in the order (Quantity of jewelry pieces ordered for)
    ✓ Category ID (Identifier for the jewelry category)
    ✓ Category alias (Name of jewelry category e.g. earring)
    ✓ Brand ID (Identifier for jeweler brand)
    ✓ Price in USD (Jewelry price in US Dollars)
    ✓ User ID (Identifier for user/customer)
    ✓ Product gender (for male/female) (Target gender for jewelry piece)
    ✓ Main Color (Overall color of jewelry piece)
    ✓ Main metal (Main metal used for mounting)

✓ Main gem (Main gem mounted on jewelry piece)
Tech Stack

The programming language of use, as in most of ML, is Python.


The Python libraries of interest for this project are:

 

    A. NumPy: Numerical computation 
    B. Pandas: Data munging and manipulation
    C. Matplotlib and Seaborn: Data Visualization
    D. Sci-kit Learn: Machine Learning

E. RAPIDS (CuML): CUDA-accelerated Machine Learning
Project Scope

A. Exploratory Data Analysis

The data is thoroughly explored and analysed to gain insights and understand its characteristics. This involves statistical analysis, data visualization, and other exploratory techniques to identify patterns, correlations, anomalies, and potential issues in the data.

 

B. Feature Selection (and Engineering)

Not all features provided in data may be of relevance to the target. Feature selection is the process by which we can select the most appropriate of these according to a specified set of criteria. The data features might also be composable to give more informative features.

 

C. Model Development

Various modelling techniques are applied to the prepared data in this stage to build predictive or descriptive models. This can include machine learning algorithms, statistical models, or other analytical approaches. The models are trained, validated, and fine-tuned to optimize their performance.

 

D. Model Evaluation, Selection and Explanation

Once the models are developed, they are evaluated using appropriate evaluation metrics and validation techniques. This involves assessing their performance, generalizability, and robustness. The best-performing model(s) are selected for further deployment or refinement, and attempts to explain why they work and what they learn are made.

 
