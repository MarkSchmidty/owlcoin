# Owlcoin [OWL, Ø] Integration/Staging Tree

## Owlcoin is currently an exact copy of dogecoin- it is dogecoin! This will change soon. Until then, don't even bother downloading and running this!

## What is owlcoin? - Such coin
owlcoin is like Bitcoin, but based on dogecoin, and also much more of a hoot.

## Development and contributions - omg developers
Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

## Frequently Asked Questions

### How much owl can exist?
100,000,000,000  coins

### How to get a owl?
Scrypt Proof of Work

1 Minute Block Targets, 4 Hour Diff Readjustments

Special reward system: Random block rewards

1-100,000: 0-1,000,000 owlcoin Reward

100,001 — 200,000: 0-500,000 owlcoin Reward

200,001 — 300,000: 0-250,000 owlcoin Reward

300,001 — 400,000: 0-125,000 owlcoin Reward

400,001 — 500,000: 0-62,500 owlcoin Reward

500,001 - 600,000: 0-31,250 owlcoin Reward

600,000+ — 10,000 Reward (flat)

### Wow plz make owlcoind

    sudo apt-get install build-essential \
                         libssl-dev \
                         libdb5.1++-dev \
                         libboost-all-dev \
                         libqrencode-dev \
                         libminiupnpc-dev

    cd src/
    make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1

### Such ports
RPC 22555
P2P 22556
