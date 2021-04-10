# user-setup
A service that registers users with the kernel + initial OS configuration

## Building from source

Clone this repository using this command:

`git clone https://github.com/EarthOS-SMC/user-setup`

Then, go to the source code directory:

`cd user-setup`

Before the build process, you need to clone the PowerSlash compiler too:

`chmod +x sync.sh && ./sync.sh`

To build the executables,

`./build.sh usrsetup.pwsle && ./build.sh initcfg.pwsle`


The output executables are `usrsetup` and `initcfg`.

## Reduce output

You can reduce the output by putting `1` in the `reduce` file:
`echo 1 > reduce`
