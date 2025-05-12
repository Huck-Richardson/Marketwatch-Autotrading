# Marketwatch Autotrading
An auto stock trading algorithm. It averages the last month of prices to make a baseline price. Then it combines that with the hourly prices with a 3 : 10 ratio respectively. If the price is above the calculacted average it sells, if its below it buys. It includes crash detection to hold all assests when the market crashes.
