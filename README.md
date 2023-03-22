# Program Design
## Structure Chart
![Chart](https://github.com/lukehami55/CSC-250---Programming-Assingment-5/blob/main/Structure%20Chart.png?raw=true)

## Data Storage in Main
``` cpp
Shirt shirts[5] = {0};
int order_qty[5] = {0};
int choice;
```
## Function Design
``` cpp

// function read shirts from shirts.txt file
void read_shirts(Shirt shirts[]);

// function print menu
void print_menu(Shirt shirts[]);

// function to print bill
void print_bill(Shirt shirts[], int order_qty[]);

// function to reset quantities
void reset_quantities(Shirt shirts[]);
```
## Time Estimates
|  | Estimated Time    | Actual Time    |
| :---:   | :---: | :---: |
| read_shirts |  20  |  15  |
| print_menu |  15  |  25  |
| print_bill |  20  |  10  |
| reset_quantities |  5  |  5  |
| Total Time | 60   | 55   |
