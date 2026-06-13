dslpy is short for Dislpay, a misspelling of Display

why dslpy?

dslpy exists because it aims to solve echo $XDG_SESSION_TYPE, by making it Display Manager Agnostic using $DISPLAY and $WAYLAND_DISPLAY calls

why $XDG_SESSION_TYPE is Flawed

$XDG_SESSION_TYPE is Flawed because it depends on a display manager to work, for anyone using a minimal setup by only typing startx or wayland equivalents, this is a problem, because $XDG_SESSION_TYPE will only output tty on these setups, regardless if you actually have an X Server or Wayland Compositor

how to get dslpy

first use wget to get the package download from the terminal
wget https://github.com/Dexter8733/dslpy-pkg/releases/download/1.0-1/dslpy-deb.deb

then install it

Install with Apt
sudo apt install ./dslpy-deb.deb

Install with Nala
sudo nala install ./dslpy-deb.deb
