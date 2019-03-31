IOT towards machine learning

to process and refine data at scale in real world applications of data science we are running from this stack
from our standard issued CFN machines (last ultrabooks issued 1st quarter 2016) running duel boot Debian OS/Windows
From the Linux side we use
VM
    • Keras Py
    • Apache Spark
    • Python
    • A virtualenv for Python with a scientific Python stack (scipy, numpy, matplotplib, pandas, statmodels, scikit-learn, gensim, xgboost, IPython + Jupyter notebook
    • R with a few packages installed (rmarkdown, magrittr,data.table, plus their dependencies). Plus SparkR & sparklyr for interaction with Spark.
    • Spark notebook Kernels for Python 3.6, Scala (SPylon) and R (IRKernel), in addition to the default "plain" (i.e. non-Spark capable) Python 3 kernel.
