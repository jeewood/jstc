jstc
====

jstc-isp is a stc mcu command line programmer tool, 

usage:

jstc com2 file.hex -pause -loop

com2      is your com port connect to stc mcu target board

file.hex  is the file make from keil. this file can be a Bin file.

-pause    flash / program / download completed, wait a key press to exit

-loop     this option can flash a barrel of mcu, need not to re-run the tool

Following MCU are tested, just program flash rom, 

program option are current not supported!

STC89 series

STC12 series

STC12C54 series

STC15 series


为方便开发，设计了一个命令行的stc单片机下载工具软件， 现在只支持程序下载，不支持选项设置。

测试过的单片机有 

STC89C52RC (STC89系列)

STC12C5410 (STC12C54系列)

STC12C5406AD (STC12C54系列)

STC11F04E (STC12C系列)

STC12C5604 (STC12C系列)

IAP15F2K61S2 (STC15系列)

理论上支持STC全系列单片机的程序下载！

