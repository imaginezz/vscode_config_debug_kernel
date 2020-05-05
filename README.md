# VSCode Config File for Linux Kernel Debug

# Usage 

- Ensure you've build the Kernel (at least, all *.cmd files should be generated).
- Add C/C++ Extension in VSCode's Marketplace.
- Clone this repository as Kernel Directory's `.vscode` folder, eg. `git clone https://github.com/imaginezz/vscode_config_debug_kernel.git linux/.vscode`.
- Run `generate_compdb.py` in Kernel's root directory, eg `python ./.vscode/generate_compdb.py`.
- Wait for IntellSense completed.
- You can run Kernel in Qemu with GDB Server first, then run debug in VSCode.

# Reference

https://github.com/amezin/vscode-linux-kernel