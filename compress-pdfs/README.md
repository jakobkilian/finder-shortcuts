# compress-pdfs

Compresses selected PDFs in Finder and puts them in a directory called `compressed`.

## Installation

This shortcut requires **Ghostscript** to be installed on your Mac.

1. **Install Homebrew** (check if you already have it by typing `brew`):
   
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

2. **Install Ghostscript**

````bash
brew install ghostscript
````

## Technical Details

This is the Ghostscript and the settings I am using to compress the PDFs

````
gs -sDEVICE=pdfwrite -dNOPAUSE -dQUIET -dBATCH \
    -dCompatibilityLevel=1.4 \
    -dPDFSETTINGS=/screen \
    -dDownsampleColorImages=true -dColorImageResolution=300 \
    -dDownsampleGrayImages=true -dGrayImageResolution=300 \
    -dDownsampleMonoImages=true -dMonoImageResolution=300 \
    -sOutputFile="$output_file" "$input_file"
````

