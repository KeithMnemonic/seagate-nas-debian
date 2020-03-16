1) clone kernel from git clone git://git.kernel.org/pub/scm/linux/kernel/git/stable/linux-stable.git

2) check out working branch git checkout -b stable v4.14.173

3) copy in old config

4) patch for cavium

5) make config: yes '' | make oldconfig

6) build kernel: make

7) Build uImage
