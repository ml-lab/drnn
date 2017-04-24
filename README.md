# drnn
Doubly-recurrent neural networks


### Dependencies


#### Software

* Torch7 (`luarocks install ...`)
* penlight
* nn
* nngraph
* optim
* rnn
* OpenNMT (only needed for MT task)


#### Data

Only data for synthetic task is provided. MT and IFTTT have to be downloaded separately.

### Basic Usage

./demo_vanilla.sh [TASK] (where task is one of synth, BABYMT, IFTTT)

Trains, evaluates and saves predictions.
