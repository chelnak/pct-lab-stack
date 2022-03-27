# pct-lab-stack

A template for use with the lab stack provisioner.

## Usage

```bash
# Override the owner setting in the template
echo "lab-stack:\n  owner: <YOUR NAME/USER>" > pct.yml

# Install the template
pct install --git-uri https://github.com/chelnak/pct-lab-stack

# Create a new stack 
pct new chelnak/lab-stack --name pe_windows_2019

# Initialise
cd pe_windows_2019
bolt module install --no-resolve
```
