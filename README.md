# Introduction

Simple script to turn on qubole clusters

## Usage

To access qubole's API, you'll have to obtain an API key

```bash
export QUBOLE_TOKEN=<API KEY>
```

* To get the status of cluster

  ```bash
  qubole state --cluster USERNAME
  ```

* Toggle cluster between `UP` and `DOWN` state

  ```
  qubole toggle --cluster USERNAME
  ```

## Installation

```
pip install pyqubole
```
