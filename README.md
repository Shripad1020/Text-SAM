## Getting Started

### Prerequisites

- Python 3.10 or higher

### Installation

#### Installing PyTorch Dependencies

Before installing `lang-sam`, please install PyTorch using the following command:

```bash

pip install torch==2.4.1 torchvision==0.19.1 --extra-index-url https://download.pytorch.org/whl/cu124

```

```bash

pip install -U git+https://github.com/luca-medeiros/lang-segment-anything.git

```

### Usage

To run the gradio APP:

`python app.py`
And open `http://0.0.0.0:8000/gradio`
