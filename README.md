# bag_to_csv for python3
In the process of processing rosbag data, I wanted to convert this data to csv, 
however, many of the batch conversions on the web are based on python2, so I made some small adjustments to the original code for Python3 to use.

## Attention
python3 may not find the rosbag module error, you can use the command `pip install bagpy` to solve this problem.

## Usage
* When you just want to extract a single package, enter the following command in the terminal`python3 bag2csv.py your-bagName`
* When you want to extract all packages under a folder, run the following command from a terminal in that folder directory`python3 bag2csv.py`.
Please note the path of the bag2csv.py file, please use the correct absolute or relative path in the command, otherwise it will report an error
