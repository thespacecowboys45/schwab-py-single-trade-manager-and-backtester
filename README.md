# Single Trade Manager and Backtester

Documentation forthcoming.

##### Disclaimer:

The information on this page is for informational purposes only.  There are inherent risks to trading.  By trading you assume those risks.  The authors assuage responsibility for trading decisions that you may, or may not, make based on any information derived from the works within these pages.

# Requirements

* schwab-py
* Flask
* python3

# Installation

The hope is to be able to run:

```

pip install -r requirements.txt

```

May or may not work.

# Screenshots

#### Main Interface

The main interface is where the entry point of the application is.

- Backtester
- Live trade Manager
- Stop Live trade manager

[![Main Interface](./media/image_main_interface_v1.png)](https://www.stockmarketswizzles.com)

#### CLI Interface

A command-line interface which allows operations of the underpinnings.

<a href="https://www.stockmarketswizzles.com">
  <img src="./media/image_cli_interface_v1.png" alt="Main Interface" height="300">
</a>

#### Strategy Mapper

Use this interface to assign strategy or strategies to symbols.

[![Main Interface](./media/image_strategy_mapper_v1.png)](https://www.stockmarketswizzles.com)


#### Strategy Manager

Use this interface to add/edit/delete/and re-factor and iterate on a strategy or strategies.

[![Main Interface](./media/image_strategy_manager_v1.png)](https://www.stockmarketswizzles.com)


# Screenshots of Vizualizations

Single Trade Manager is designed to work and output data compatible with a visualization layer to see entry / exit signals and technical indicator signals on an OHLCV chart.

### Entry Signal

[![Main Interface](./media/image_entry_signal_v1.png)](https://www.stockmarketswizzles.com)

### Exit Signal

[![Main Interface](./media/image_exit_signal_v1.png)](https://www.stockmarketswizzles.com)


### Trade Report

[![Main Interface](./media/image_trade_report_v1.png)](https://www.stockmarketswizzles.com)
