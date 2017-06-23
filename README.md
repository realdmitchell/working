# Setup KDE in xenial

```
export PATH="$PATH:/othersoft/local/kde/bin"
export KDEDIR="/othersoft/local/kde"
export XDG_DATA_DIRS="$XDG_DATA_DIRS:/othersoft/local/kde/share"
```

# Download the appropriate tar from ubuntu trusty. See the bash file


# Setup
add to your .bashrc

```
kate2(){
export PATH="$PATH:/othersoft/local/kde/bin"
export KDEDIR="/othersoft/local/kde"
export XDG_DATA_DIRS="$XDG_DATA_DIRS:/othersoft/local/kde/share"
kate "$@" 2>/dev/null
}
```


