# Bash Practice
🖥 Bash Practice


- [Alias bb - BBEdit](#alias-bb---bbedit)
- [FFMEPG Cut from to]()
- [etc]()


## Alias bb - BBEdit

**Add to ~/.profile**

```bash
nano ~/.profile
```

**This Code**

```bash
alias bb="open -a /Applications/BBEdit.app"
```

**And make to install at once**

```bash
source .profile
```

**How to use**

```bash
bb script.sh
```



### FFMEPG Cut from to 

```bash
ffmpeg -i aristotle-ethics-book-5.m4a -ss 00:00:00 -to 00:39:30 -c:a aac -b:a 48k  aristotle-ethics-book-5-p1.m4a
```


