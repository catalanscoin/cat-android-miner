# CATALANSCOIN ANDROID MINER

CatalansCoin android miner is a fork from upx android miner. We made a little redesign and added our catrig binaries to make It work.

In our next update miner will be optimized to have best hashrate on IoT devices.

# Usage

This will currently only work on devices with ARM64 architecture.

Install and run the app, goto settings, enter your wallet address, press the start button
to start mining or stop to stop mining.
  
# Notes
  
The xmrig binary is copied to the app's internal directory along with its dependent libraries.
(Because it can only be executed there)

The binary is started using the ProcessBuilder class, and the output is captured
into the app's scrolling pane once each secons.

Currently only arm64 binaries are included, and the app will refuse to work on 
other architectures like x86 or 32 bit devices. 
