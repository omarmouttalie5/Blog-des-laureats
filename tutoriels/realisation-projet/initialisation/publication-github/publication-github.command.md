mkdir -p tutoriels/realisation-projet/initialisation/publication-github
cat << 'EOF' > tutoriels/realisation-projet/initialisation/publication-github/publication-github.command.md
gh auth status
mkdir blog-des-laureats
cd blog-des-laureats
echo "" > .gitignore
git init
git checkout -b sprint1
gh repo create
EOF