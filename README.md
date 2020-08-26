# Binance Toolbox

Some useful scripts that help API users to validate endpoints or API settings

Futures is not supported here.

## How to use
It's required to install the `binance-connector-python` package

```python
pip install binance-connector-python

```

## Scripts
### `place-order.py`
A simple one to place an order and cancel it every second, you are free to adjust parameters to place any orders.
Support with testnet

### `break-symbols.py`
List symbols in status

### `order-update-latency.py`
Listens to the user's websocket and creates a fixed number of orders to list the Transaction vs Event time (T vs E) 
and Event vs Received time (T vs Now) for every order update
(Adjust script as needed)

### `manage-orderbook.py`
Creates, manages a local orderbook and prints out its best prices.
Based on https://binance-docs.github.io/apidocs/spot/en/#diff-depth-stream.

