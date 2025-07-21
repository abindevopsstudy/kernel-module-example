# kernel-module-example
A kernel module example written by me, a kid. any feedback is welcome here
# What is this kernel module for?
This is a kernel module, that compares two strings: 'x' and 'y' and outputs the number that strcmp() gave back in dmesg.
# How to use this?
First, download it:
`git clone https://github.com/abindevopsstudy/kernel-module-example`
Second, insert the module:
`cd kernel-module-example`
`sudo insmod kernelmodule.ko`
Third, grep for the output:
`dmesg | grep "W"`
It will show:
`Well, [nonsense]: read this! it's: -1 :: what a dumb answer.`
