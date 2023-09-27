# Virtual-CP-Program
This is a project I was in charge of during my internship. Its primary focus was on the visualization process of chips, identifying those that did not meet the set standards. My personal reflections and thoughts on this can be found on Trello https://trello.com/b/zZcCujs8/work-planner 
Due to the confidentiality agreement I signed with the company, I can only disclose some of the initial code

Introduction

This script is a data processing and analysis tool, primarily designed for handling specific formats of CSV files. The tool can read data from the file, apply particular formulas, flip coordinates, identify missing data points, and visualize the processed data.

Main Features of the First Segment of the Code:
Loading Data (load_data function)

Load data from the specified CSV file.
Handle file errors and log them.
Validating and Removing Duplicates (validate_and_remove_duplicates function)

Verify and remove duplicate rows in the dataframe.
Applying Formula (apply_formula function)

Apply a specific formula to the 'Y' column in the dataframe.
Flipping X Coordinates (flip_x_coordinates function)

Flip the X coordinates in the dataframe based on the center X coordinate.
Adjusting Coordinates (adjust_coordinates function)

Apply an offset to the coordinates in the dataframe.
Identifying Gaps (find_all_holes function)

Locate missing coordinate points in the grid.
Data Visualization (visualize_data function)

Plot a scatter diagram based on the PF column.
Generating TXT from Dataframe (generate_txt_from_df function)

Export the processed data into a TXT format.
Finding the First Gap and Its Surroundings (find_first_hole_and_surroundings function)

Identify the first gap and its surrounding coordinates in the grid.
Calculating the Totals for Failed, Passed, and Tested Cases

Count the total number of failures, passes, and tests.
All subsequent codes are appropriately commented.

Notes:
The default filenames and paths are hard-coded, so ensure you adjust them to point to the correct location before using.
If you need to apply different formulas or adjust parameters, modify the relevant sections in the script directly.
To prevent data loss, the script by default creates a new TXT file, instead of overwriting the original file.
For design logic, please refer to: https://trello.com/b/zZcCujs8/virtual-cp-work-planner-week12
Lastly, enjoy using the tool!
