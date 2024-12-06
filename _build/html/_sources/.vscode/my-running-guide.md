# to update the book - 

cd /home/breezy/Documents/GitHub/Jupyter-Books

jupyter-book build quantum-cryptography-guide

or rebuild with

jupyter-book build --all quantum-cryptography-guide

# to push the book to GitHub Pages -

cd /home/breezy/Documents/GitHub/Jupyter-Books/quantum-cryptography-guide

make sure in main - 

ghp-import -n -p -f _build/html