# pytorch-learning

A hands-on PyTorch tutorial, built around
[microgpt-fast](https://github.com/RaghuvirSingh23/microgpt-fast): it starts at
"what is a tensor" and ends with microgpt rebuilt in PyTorch, with batched
training, a KV cache, sampling, and profiling.

It's a static site with no build step. Open `index.html` in a browser:

```bash
open index.html        # macOS
xdg-open index.html    # Linux
```

```
pytorch-learning/
├── index.html                      # overview + table of contents
├── exercises.html                  # every exercise, by chapter and difficulty
├── assets/
│   ├── style.css
│   └── site.js                     # nav, copy buttons, progress, highlighting
└── chapters/
    ├── 01-why-pytorch.html
    ├── 02-tensors.html
    ├── 03-tensor-math.html
    ├── 04-autograd.html
    ├── 05-nn-module.html
    ├── 06-transformer-blocks.html
    ├── 07-losses-optimizers.html
    ├── 08-training-loop.html
    ├── 09-devices-precision.html
    ├── 10-inference.html
    ├── 11-performance.html
    ├── 12-debugging.html
    ├── 13-50-questions.html
    └── 14-capstone.html
```

The code examples were run against PyTorch 2.8.0 on CPU. GPU-only parts
(CUDA timing, TF32, `GradScaler`) are marked as such.
