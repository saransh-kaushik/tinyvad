### file strtucture

```
tinyvad/
├── tinyvad/                    # Python package
│   ├── __init__.py
│   ├── vad.py                  # Public VAD API
│   ├── audio.py                # Framing and preprocessing
│   ├── features.py             # Feature extraction
│   ├── baseline.py             # DSP baseline
│   ├── model.py                # Neural network architecture
│   ├── streaming.py             # Streaming inference
│   └── endpointing.py           # Speech start/end detection
│
├── training/
│   ├── prepare_data.py
│   ├── train.py
│   └── evaluate.py
│
├── models/
│   └── .gitkeep                # Trained model goes here later
│
├── packages/
│   └── node/                   # npm package
│       ├── src/
│       │   ├── index.ts
│       │   ├── vad.ts
│       │   └── audio.ts
│       ├── test/
│       ├── package.json
│       └── tsconfig.json
│
├── tests/                      # Python tests
│   ├── test_audio.py
│   ├── test_baseline.py
│   └── test_vad.py
│
├── benchmarks/
│   └── benchmark.py
│
├── examples/
│   ├── python_file.py
│   └── python_microphone.py
│
├── pyproject.toml              # Python package configuration
├── requirements-dev.txt
├── .gitignore
├── LICENSE
└── README.md
```
