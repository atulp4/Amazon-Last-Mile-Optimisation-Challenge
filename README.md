# Amazon-Last-Mile-Optimisation-Challenge
Amazon Last Mile Optimisation Challenge

## THE PROBLEM

Despite tremendous advances in route optimization over the last decades, there remains an important gap between theoretical route planning and real-life route execution: in real-life operations, the quality of a route is not exclusively defined by its theoretical length, duration, or cost. Experienced delivery drivers have tacit knowledge about the complex operational environment in which they serve customers on a daily basis. To allow for safer, more efficient, and sustainable last-mile delivery, it is critical to leveraging this tacit information for improved route planning.

## THE OBJECTIVE

The primary goal of the Last Mile Routing Research Challenge is to encourage participants to develop innovative approaches leveraging artificial intelligence, machine learning, deep learning, computer vision, and other non-conventional methods to produce solutions to the route sequencing problem that outperform traditional, optimization-driven operations research methods in terms of solution quality and computational cost.

## Downloading the Data

The AWS command line interface (CLI) (Amazon Web Services 2022) is the recommended tool to access the research challenge data set. After installing the AWS CLI, the following command can be executed to download the data to a local directory specified by the user: aws s3 sync–no-sign-request s3://amazon-last-mile-challenges/almrrc2021/{local directory}

## Important links for Dataset summary and variable description

https://registry.opendata.aws/amazon-last-mile-challenges/
https://github.com/MIT-CAVE/rc-cli/blob/main/templates/data_structures.md
https://github.com/MIT-CAVE/rc-cli
https://github.com/aws-samples/amazon-sagemaker-amazon-routing-challenge-sol
https://pubsonline.informs.org/doi/10.1287/trsc.2022.1173

## Instructions for Viewing EDA Outputs

Download Dataset using instructions given.  

Clone the repository.

Convert json to dataframe format using the code given in Amazon-Optimisation.ipynb (Change path to where data is located on your machine)

Open the EDA.ipynb file in Jupyter Notebook.

Execute all cells to reproduce the analysis and visualizations.

