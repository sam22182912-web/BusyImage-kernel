https://private-user-images.githubusercontent.com/233587364/492032915-79a0654e-b737-481d-8cf3-eb7b44c1290d.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTg0NjY5MzUsIm5iZiI6MTc1ODQ2NjYzNSwicGF0aCI6Ii8yMzM1ODczNjQvNDkyMDMyOTE1LTc5YTA2NTRlLWI3MzctNDgxZC04Y2YzLWViN2I0NGMxMjkwZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwOTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDkyMVQxNDU3MTVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1mYzE1ZmE4ZWUwNTYwODcwYTgxMWQ5YzQ5ZjdlNzU2YjQxZWYyMjE3NjM5YjYxOTIwMTE5YmFiNzcwN2MzMTViJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.G3GeC1PnRKpdMpjMP11i9UjzRwNcVhV_nDyC25Dln4I
BusyImage is linux distro that was build using Buildroot.
This repository is like gentoo but busyimage with buildroot sources.
They said was "You do not need to be root to build or run buildroot."
Thats true afterall.

This is what you need before compiling BusyImage's starter image.

1) run `make menuconfig` to configure your image.

2) run `make -j$(nproc)` to compile with your cores or without it your computer might explode.

3) extract your rootfs.tar in the `output/images/rootfs.tar` after compiling and edit the os-release.

Have fun! :)
