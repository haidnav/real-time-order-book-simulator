# Real-time Orderbook Simulator 
This Python application simulates a real-time order book, providing a visual representation of buy and sell orders in a financial market. It offers a graphical user interface (GUI) that allows users to observe the order book in action, with randomised buy and sell orders being generated and displayed.

The application generates random buy and sell orders for BTC/GBP and displays them within a graphical user interface (GUI).

![Real-time orderbook simulator screenshot](https://github.com/haidnav/real-time-order-book-simulator/blob/main/orderbook.png)

## Features

- Real-time order book display.
- Random generation of buy and sell orders.
- Highlighting of the highest buy and lowest sell orders.
- Calculation and display of the spread.
- Custom settings for simulation
  

## Requirements

- Python 3.6 or higher
- Tkinter (Python's standard GUI library)

## Usage
1. Download the zip or clone the repo
2. In ```**settings.py**```, change the values for min_price, max_price, min_btc, max_btc and the time interval variables. These settings allow you to tweak the frequency of generations as well as length of simulations.
3. In the terminal, navigate to your projects directory and run ```**python3 app.py**```
   - this should open the GUI interface
   - Click ```**Start Simulation**```
  
