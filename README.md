# installation

inside your wsl, clone this repo and copy binary file to /usr/local/bin

        git clone https://github.com/Snavens/cyg-wsl.git

        cp -rvf cyg-wsl/cyg-wsl /usr/local/bin && chmod 755 /usr/local/bin/cyg-wsl

## usage

cyg-wsl [arg option] [name option]

    ARG OPTIONS:

    install <option>    --> installs the specified package into cygwin terminal
                other options:

        --fix-broken    tries to fix packages that failed during installation process
                        also try searching for a specific version using search option
                        if this fix does not work

    reinstall       --> reinstall a package which is already installed

    installd        --> install a package and all of its dependencies

..and more

## disclaimer

this script is for personal development use only please
