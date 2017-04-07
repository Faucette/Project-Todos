## Randomness

For a lot of our projects we need good random number generation.
Currently we need randomness for backend test object generation and generation of questions and exercise problems on the platform.


### JS and Rust Libs

- [x] Generate Cross-Browser high quality random byte sequences
  -  [jwaterfaucett/js-random_byte_sequence](https://github.com/jwaterfaucett/js-random_byte_sequence)
- [ ] Create a RNG Library which does
  - [ ] RNGs for Integers
  - [ ] RNGs for f64 and f32
  - [ ] RNGs for Booleans (essentially 0 or 1)
  - [ ] RNGs which conform to i8/u8, i16/u16 ... to i128/u128
  - [ ] RNG sequences of all the above types
- [ ] Create RNG user-facing toolkit with the following functions
  - [ ] RNG min, max, and range functions
  - [ ] RNG from Distributions (Gaussian, Log Normal, Poisson, etc.)
- [ ] Create Wrapper Libs with API and plugins which generate
  - [ ] Random names
  - [ ] Random emails
  - [ ] Random phone numbers
  - [ ] Random ages
  - [ ] Random dates and times
  - [ ] other test objects as we need them
