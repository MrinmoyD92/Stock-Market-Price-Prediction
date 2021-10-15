# Stock-Market-Price-Prediction
Stock Market Price prediction project using LSTM and Decision Tree Regression
Members:
1) Mihir Vatsa
2) Mrinmoy Dutta
3) Gaurav Bhogale
4) Shubham Salokhe
5) Chetan Bansal

PROBLEM DEFINITION: 
The Stock market check is an exceptionally fascinating errand which joins high substances of how the budgetary exchange limits, and what unconventionalities can be prompted in a market in light of different conditions. While a few venders may battle that the market itself is functional, and that if there is new check or any assortment from the standard in a market it charms it by auditing itself, thusly making no space for conjectures, while several vendors may battle that on the off chance that the information is orchestrated well, by then machine can make a sort out of procedure that is persuading can affect high continue exchanging or HFT, which is just conceivable through Algorithmic Trading Systems or Automated Systems of Trade. 
Money related authorities think about the expression, Buy low, Move high yet this does not give enough setting to settle on proper endeavor decisions. Before an investigator places assets into any stock, He should realize how money markets continues .Setting assets into a wonderful stock regardless at a horrible time can have awful results, while vitality for a common stock at the fortunate time can hold up under focal points. Cash related monetary pros of today are going toward this issue of trading as they don't for the most part understand concerning which stocks to buy or which stocks to offer with the authentic objective to get impeccable focal points. Envisioning whole game plan estimation of the stock is commonly clear than foreseeing on day-to-day premise as the stocks change rapidly reliably subject to world events. 
The answer for this issue requests the utilization of instruments and advances identified with the field of information mining, design acknowledgment, machine learning and information forecast. The application will foresee the stock costs for the following exchanging day. The necessities and the usefulness of this application corresponds it to the class. 

PROJECT OVERVIEW:
Artificial intelligence (AI) to play an integral role in our day to day life applications whether it be home environment applications like Alexa or financial applications like trading, it is a development towards a new era of technology. This project comprises of an application of AI on financial data, known as algorithmic trading. 
Automated trading systems involves the use of complex AI systems to make extremely fast trading decisions like buy, hold, or sell. It involves high frequency trading or HFT to make millions of trade in a day. 
Machine learning is a subset of AI and generally provides solutions which learn from experience without being explicitly programmed. 
In simple words, just the machine learning models are selected and fed with data the model then automatically adjusts its parameters and improves its outcome. 

TECHNOLOGIES USED:
NumPy
NumPy is the fundamental package for scientific computing in Python. It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.

Pandas
Pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series.

Matplotlib
It is a comprehensive library for creating static, animated, and interactive visualizations in Python.

Keras
Keras is an API designed for human beings, not machines. Keras follows best practices for reducing cognitive load: it offers consistent & simple APIs, it minimizes the number of user actions required for common use cases, and it provides clear & actionable error messages. It also has extensive documentation and developer guides.

Tensorflow
TensorFlow is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML powered applications.

DEEP LEARNING USING LSTM
Long Short Term Memory cells are like mini neural networks designed to allow for memory in a larger neural network. This is achieved through the use of a recurrent node inside the LSTM cell. This node has an edge looping back on itself with a weight of one, meaning at every feedforward iteration the cell can hold onto information from the previous step, as well as all previous steps. Since the looping connection’s weight is one, old memories wont fade over time like they would in traditional RNNs.
LTSMs and recurrent neural networks are as a result good at working with time series data thanks to their ability to remember the past. By storing some of the old state in these recurrent nodes, RNNs and LSTMs can reason about current information as well as information the network had seen one, ten or a thousand steps ago. Even better, I don’t have to write my own implementation of an LSTM cell; they are a default layer in Tensorflow’s Keras.
We are going to use LSTMs and Keras to predict the stock market, and perhaps even make some money.
