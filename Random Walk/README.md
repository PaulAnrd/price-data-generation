# Random Walk

Random Walk price paths model follow :
$$ S(t+1) = S(t) + \epsilon $$

- $ S(t+1) $ is the price at time $ t+1 $
- $ S(t) $ is the price at time $ t $
- $ \epsilon $ is a random noise term (or a random increment).

with the probability density for the Gaussian distribution :
$$
p(x) = \frac{1}{\sqrt{2 \pi \sigma^2}} e^{-\frac{(x - \mu)^2}{2 \sigma^2}}
$$


- $ p(x) $ is the probability density function.
- $ \mu $ is the mean of the distribution.
- $ \sigma $ is the standard deviation.
- $ x $ is the random variable.

[Usefull NumPy doc](https://numpy.org/doc/stable/reference/random/generated/numpy.random.normal.html)