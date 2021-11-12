# conda
conda env create -f requirements.yml -p ./envs [--offline --insecure]
conda develop path-to-folder

# git
git config --get remote.origin.url
git remote add origin https://github.com/project-user-name/repo.git
git push --set-upstream origin master

# cython
cythonize source_file.pyx -i