# Historical-Urban-Growth-in-Europe
population change spatial expansion
Berlin
Warsaw
Barcelona
history
geography
urban systems
import matplotlib.pyplot as plt

years = [1950, 1970, 1990, 2010, 2020]
berlin = [3.3, 3.2, 3.4, 3.5, 3.7]

plt.plot(years, berlin)
plt.title("Population Growth of Berlin")
plt.xlabel("Year")
plt.ylabel("Population (millions)")
plt.show()
