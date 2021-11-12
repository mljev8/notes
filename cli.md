# conda
conda env create -f requirements.yml -p ./envs [--offline --insecure]
conda develop path-to-folder

# git
git config --get remote.origin.url  
git remote add origin git@github.com:username/reponame.git  
git push --set-upstream origin master  
curl -u 'USER' https://api.github.com/user/repos -d '{"name":"REPO"}'

# cython
cythonize source_file.pyx -i