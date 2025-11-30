# 1. create local folder
mkdir invoice-processing-solution-yourname
cd invoice-processing-solution-yourname

# 2. create README.md and CLIENT_INVOICE_SOLUTION.md by pasting contents into files
# (use your editor: nano/vim/code, or echo >> files)

# 3. init git and push to new GitHub repo
git init
git add README.md CLIENT_INVOICE_SOLUTION.md
git commit -m "Initial docs: README + client solution"
# create remote on GitHub first (or use GitHub CLI: gh repo create)
git remote add origin https://github.com/<your-username>/invoice-processing-solution-yourname.git
git branch -M main
git push -u origin main

