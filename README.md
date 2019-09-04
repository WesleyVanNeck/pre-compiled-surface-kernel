# pre-compiled-surface-kernel
this surface kernel is patched with https://github.com/kitakar5525/ipts-fix-crash

### for now this is only for debian and ubuntu other distros comming soon

### Instructions for Firmware

0. (Prep) Install Dependencies:
  ```
   sudo apt install git curl wget sed
  ```
1. Clone the linux-surface repo:
  ```
   git clone --depth 1 https://github.com/qzed/linux-surface.git ~/linux-surface
  ```
2. Change directory to linux-surface repo:
  ```
   cd ~/linux-surface
  ```
3. Run setup script:
  ```
   sudo sh setup.sh
  ```
4. Reboot on installed kernel.


### creddits

- kitakar5525
- jakeday
- StollD
- qzed 
- sebanc
