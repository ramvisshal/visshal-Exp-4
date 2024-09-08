# visshal-Exp-4
from pandas import read_csv
from matplotlib import pyplot
series=read_csv(r'C:\visshal\airline-passengers.csv')
print(series.head())
series.plot()
pyplot.show()
![1](https://github.com/user-attachments/assets/b9b4d443-8075-45d8-bb26-f2457d8892b1)
series.plot(style='-.')
pyplot.show()series.plot(style='-.')
pyplot.show()
![2](https://github.com/user-attachments/assets/caa9a772-ff2e-46b8-b30f-b826d0a15830)
series.plot(kind='kde')
pyplot.show()
![3](https://github.com/user-attachments/assets/69b27f7d-25c4-498f-b19e-d0d086a89bdf)
series.hist()
pyplot.show()
![4](https://github.com/user-attachments/assets/e336b371-1380-47f8-bd3f-3b91de60dc85)
