Purpose & scope: BS vanillas + SVI surface + Heston + PDE CN/Rannacher for barriers + MC for Asians; hedging backtest.
Data policy: mids by default; note later sensitivity to bid/ask.
Validation plan: no-arb checks for surface; convergence studies (PDE grid, MC RMSE vs paths); hedging P&L attribution.
Tolerances: price abs 1e-6, Greek rel 1e-4 (initial targets).
Limitations: equity only; discrete dividends simplified; Heston wing fit; discrete barrier monitoring approximations.