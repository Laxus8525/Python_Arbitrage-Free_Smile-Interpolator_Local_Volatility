# Python_master_project_arbitrage-free_smile-interpolator_local_volatility

Data is usdjpy market quote delta on 16-Mar-2023, downloaded from Bloomberg. The details about the constraints of free arbitrage are stated in the jupyter notebook.
Using market data to derive the strike price then interpolate the implied volatilty and local volatolity. 
Visualize the implied vol surface and local vol surface. 
Use PDE with local volatility model to price a given set of European options (strike in delta  ×  maturity)
Compare the price errors of arbitrage-free smile interpolator and the cubic spline smile interpolator
