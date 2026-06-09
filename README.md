# homelab


# Commands

## Force reconcile flux (instead of waiting period)
flux reconcile kustomization flux-system --with-source

## Print all file names and theirs contents in current directory
awk 'FNR==1 {print "\n=== " FILENAME " ==="} {print}' *