# Shell

## Print empty line

```sh
echo
```

## `expr`

```sh
expr 1 + 1
```

```sh
$((1 + 1))
```

## Mapping characters with `tr`

```sh
tr '123456' '654321'
```

Input: `654321`

Output: `123456`

## While loop with increment

```sh
n=10
x=0
while [ $x -lt $n ]; do
    # Do something
    x=$(($x + 1)) # Increment
done
```

## For `i` in `seq`

```sh
n=10
for i in `seq $n`; do
    echo $i
done
```

