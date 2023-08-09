arduino
=======

使った Arduino Nano

[Aliexpress](https://ja.aliexpress.com/item/4000587268145.html?spm=a2g0o.order_list.order_list_main.270.5375585aDJxWBG&gatewayAdapt=glo2jpn) の Type-C Nano

atmega328pではなくatmega328pbがついていた。

![Arduino-nano-chip](https://user-images.githubusercontent.com/138425329/259375550-dea075be-47e1-45c2-b5b8-4c370adcd226.jpg)

[違い](https://avr.jp/user/AN/PDF/AT15007.pdf)

セットアップ参考

[Youtube](youtube.com/watch?v=ZPSqhb4KKNc)

[GitHub](https://github.com/Rahix/avr-hal/tree/main/examples)


Rust project for the _Arduino Nano_.

## Build Instructions
1. Install prerequisites as described in the [`avr-hal` README] (`avr-gcc`, `avr-libc`, `avrdude`, [`ravedude`]).

2. Run `cargo build` to build the firmware.

3. Run `cargo run` to flash the firmware to a connected board.  If `ravedude`
   fails to detect your board, check its documentation at
   <https://crates.io/crates/ravedude>.

4. `ravedude` will open a console session after flashing where you can interact
   with the UART console of your board.

[`avr-hal` README]: https://github.com/Rahix/avr-hal#readme
[`ravedude`]: https://crates.io/crates/ravedude

## License
Licensed under either of

 - Apache License, Version 2.0
   ([LICENSE-APACHE](LICENSE-APACHE) or <http://www.apache.org/licenses/LICENSE-2.0>)
 - MIT license
   ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)

at your option.

## Contribution
Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.
