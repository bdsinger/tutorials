Instructions

this will build a local conda package from the latest
brainiak code and then build the brainiak_tutorials 
conda package, which is just a list of dependencies
including the local brainiak + packages needed for
the tutorials.

The tutorials packge will carry beta brainiak as
a payload.
This is better than polluting the anaconda cloud
namespace with a beta brainiak package which we
did previously.

Steps

from the dir containing this README:

cd bin
./build

any arguments to build will be used in the brainiak build

On Linux the tests hang so can do quick build via

cd bin
./build --no-test


