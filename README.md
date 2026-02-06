


# Working Log
## 2/6
Install official TabPFN codebase
https://github.com/PriorLabs/TabPFN?tab=readme-ov-file
The environment was installed by uv:
```bash
# Install UV
curl -LsSf https://astral.sh/uv/install.sh | sh
# Install TabPFN
git clone https://github.com/PriorLabs/TabPFN.git --depth 1
cd TabPFN
uv sync
# Remove Git role for TabPFN
rm -rf .git
```