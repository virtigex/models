# Running cam-mon.py


## Building


cd research/

protoc object_detection/protos/*.proto --python_out=.

cd object_detection

export PYTHONPATH="$PYTHONPATH:.:.."

## Running

python cam-mon.py 

to quit press 'q' while in the window.

