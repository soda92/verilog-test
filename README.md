# verilog-test

commands

```sh

iverilog -o wave led_demo_tb.v led_demo.v -y ./
vvp -n wave -lxt2
gtkwave wave.vcd
```
