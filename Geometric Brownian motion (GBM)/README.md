# Geometric Brownian Motion (GBM) Simulation 


$$
dS(t) = \mu S(t) dt + \sigma S(t) dW(t)
$$

where:

- $dS(t) $ is the asset price
- $ \mu$ is the expected rate of return (drift)
- $ \sigma $ is the volatility
- $ dt $ is a time increment.
- $ dW(t)$ is the increment of a Wiener process (Brownian motion) over the time interval $dt $.

### Solution of the GBM

By integrating the above stochastic differential equation, we obtain:

$$
S(t) = S(0) \exp\left( \left(\mu - \frac{1}{2}\sigma^2\right)t + \sigma W(t) \right)
$$

where:

- $ S(0) $ is the initial price of the asset at $t = 0 $.
- $ W(t) $ is a Wiener process, representing standard Brownian motion.
