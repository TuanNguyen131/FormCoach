# Cấu trúc thư mục dự án FormCoach

```
FormCoach/
├── .gitignore
├── README.md
├── requirements.txt
├── configs/
│   ├── data.yaml
│   ├── method_a.yaml
│   └── method_b.yaml
├── data/
│   ├── keypoints/
│   │   └── .gitkeep
│   ├── raw/
│   │   └── .gitkeep
│   ├── splits/
│   │   └── .gitkeep
│   └── webcam/
│       └── .gitkeep
├── docs/
│   ├── directory_structure.md
│   ├── experiments.md
│   └── plan.md
├── notebooks/
│   ├── 01_eda.ipynb
│   └── 02_error_analysis.ipynb
├── outputs/
│   ├── checkpoints/
│   │   └── .gitkeep
│   ├── logs/
│   │   └── .gitkeep
│   └── results/
│       └── .gitkeep
├── report/
│   └── .gitkeep
├── app/
│   ├── main.py
│   ├── messages_vi.yaml
│   └── ui.py
├── scripts/
│   ├── benchmark_fps.py
│   ├── download_data.py
│   ├── eval.py
│   ├── extract_keypoints.py
│   └── train_b.py
├── src/
│   ├── __init__.py
│   ├── data/
│   │   ├── __init__.py
│   │   └── dataset.py
│   ├── evaluation/
│   │   ├── __init__.py
│   │   └── metrics.py
│   ├── features/
│   │   ├── __init__.py
│   │   └── angles.py
│   ├── method_a/
│   │   ├── __init__.py
│   │   └── rules.py
│   ├── method_b/
│   │   ├── __init__.py
│   │   ├── models.py
│   │   └── train.py
│   ├── pose/
│   │   ├── __init__.py
│   │   └── extractor.py
│   ├── preprocessing/
│   │   ├── __init__.py
│   │   ├── normalize.py
│   │   └── smoothing.py
│   └── realtime/
│       ├── __init__.py
│       ├── inference.py
│       └── rep_counter.py
└── tests/
    ├── .gitkeep
    └── test_placeholder.py
```
