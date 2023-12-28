---
creation date: 2023-12-28 22:12
modification date: 2023-12-28 22:12
link: https://mathdatasimplified.com/ruptures-detecting-change-points-in-non-stationary-signals/
author: Khuyen Tran
---

<< _Creation date_: [[2023-12-27]] | _Modification date_: [[2023-12-29]] >>


## <u>Code snippets</u>

```Python
import matplotlib.pyplot as plt
import ruptures as rpt
import numpy as np


signal: np.array = ...

# detection
algo = rpt.Pelt(model="rbf").fit(signal)
predicted_breakpoints = algo.predict(pen=10)

#display
rpt.display(signal, predicted_breakpoints)
plt.show()

```

## <u>Other notes and questions</u>
 
- Ruptures to detect change points from non-stationary signals such as trend, seasonality, and variance.
- With change points, you can detect anomalies or deviations from the expected behavior and gain insights into when these transitions occur.


- <u>Tags</u>: #TimeSeries
- <u>Related</u>:

> [!quote] It is the province of knowledge to speak, and it is the privilege of wisdom to listen.
> — Oliver Wendell Holmes Jr.