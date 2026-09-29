# Negating-Machine
A machine that negates.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: Negate that, machine." \
  | uvx negating-machine \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install negating-machine
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
negating-machine -a multilogue.txt
```
Or:
```bash
negating-machine multilogue.txt > response.txt
```
Or:
```bash
negating-machine -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import negating_machine
```
