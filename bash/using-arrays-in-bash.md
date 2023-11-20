# Bash Arrays

Define an array:

`array=( one two three )`

Declare associative array:

```
declare -A array_name
array_name[key]="value"
```

Print array:

```
printf "%s\n" "${array[@]}"
printf "%s\n" "${array[1]"
```

Iterate arrays

```
for i in "${arrayName[@]}"; do
    # "$i" is the value
done
```

Iterate over keys in an associative array:

```
for key in "${!arrayName[@]}"; do
    # $key ${arrayName[$key]}
done
```
