# Algorithmic Trading
Used machine learning algorithms to create an algorithmic trading system.
 
---

## Technologies

This project uses Jupyter Lab in addition to the following libraries and add ons:

* [pathlib](https://docs.python.org/3/library/pathlib.html) for the path functions to locate the csv files.

* [pandas](https://pandas.pydata.org/docs/) for working with dataframes.

* [matplotlib](https://docs.python.org/3/library/pathlib.html) for the data visualization.

* [hvplot](https://hvplot.holoviz.org/) for the data visualization.

* [numpy](https://numpy.org/doc/) for certain numericalfunctions.

* [sklearn](https://scikit-learn.org/stable/user_guide.html) for the logistical regression.
---

## Installation Guide

Please run the following commands in your terminal before running the app:
```
pip install jupyterlab

pip install python-dotenv

pip install sklearn

```
---

## Usage

The App imports stock data from the csv in the resources file, which is then processed to create a short and long window. This data is then used to create a trading algorithm of which the results are evaluated:

![Predictions](https://user-images.githubusercontent.com/96391748/161412692-db475895-7d8a-4f0a-96f8-a6959b003fd2.PNG)

The results are then compared to the actual return of the asset as cumulative returns and displayed:

![results](https://user-images.githubusercontent.com/96391748/161412753-1f427ecb-44fb-4925-8420-b62284bf1c21.PNG)

Finally, a second algorithm is created and the same process is repeated to evaluate and visualize the results:

![second_results](https://user-images.githubusercontent.com/96391748/161412785-d1a3e7dc-e26f-4abf-95e0-3e85a9a4b367.PNG)

---

## Contributors

* Nicklaus Danialy nickdanialy@gmail.com 

---

## License

Copyright (c) [2021] [Nicklaus Danialy]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE