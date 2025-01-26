# High-Frequency Trading Based on Directional Change Intrinsic Time

A project implementing a high-frequency trading strategy using directional change intrinsic time as the basis for decision-making.

# Code

## Introduction:

This program implements a trading strategy based on the principles described in "High Performance Computing in Finance" by by M. Dixon, H. Halperin, and P. Bilokon. It uses intrinsic time, where events are triggered by directional price changes, to identify potential trading opportunities in FX markets. The main components include:

- Event-based time representation with a movement size threshold parameter.
- Strategy logic based on the scaling law: after a directional change, an overshoot of the same magnitude tends to follow.
- Visualisation of directional changes, entry and exits.
- Backtesting of the strategy using historical FX data.

## How to Use My Program:

Following the notes in the notebook.

### Prerequisites:
Recommend using Jupyter Notebook (via Anaconda or standalone) with Python 3.9 or later.
