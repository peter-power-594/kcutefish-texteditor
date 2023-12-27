# Text Editor

Elegant text editor for CutefishOS. 

![screenshot](screenshots/Screenshot_20211221_212801.png)

## OpenMandriva Dependencies

```
sudo dnf in task-develop
sudo dnf install lib64KF5SyntaxHighlighting-devel
```

## Build

```shell
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
```

## Install

```shell
sudo make install
```

## License

This project has been licensed by GPLv3.
