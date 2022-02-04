# ADCT_JoystickInput

INPUT:

data: 4 x Timeseries Location data. data_t: Thrust Location data; data_p: Pitch Location data; data_y: Yaw Location data.

window_size: I think 51 - 201 is a good number for this particular time seriesThe length of the filter window (i.e., the number of coefficients). window_length must be a positive odd integer. If mode is ‘interp’, window_length must be less than or equal to the size of x.

factor_noisefloor: The number of standard deviation you set for calculating the noise floor. I normally set it to 1

OUTPUT:

input_t: Thrust Input

input_y: Yaw Input

input_p: Pitch Input
