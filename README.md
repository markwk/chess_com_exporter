# Chess.com Data Exporter and Games Played Data Analysis

**Chess.com Data Exporter**: [chess.com_exporter.ipynb](https://github.com/markwk/chess_com_exporter/blob/master/chess.com_exporter.ipynb)

* Pull basic user data, stats and complete history and data of games played from Chess.com Public API 
* Advanced Parsing of [Portable Game Notation (PGN)](https://en.wikipedia.org/wiki/Portable_Game_Notation) to extract relevant data from game play like start time, total moves,  move times of black and white. 
* Export Games Played Data to CSV

**Chess.com Data Analysis of Past Games**: [chess.com_data_analysis.ipynb](https://github.com/markwk/chess_com_exporter/blob/master/chess.com_data_analysis.ipynb)

* Simple Data Analysis and Data Visualization of Games Played

### TODO: 

* Fix to include past days and months where no games played  
* More advanced Data Analysis and Data Visualizations
* Improve Requests logic to deal with API Limitations 
* Additional PGN Parsing
* Calculate the total play time of each player from last timestamp minus total seconds of your side game
* Calculate the average move time of each side

### Development Notes

* Python 3 code in a Jupyter Notebook. 
* Basic usage depends on Pandas and Numpy
* Advanced PGN Parsing uses Chess-Python library which can be installed with the command `$
* I recommend installing Anaconda Distribution of Python to use. 

#### Creator:

* [Mark Koester](https://github.com/markwk/) - read more about his self-tracking and data adventures at [www.markwk.com](http://www.markwk.com)