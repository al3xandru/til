# Show file access, modification, birth time, and inode last change

Can be done using `stat` as follows:

```
stat -f '%Sa %Sm %SB %Sc' -t %Y-%m-%dT%H:%M filename
```

Where

*   `%Sa`: means display access time as string (`S` is the format, `a` is the
    attribute)
*   `m`: modification time
*   `B`: birth time
*   `c`: inode last change
*   `-t` allows customizing the format in which a date is displayed

