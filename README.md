# Vehicle-Routing-Problem-with-Time-Window
Vehicle Routing Problem with Time Window(VRPTW) using Discrete Bat Algorithm(DBA)

Bat Algorithm(BA)

Bat algorithm is based on the echolocation behavior of bats. It is a metaheuristic method. All bats use echolocation to sense distance, and they also know the difference between food/prey and background barriers in some magical way. In simulations, we use virtual bats naturally.We have to define the rules how their positions   and velocities   in a d-dimensional search space are updated. At time step   the positions and the velocities are   and  , respectively. The new solutions   and velocities   at time step   are given by
                 (11)
                    (12)
                          (13)
where   is a random vector drawn from a uniform distribution. Here   is the current global best location (solution) which is located after comparing all the solutions among all the bats.   is the current frequency of bats.   expresses the maximum frequency.   refers to the minimum frequency.
Furthermore, the loudness   and the rate   of pulse emission have to be updated accordingly as the iterations proceed. At time step   the loudness and the initial rate of pulse emission are   and  , respectively. Now we have
                            (14)
                    (15)
where   and   are constants. The range of   is  .   satisfies  .
 

Discrete Bat Algorithm(DBA)
