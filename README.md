# hekate-pqc

Post-quantum AIR chiplets for the [Hekate](https://github.com/oumuamua-labs/hekate) ZK proving system. Implements
ML-KEM (Kyber) decapsulation and ML-DSA (Dilithium) signature verification natively in binary fields, with supporting
NTT, basemul, high-bits, norm-check, and twiddle-ROM chiplets.

```
Proving on Apple M3 Max:
  ML-KEM-768  : 1.40 s,  331 MB peak, 4,232 KiB proof, 30.6 ms verify
  ML-DSA-44   : 2.43 s,  294 MB peak, 5,139 KiB proof, 69.0 ms verify
  ML-DSA-65   : 2.54 s,  294 MB peak, 5,156 KiB proof, 70.7 ms verify
  ML-DSA-87   : 3.98 s,  580 MB peak, 8,620 KiB proof, 115.6 ms verify
```

## License

Apache-2.0. See [LICENSE](LICENSE) and [NOTICE](NOTICE).