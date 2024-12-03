This is a simple script to create a pretraining dataset from a folder of input files (`txt`, `md`, `pdf`, `docx`, `epub`, `html"`)

```bash
git clone https://github.com/agi-dude/pretraining-generator
cd pretraining-generator
pip install -r requirements.txt

python main.py <input_folder> pretraining.jsonl
```