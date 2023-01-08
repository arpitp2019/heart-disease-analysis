This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.

Columns are - 
age

sex

cp: chest pain type
-- Value 1: typical angina
-- Value 2: atypical angina
-- Value 3: non-anginal pain
-- Value 4: asymptomatic

trestbps: resting blood pressure (in mm Hg on admission to the hospital)

chol: serum cholestoral in mg/dl

fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

restecg: resting electrocardiographic results
-- Value 0: normal
-- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation ordepression    of > 0.05 mV)
-- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

thalach: maximum heart rate achieved

exang: exercise induced angina (1 = yes; 0 = no)

oldpeak = ST depression induced by exercise relative to rest

slope: the slope of the peak exercise ST segment
-- Value 1: upsloping
-- Value 2: flat
-- Value 3: downsloping

ca: number of major vessels (0-3) colored by flourosopy

thal: 1= normal; 2 = fixed defect; 3 = reversable defect

The names and social security numbers of the patients were recently removed from the database, replaced with dummy values.



### matplotlib subplots
matplotlib is a python library used for data visualization. The subplot function is a way to create multiple subplots within a single figure in matplotlib.

According to 1, the subplot function has the following parameters:

*args: either a 3-digit integer or a 3-tuple of integers. If a 3-digit integer is provided, it specifies the number of rows, number of columns, and index of the subplot. The index of the subplot is 1-based and starts at the upper left corner of the grid, and increases to the right. If a 3-tuple is provided, it specifies the (first, last) indices of the subplots to be created in the grid.


int, int, index: these are the three integers that specify the number of rows, number of columns, and index of the subplot if *args is a 3-digit integer.


SubplotSpec: a subclass of tuple that specifies the location of the subplot in a grid.


2 describes the subplots function, which creates a figure and a grid of subplots with a single call. It has the following parameters:

nrows: the number of rows in the subplot grid. Default is 1.

ncols: the number of columns in the subplot grid. Default is 1.

sharex: if True, the X axis limits are shared among all subplots. Default is False.

sharey: if True, the Y axis limits are shared among all subplots. Default is False.

squeeze: if True, extra dimensions are squeezed out from the subplot grid. Default is True.

width_ratios: a list of relative widths for each column of the subplot grid.

height_ratios: a list of relative heights for each row of the subplot grid.

subplot_kw: a dictionary of keyword arguments to be passed to the add_subplot call used to create each subplot.

gridspec_kw: a dictionary of keyword arguments to be passed to the GridSpec constructor used to create the subplot grid.

**fig_kw: keyword arguments to be passed to the figure call.

3 describes the subplots_adjust function, which adjusts the parameters of the subplot layout. It has the following parameters:

left: the position of the left edge of the subplots, as a fraction of the figure width.

right: the position of the right edge of the subplots, as a fraction of the figure width.

bottom: the position of the bottom edge of the subplots, as a fraction of the figure 
height.
top: the position of the top edge of the subplots, as a fraction of the figure height.

wspace: the amount of width reserved for blank space between subplots, as a


Share
