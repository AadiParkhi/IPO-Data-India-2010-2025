IPO Data Visualization
This project provides a series of visualizations based on a dataset of Initial Public Offerings (IPOs). The visualizations are created using Python with the pandas library for data manipulation and matplotlib for plotting.

Visualizations
This project generates the following five visualizations from the IPO dataset:

Top 10 IPOs by Issue Size: A horizontal bar chart showcasing the ten largest IPOs based on their issue size in crores. This helps in quickly identifying the most significant market entries.

Average Listing Gain Over the Years: A line chart that tracks the annual average listing gain of IPOs. This visualization provides insights into the performance trends of IPOs over time, indicating periods of higher or lower immediate returns for investors.

Total Subscription by Investor Category: A pie chart that breaks down the total subscription amounts by different investor categories: Qualified Institutional Buyers (QIBs), High Net-worth Individuals (HNIs), and Retail Individual Investors (RIIs). This highlights the contribution of each investor group to the IPO market.

IPO Issue Size vs. Listing Gain: A scatter plot that explores the relationship between the issue size of an IPO and its listing day gains. Each point represents an individual IPO, helping to visualize any potential correlation between the size of an offering and its initial market performance.

Pareto Chart of Top 20 IPO Issue Sizes: This chart combines a bar chart of the top 20 IPOs by issue size with a line graph representing the cumulative percentage of the total issue size. It illustrates the concentration of capital, often showing that a small number of large IPOs account for a significant portion of the total funds raised.

How to Run
To generate these visualizations on your own machine, please follow these steps:

Prerequisites
Make sure you have Python installed on your system. You will also need the following libraries:

pandas

matplotlib

You can install these libraries using pip:

Bash

pip install pandas matplotlib
Execution
Clone the repository:

Bash

git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
Place the dataset in the root directory:
Ensure that the Initial Public Offering.csv file is in the same directory as the Python script.

Run the script:
Execute the Python script from your terminal:

Bash

python your_script_name.py
After running the script, the five visualizations will be saved as PNG image files in the same directory.

Data Source
The data for this project is contained in the Initial Public Offering.csv file. This dataset includes information about various IPOs, such as the issue date, issue size, subscription details for different investor categories, offer price, listing price, and subsequent gains.
