# Time Series Analysis of BXD Aging Colony Body Weight

The BXD family of mice is a recombinant inbred strain of mice which
can be reproduced by crossing a female C57BL/6J (B6 or B) and a male
DBA/ 2J (D2 or D). They are used to map Mendelian and Trait Loci.

In this explorative exercise, we apply some time series analysis to
investigate body weight across several months of collected data. We
first do some data cleaning, and from the various data points, pick
one experiment(represented as one vector) to model and attempt
forecasting.

# Using GNU/ GUIX To Manage Dependencies

In this exercise, GNU Guix was used to handle dependencies.  To run
this project locally, please run `guix shell -m manifest.scm`. The
command used to start the notebook file is: `jupyter notebook
--ip=0.0.0.0 --port=8080`
