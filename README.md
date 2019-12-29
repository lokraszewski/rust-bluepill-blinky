# rust-bluepill-blinky
Simple STM32 Bluepill Blinky


# Build
```
cargo build --release
```

# Run
Open a openocd session:
```
openocd 
```

`cargo` will invoke the runner defined in `.cargo/config`, in this case it will be gdb-multiarch
```
cargo run --release 
```
