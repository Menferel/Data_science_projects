OilyGiant seeks to expand its operations by developing 200 new oil wells. The objective was to create a predictive model that estimates the volume of reserves in three candidate regions and thus identify the most profitable zone under investment and risk conditions.

- Data: Technical characteristics (f0, f1, f2) and reserve volume (product) in thousands of barrels for each well.
- Libraries: Pandas, Numpy, Sklearn (models, metrics, and others)
- Conditions: Budget of $100M for 200 wells. The well must generate ≥111.1 thousand barrels (~$500,000) to avoid losses. Minimum acceptable loss margin: 2.5%.
- Results:
  * A model was trained for each region.
  * The expected profit and risk of loss were calculated using statistical simulation.
  * The region with the highest average profit and risk below the threshold was chosen.
