https://rumble.com/upload.php



https://www.brightcove.com/en/why-brightcove/?utm_type=player

https://tradingeconomics.com/commodity/silver

https://www.pybroker.com/en/latest/

https://www.schiffsovereign.com/cost-of-living-index/

https://quant.stackexchange.com/questions/79332/get-bonds-data-in-python

https://andersbrownworth.com/blockchain/

----
# Import the libraries

import numpy as np
import pandas as pd
import pandas_datareader as pdr
import datetime

# Time range

start = datetime.date(2000, 1, 1)
end = datetime.date.today()

# Import the data

yields = ['DGS3MO', 'DGS1', 'DGS10']
df_yields = pdr.DataReader(yields, 'fred', start, end)
