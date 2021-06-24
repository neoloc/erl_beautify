# config_cleaner

## Contains

- script to generate a beautified edge router configuration from the output of ''show configuration commands''

## How to download

1) Download the repository

    mkdir -p $HOME/.local/src
    git clone https://github.com/neoloc/erl_beautify.git $HOME/.local/src/erl_beautify

## How to use

1) Link the config_cleaner script somewhere more useful

    ln -s $HOME/.local/src/erl_beautify/config_cleaner $HOME/.local/bin/

2) Download the configuration from an ERL device.

    From and ERL device:
        show configuration commands

    Save output of the above command into a file like '/path/to/input_file'

2) Run the script against the input file. Optionally, redirect output to a file like output_file

    config_cleaner /path/to/input_file > /path/to/output_file
