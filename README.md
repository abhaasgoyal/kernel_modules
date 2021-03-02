# Introduction

Some kernel modules for linux (to learn OS concepts as of now)

# Usage

For a particular module:

* Compile

```
make
```

* Insert into kernel

```
sudo insmod <modulename>.ko
```

* Remove from kernel

```
sudo rmmod <modulename>
```

* Remove object/built files

```
make clean
```
