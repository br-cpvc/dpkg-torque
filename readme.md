# Description

The deb packages here were downloaded from the following urls based on links found via
https://packages.ubuntu.com/xenial/utils/torque-server

The packages are torque packages from the Ubuntu Xenial apt repository, which are not available on newer Ubuntu version as they no longer have any maintainers. As we want to use these packages on newer Ubuntu versions, we have downloaded ans stored them to serve be able to serve them from using a private apt repository.

http://mirrors.kernel.org/ubuntu/pool/universe/t/torque/torque-server_2.4.16+dfsg-1.5_amd64.deb
http://mirrors.kernel.org/ubuntu/pool/universe/t/torque/torque-mom_2.4.16+dfsg-1.5_amd64.deb
http://mirrors.kernel.org/ubuntu/pool/universe/t/torque/torque-scheduler_2.4.16+dfsg-1.5_amd64.deb
http://mirrors.kernel.org/ubuntu/pool/universe/t/torque/torque-client_2.4.16+dfsg-1.5_amd64.deb
http://mirrors.kernel.org/ubuntu/pool/universe/t/torque/torque-common_2.4.16+dfsg-1.5_amd64.deb
http://mirrors.kernel.org/ubuntu/pool/universe/t/torque/libtorque2_2.4.16+dfsg-1.5_amd64.deb

client dep:
http://mirrors.kernel.org/ubuntu/pool/main/r/readline6/libreadline6_6.3-8ubuntu2_amd64.deb

not currently used as we utilize the Maui scheduler:
http://mirrors.kernel.org/ubuntu/pool/universe/t/torque/torque-scheduler_2.4.16+dfsg-1.5_amd64.deb

on 20250204 added libtinfo5 from https://mirrors.edge.kernel.org/ubuntu/pool/universe/n/ncurses/libtinfo5_6.3-2ubuntu0.1_amd64.deb to enable support of ubuntu 24.04
