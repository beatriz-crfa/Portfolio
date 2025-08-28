# Portfolio
This is a fun portfolio to study/review statistics on the side.

## Lists of projects:
### Pi Monte Carlo Estimation:
This project uses the Monte Carlo method to estimate pi and visualizes how the number of iterations affects the estimation error. This method uses the ratio between the area of a square of side 2*r (Area_s = 4*r^2) and of a circle inscribed in that square (Area_c = pi*r^2). 

The law of large numbers for proportions states that if you repeat an experiment independently (with no repetition) a large number of times, the observed proportion of times a specific event occurs will get closer and closer to the true probability of that event, i.e. by sampling a large number of points inside the square, the proportion of those points that are also inside the circle will tend to Area_c/Area_s=pi/4.

Hence, pi can be estimated by 4*#samples_inside_circle/#total_samples.

The samples were obtained using a uniforme distribution as each point inside the square as equal probability of being picked.

### IMDb: