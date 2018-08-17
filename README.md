
# LNvis

A Lightning Network Visualizer


## Usage

LNvis requires a json dump of nodes and channels. Currently only clightning
channel/node output is supported

    lightning-cli listnodes > clightning-nodes.json && \
    lightning-cli listchannels > clightning-channels.json && \
    ./lnvis
    

## Controls

```
b             view multiple channels between nodes
t             toggle dark/light theme
a             toggle aliases
g             toggle grid
s             toggle stroked nodes (small perf boost)
left click    move + focus node
right click   filter node
```
