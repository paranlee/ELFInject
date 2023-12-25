# ELF Injection Example

```
./build.sh
./strlen
./inject strlen payload
./strlen

# or

cp /bin/ps .
./inject ps payload
./ps
```

Default payload shows a message printed to STDOUT in red.

- https://asciinema.org/a/369635

