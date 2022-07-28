The following code in Rust calculates successive square root of the largest-possible 64-bit real number:

```rust
use std::f64::MAX; // std::f64 is not actually needed to use sqrt()
fn main() {
    let mut n: f64 = MAX; // Largest finite f64 value.
    println!("n = {}", n);
    for i in 1..65 {
        n = n.sqrt();
        println!("i: {}    n = {}", i, n);
    }
}
```

It's not colour-coded in the way I prefer, but it is good enough.  

Let's include a weblink to [Rust](https://www.rust-lang.org/) and an internet SVG image scaled at 50%: 

<img src="https://www.vectorlogo.zone/logos/rust-lang/rust-lang-ar21.svg" style="zoom:50%;" />

Let's write some maths using the ```-s --katex``` parameter : $a^2 + b^2 = c^2$.  This is Euler's Identity: $e^{i\pi} + 1 = 0$ 

This is adapted from the [Katex](https://katex.org/) website:

$$
f(x) = \int_{-\infty}^\infty  \hat{f}(\xi) \, e^{2 \pi i \xi x} \,d\xi
$$

And this is part of my nurse rostering model:
$$
\sum_{b,s,d,w} \; \left( g_{bsdw} S^{+}_{bsdw} \; + h_{bsdw} S^{-}_{bsdw} \right) \;\; 
+ \sum_{n,w, p \in P(n,w)} \!\! c_{n} x_{npw} 
$$

such that
$$
\sum_{n,p} \: co_{sdp} \: x_{npw} \; + \; S^{+}_{bsdw} \; - \; S^{-}_{bsdw} \; = \; r_{bsdw}
\hspace{8ex} \forall \; b, s, d, w 
$$


