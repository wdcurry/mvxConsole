# mvxConsole MultiversX App

The MultiversX blockchain (formerly known as Elrond) and ecosystem offers amazing user-experiences, so mvxConsole was created to both augment the standard validator node operation shell script and to provide a smoother environment for new node operators. It wraps all the calls currently available and adds a few new features to make a MultiversX validator's life even easier!

<img width="1144" alt="mvxConsole(0 7 8)" src="https://user-images.githubusercontent.com/2454749/210174829-cad160b9-511f-4aeb-bc4f-7f51e0d58db8.png">

## Getting Started

These instructions will get mvxConsole up and running on your existing MultiversX server.  We recommend trying it out on a testnet server first to familiarize yourself with its features. Trust though, it is designed to be as simple as possible!

### Prerequisites

To run mvxConsole, all you need: a working MultiversX server running ubuntu 20.04.5 LTS.  It was created & tested in Bash (5.0.17(1)-release). It should work on any ubuntu that allows the node software to work, but it simply was not tested on other versions.

```
A MultiversX node running on an unbuntu server.
The lastest version of mvxConsole.vXYZ.tar.gz
```

### Installing

A step-by-step guide to obtain and install mvxConsole:

The latest public version is at: [https://github.com/wdcurry/mvxConsole](https://github.com/wdcurry/mvxConsole)

Copy the tar file into the MultiversX scripts folder, assuming it is in your ~ folder (adjust accordingly):

```
mv ~/mvxConsole.v0.7.8.tar.gz ~/elrond-go-scripts/
```
Switch into the scripts folder (assuming your install is standard):

```
cd ~/elrond-go-scripts/
```
Unzip the tar file:

```
tar -xzvf mvxConsole.tar.gz
```
That is it! Now you run mvxConsole with the following (and we highly recommend an alias to an executable script that will simplify the startup.

```
~/elrond-go-scripts/mvxConsole.sh
```



A simple test is to fire up mvxConsole and choose to run TermUI, currently option N. Just tap the N key once, no need for [Enter]. The app will automatically determine how many nodes you have and act accordingly. If only one is installed you will go directly to it. If you have more than one, it will present a list of nodes to select from. No need to hit the enter key while making selections, and you can only enter valid responses. Once you exit TermUI via ctrl-C, you will be back into mvxConsole automatically!

## A Few Features

- mvxConsole was designed to minimize effort for node operators.
- Wraps every call currently available in the standard script.sh provided by MultiversX in a slightly more polished UX.
- Single key presses to select options, and feedback in the form of "ⓧ" will appear if your choice is invalid.
- For new validators, if no github token is set, the app will remind you.
- The entire upgrade sequence is now automated for you, with optional stepXsstep mode to provide you with more involvement in the upgrade.
- A full Testnet upgrade is possible, but will not proceed for a mainnet install.
- A clean environment allowing for expansion as MultiversX expands

### Coming Features

- The ability to easily toggle nodes between DEBUG and INFO modes!
- A concise display of your nodes, their Eligible state, and their running state!
- and a few more goodies planned!

## Author

* **drew curry** - "The EGLD Guy" @ [ApeStaking](https://www.ApeStaking.com)


## License

This project is licensed under the GNU License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Special thanks to TerryR with ApeStaking for providing support
* The tranquil life in San Miguel de Allende, Mex
* MultiversX, for changing my life!
* coffee, did i mention coffee?
* Btw, feel free to stake your EGLD with us (ApeStaking.com). Smaller Staking Providers offer you similar ROI AND we are essential to the true decentralization of the most amazing tech in the blockchains space: MultiversX.
