``` python

from datetime import datetime, timedelta, date
import pandas as pd
from clean import data_merge
import seaborn as sns
import matplotlib.pyplot as plt
import time

f_date = date(2017, 8, 17)
l_date = date(2022, 4, 28)
delta = l_date - f_date
days_loop = int(delta.days)

start_date = f_date.strftime("%Y%m%d")
end_date = l_date.strftime("%Y%m%d")
curr_date = start_date
end_int = int(end_date)

```


