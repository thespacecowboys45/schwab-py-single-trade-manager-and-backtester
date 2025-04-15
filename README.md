# Single Trade Manager and Backtester

Documentation forthcoming.

[![Lines of Code](./media/count_lines_of_code_04152025.png)](https://www.stockmarketswizzles.com)

##### Disclaimer:

The information on this page is for informational purposes only.  There are inherent risks to trading.  By trading you assume those risks.  The authors assuage responsibility for trading decisions that you may, or may not, make based on any information derived from the works within these pages.


##### Where do I get the code?

The intent is for a collaborative effort on development and feedback at this stage.

This is done via a private repo, and access can be granted for collaborators and interested 3rd parties.

Get in touch via: [ TBD if you do not have contact ] [ at the moment ] [ Discord is best ]

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

#### Strategy Configuration Language Model

A flexible language model for describing trade signals including:

- Time of Day Entry / Exit
- Price point Entry / Exit
- Indicator Signals Entry / Exit

Signals may be evaluated on an [ AND | OR ] basis, meaning an "ALL or ANY" evaluation.

[![Strategy Config Language Models](./media/strategy_config_language_model.png)](https://www.stockmarketswizzles.com)


# Screenshots of Vizualizations

Single Trade Manager is designed to work and output data compatible with a visualization layer to see entry / exit signals and technical indicator signals on an OHLCV chart.

### Entry Signal

##### Entry signal triggers at 12:30pm EST (according to parameters set from the **main Interface**)

These parmeters are tunable and vary according to the assigned strategy.

[![Main Interface](./media/image_entry_signal_v1.png)](https://www.stockmarketswizzles.com)

### Exit Signal

##### Exit signal triggers at 3:40pm EST (according to parameters set from the **main Interface**)

These parmeters are tunable and vary according to the assigned strategy.

[![Main Interface](./media/image_exit_signal_v1.png)](https://www.stockmarketswizzles.com)


### Trade Report

A trade report which shows basic statistics including batting-average, PnL, and # of trades.

[![Main Interface](./media/image_trade_report_v1.png)](https://www.stockmarketswizzles.com)
