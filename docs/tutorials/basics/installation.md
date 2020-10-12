title: Installing Elixir
description: Learn how to install Elixir on your machine

# Installation

![Introduction to Elixir](../../../images/tutorial-elixir/installing-elixir.png)

Learn how to install Elixir and how to setup your machine for development.

At the time of writing, the latest stable version is Elixir 1.11.0, you may have a different version depending when you are reading this tutorial.

## Mac OS

Installing Elixir couldn't be any easy, just make sure you have [Brew](https://brew.sh/) installed and then type the following in the terminal -

    brew install elixir

## Windows

On windows you can install Elixir as you would install just about any program, all you need to do is to [download](https://elixir-lang.org/install.html#windows) the installer and press next till it is installed.

## Other Platforms

Elixir offers excellent support for all other platforms including **FreeBSD** and other unix derived languages, check out [this](https://elixir-lang.org/install.html) page for documentation.

## Checking Installation

You can check the installation, by typing the following in your terminal or powershell -

    elixir -v

Output -

```bash hl_lines="3"
Erlang/OTP 23 [erts-11.1.1] [source] [64-bit] [smp:4:4] [ds:4:4:10] [async-threads:1] [hipe] [dtrace]

Elixir 1.11.0 (compiled with Erlang/OTP 23)
```

Line 3 indicates that Elixir 1.11.0 has been installed and Elixir has been compiled with Erlang 23.0

## Setting up your editor

Elixir is supported in all the leading editors and IDE's, incase you are using **Visual Studio Code**, you only need to install [this](https://marketplace.visualstudio.com/items?itemName=JakeBecker.elixir-ls) plugin.

<!-- Buy me a coffee -->
<script type="text/javascript" src="https://cdnjs.buymeacoffee.com/1.0.0/button.prod.min.js" data-name="bmc-button" data-slug="anilkulkarni" data-color="#FFDD00" data-emoji=""  data-font="Cookie" data-text="Buy me a coffee" data-outline-color="#000" data-font-color="#000" data-coffee-color="#fff" ></script>