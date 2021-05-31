# minecraft-ntgbtminer
Video Tutorial / Explanation:  
https://www.youtube.com/watch?v=sLClfQdmzPw  

This project is a fork of ntgbtminer to mine bitcoins in minecraft  
I don't have my own crypto wallet nor am I old enough for paypal but I do have a patreon. One time donations are fine and much appreciated  
https://www.patreon.com/cmdrredstone

# ntgbtminer
ntgbtminer is a no thrills
[getblocktemplate](https://en.bitcoin.it/wiki/Getblocktemplate) Bitcoin miner.
It is not performant, but demonstrates basic use of the getblocktemplate
protocol for a standalone Bitcoin miner. It has no dependencies outside of
standard Python libraries and a JSON-HTTP connection to your local Bitcoin
daemon.

Donations (to the original developer of ntgbtminer) are welcome at `15PKyTs3jJ3Nyf3i6R7D9tfGCY1ZbtqWdv` :)

## Usage

* Configure `rpcuser` and `rpcpass` in `~/.bitcoin/bitcoin.conf`

* Start bitcoind

```
$ bitcoind -testnet -daemon
```

* Run ntgbtminer


I changed a few things so you just have to edit stuff inside the python file and just launch it normally.
Run the minecraft save, and open chat, then run the program. Choose your .minecraft directory, then go back to minecraft and press escape.
Download Minecraft world here:  
https://www.mediafire.com/file/si1aamfblbi2nqs/Bitcoin_Miner_by_CommanderRedstone.zip/file

## License

ntgbtminer is MIT licensed. See the provided [`LICENSE`](LICENSE) file.
