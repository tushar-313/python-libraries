# Python Libraries — Notes 🐍

My personal notes and Jupyter notebooks from the **[Python Libraries Playlist](https://www.youtube.com/playlist?list=PL9n0l8rSshSnragNblKDBsT8Xu3otp3jA)** on YouTube.

Each folder covers one library, with hands-on notebooks and the datasets used along the way.

## 🗂️ What's Inside

```
.
├── numpy/
│   └── numpy.ipynb
├── pandas/
│   ├── Datasets/
│   ├── PART 1.ipynb
│   ├── PART 2.ipynb
│   ├── ...
│   └── PART 10.ipynb
├── matplotlib/
│   ├── LINE PLOT.ipynb
│   ├── BAR PLOT.ipynb
│   ├── HIST PLOT.ipynb
│   ├── PIE PLOT.ipynb
│   ├── SCATTER PLOT.ipynb
│   ├── SUBPLOT.ipynb
│   ├── IMSHOW.ipynb
│   ├── IRIS.csv
│   └── SUPERMARKET.csv
└── seaborn/
    ├── Seaborn.ipynb
    └── hr_data.csv
```

## 📌 Libraries Covered

| Library | Notebooks | Status |
|---|---|---|
| [NumPy](./numpy) | `numpy.ipynb` | ✅ |
| [Pandas](./pandas) | `PART 1` → `PART 10` (10 notebooks) + `Datasets/` | ✅ |
| [Matplotlib](./matplotlib) | Line, Bar, Hist, Pie, Scatter, Subplot, Imshow plots | ✅ |
| [Seaborn](./seaborn) | `Seaborn.ipynb` | ✅ |

> More folders will be added here as I move further through the playlist.

## 🚀 Running the Notebooks

Clone the repo:

```bash
git clone https://github.com/tushar-313/python-libraries.git
cd python-libraries
```

Set up a virtual environment and install the libraries you need (NumPy, Pandas, Matplotlib, Seaborn, Jupyter):

```bash
python -m venv .venv
source .venv/bin/activate   # on Windows: .venv\Scripts\activate
pip install numpy pandas matplotlib seaborn jupyter
```

Then launch Jupyter and open any notebook:

```bash
jupyter notebook
```

## 🎥 Source

Notes and code are based on this playlist:
👉 [Python Libraries Playlist – YouTube](https://www.youtube.com/playlist?list=PL9n0l8rSshSnragNblKDBsT8Xu3otp3jA)

All credit for the teaching content goes to the original creator — this repo just holds my practice notebooks and notes while following along.

## 📝 License

Notes and code here are shared for learning purposes. Feel free to reference them, though the datasets (`IRIS.csv`, `SUPERMARKET.csv`, `hr_data.csv`, etc.) belong to their original sources.