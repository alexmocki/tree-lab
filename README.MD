# OSINT Recon Tool

This is a simple Open Source Intelligence (OSINT) reconnaissance tool written in Python.  
It scans a list of domains and gathers basic information such as IP addresses and WHOIS records.

## 📁 Project Structure

```
tree-lab/
├── data/
│   └── targets.txt                # List of target domains
├── src/
│   ├── recon.py                   # Main scanning logic
│   └── utils.py                   # Utility functions
├── reports/
│   ├── example.com.json           # Report for each domain
│   └── summary.json               # Aggregated report
├── requirements.txt               # Python dependencies
├── README.md                      # Project documentation
└── LICENSE                        # License file (MIT)
```

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/alexmocki/tree-lab.git
cd tree-lab
pip install -r requirements.txt
```

## ▶️ Usage

Run the tool using:

```bash
python src/recon.py
```

It will read targets from `data/targets.txt` and generate JSON reports in the `reports/` folder.

## 📦 Output

- Individual reports per domain (e.g., `reports/github.com.json`)
- Summary file with timestamps (`summary.json`)

## 🔐 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

## 👩‍💻 Authors

- [@alexmocki](https://github.com/alexmocki)
