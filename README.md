# Holberton Project Check


## What is this?

Holberton Project Check helps Holberton School's students make sure that all their files are the ones that are expected before they get QA reviewed by HolbertonCloud.
- By default, the program creates the directories and files required for each task.
- Use the flag '-check' when running the program to check if the required files exist.

You need an account on Holberton School's intranet in order to use this.


## How to use on Mac OS

Download [the latest release](https://github.com/rudyrigot/holberton_project_check/releases).

Then, change your directory to your project's directory, and (assuming the binary was downloaded in `~/Downloads`) run:
```
chmod u+x ~/Downloads/holberton_project_check
~/Downloads/holberton_project_check [-check]
```


## Run from source

Install Go (don't forget to setup a GOPATH), clone the repository under `$GOPATH/src`, and then:
```
go get github.com/howeyc/gopass
cd /path/to/your/project  # Replace with the path to your project
go $GOPATH/src/holberton_project_check/run *.go
```

## Build:

```
cd $GOPATH/src/holberton_project_check
go build -o holberton_project_check *.go
```


## Contribution

Contributions are welcome, whether to fix some Go style (I am fairly new to Go), or to build more features. Just open a pull request!
