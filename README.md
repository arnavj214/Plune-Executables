# PLUNE - PLotting Utility N Exporter

## Usage
Download the correct folder for for the specific machine. You must also create an empty folder named logs in the same directory which is where all of the converted logs will be held. Any logs that you want displayed should be put in the raw_logs directory.

### `./plune.exe -c, --convert`
Convert all raw binary logs to JSON files. By deafult, `raw_logs/*.bin` are converted to JSON files in `logs/`.

### `./plune.exe`
Run the webserver. Displays all JSON logs in `logs/` (must convert binary logs first).

