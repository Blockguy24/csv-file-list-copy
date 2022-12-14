# CSV File List Copy
This is a small utility written in Python to copy files based on the contents of a CSV file.

## Usage
```
usage: csv-file-copy.py [-h] [-c COLUMN_NAME] [-q] [-o] [--dry-run]
                        csv_file source_dir target_dir
```

### Positional Arguments
`csv_file` - CSV file specifying files to copy

`source_dir` - Source directory

`target_dir` - Target directory

### Optional Arguments
`-h, --help` - Display help message

`-c COLUMN_NAME, --column-name COLUMN_NAME` - Column to read from the CSV file (default: `"filename"`)

`-q, --quiet` - Suppress program output

`-o, --overwrite` - Overwrite file if it already exists in destination (default: skip file)

`--dry-run` - Don't copy files, just print what would've been copied
