# Mynth White Paper

Welcome to the Mynth open-source white paper repository. This document
guides you through the process of building the white paper using
`pdflatex`.

Mynth is a synthetic asset swapping platform that enables seamless
conversion of synthetic assets to real-world assets. It addresses
challenges like inapplicability and temporary depegging. The platform
simplifies the complex arbitrage and conversion process for users,
ensuring secure and swift transactions. By connecting synthetic and real
assets, Mynth increases accessibility and appeal of synthetic assets to
a wider range of users.

The latest version of the Mynth white paper can be viewed at
<https://mynth.ai/paper>.

## Prerequisites

Before you begin, ensure you have the following installed on your
system:

  - TeX distribution (e.g., TeX Live, MiKTeX, or MacTeX)
  - pdflatex (included in the TeX distribution)

To install `pdflatex`, you need to install a TeX distribution that
includes it. One popular option is TeX Live. Here’s how to install it on
various operating systems:

### Windows

1.  Download the TeX Live installer from
    [here](https://www.tug.org/texlive/acquire-netinstall.html) by
    selecting the `install-tl-windows.exe` file.
2.  Run the installer and follow the on-screen instructions.

### macOS

1.  Download the MacTeX distribution from
    [here](http://www.tug.org/mactex/).
2.  Open the downloaded `.pkg` file and follow the installation
    instructions.

### Linux (Debian/Ubuntu)

1.  Open a terminal and run the following command: `sudo apt-get install
    texlive-latex-base`

This installs the basic TeX Live package. If you need additional
packages, install the full TeX Live distribution with: `sudo apt-get
install texlive-full`

After the installation is complete, you should have access to the
`pdflatex` command. To check if it’s installed correctly, run `pdflatex
--version` in your terminal or command prompt.

## Building the White Paper

1.  Locate the main file, `main.tex`, in the repository.

2.  Open a terminal or command prompt.

3.  Navigate to the directory containing `main.tex`.

4.  Run the following command to generate the PDF:
    
    ``` 
     pdflatex –shell-escape main.tex
    ```
    
    This command will produce a file named `main.pdf`.

5.  Open `main.pdf` with your preferred PDF viewer to view the Mynth
    white paper.

## Contributing

We welcome contributions to the Mynth open-source white paper. If you’d
like to make improvements or changes, please fork the repository, make
your changes, and submit a pull request.

## License

This work is licensed under the Creative Commons Attribution 4.0
International License. To view a copy of this license, visit
<http://creativecommons.org/licenses/by/4.0/> or send a letter to
Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

When using this work, please attribute the original author(s) and
include a link to the license.

## Support

If you have any questions or issues, please open an issue on the GitHub
repository or contact the Mynth team on Discord. You can view more
information on the [Mynth website](https://mynth.ai/).

Thank you for your interest in Mynth and its white paper.
