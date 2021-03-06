# HillScript
This is a simple scripting language which allows you to do simple tasks similarly to lua (but probably has an even lighter implementation)


## Features
- Simple scripting
- Examples provided
- Can include other scripts
- Easily portable since there is not much code
- Coded in 1 day
- Also features shorter versions of names so you can code faster
- Lightweight implementation

## Demo programs
The demo programs can be found inside the `examples` directory. Here's one of them:
```
// Program name: "Maths"
// Version: 1.0
// (C) 2020 iProgramInCpp
// This serves as an example for the HillScript scripting language
// The HillScript scripting language is a very simple scripting language
// which can take care of simple scripting needs, similarly to lua.

global_var|int|var|69

return_value_type|int
start_function|main
	printl_fmt|"var initially: {0}"|var
	add_var|var|8
	printl_fmt|"var after incrementing by 8: {0}"|var
	sub_var|var|192
	printl_fmt|"var after subtracting 192: {0}"|var
	add_var|var|-19248
	printl_fmt|"var after adding -19248: {0}"|var
	set_var|var|0
	printl_fmt|"var after setting to 0: {0}"|var
	bnot_var|var
	printl_fmt|"var after bnotting: {0}"|var
	bnot_var|var
	printl_fmt|"var after reset: {0}"|var
	set_var|var|0xDEADBEEF
	bxor_var|var|0xBEEFDEAD
	printl_fmt|"var after (0xdeadbeef ^ 0xbeefdead): {0}"|var
	set_var|var|0xDEADBEEF
	band_var|var|0xBeefdead
	printl_fmt|"var after (0xdeadbeef & 0xbeefdead): {0}"|var
	set_var|var|0xDEADBEEF
	bor_var|var|0xBeefdead
	printl_fmt|"var after (0xdeadbeef XOR 0xbeefdead): {0}"|var
	set_var|var|2
	pow_var|var|8
	printl_fmt|"var 2 to the power of 8: {0}"|var
	sqrt_var|var
	printl_fmt|"var sqrt(2^8): {0}"|var
	return|0
end_function
```
