from pandas import read_csv
from matplotlib import pyplot
series=read_csv("airline-passengers.csv")
print(series.head())
series.plot()
pyplot.show()

![Screenshot (8)](https://github.com/user-attachments/assets/986d6969-42c0-4e0a-87a8-53466e68b60a)

series.plot(style='-.')
pyplot.show()

![Screenshot (9)](https://github.com/user-attachments/assets/9690f020-22ef-4524-bf5d-e8d2e252b1ce)

series.hist()
pyplot.show()

![Screenshot (10)](https://github.com/user-attachments/assets/ab82e27f-c733-4ec9-88e8-cfa1a030e922)

series.plot(kind='kde')
pyplot.show()

![Screenshot (11)](https://github.com/user-attachments/assets/73ead679-bef0-4f6d-82ef-9af8ec45330e)
