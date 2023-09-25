# Abdullah Alkhodiri 2135170

# git-it-assingment

1. Get git
"""
git --version
git config --global user.name "Abdullah Alkhodiri"
git config --global user.email "abudllahkhodiri@gmail.com"

"""
2. Repository
"""
mkdir hello-world
cd hello-world
git init

"""

3. Commit To It
"""
git status
git add readme.txt
git commit -m "Created readme"
git diff

"""

4. GitHubbin
"""
git config --global user.username "AbdullahAlkhodiri"
git config --global user.username

"""

5. Remote Control
"""
git remote set-url origin "https://github.com/AbdullahAlkhodiri/hello-world"
git push origin main

"""

6. Forks And Clones
"""
cd ..
git clone "https://github.com/AbdullahAlkhodiri/patchwork"
cd patchwork
git remote -v
git remote add upstream https://github.com/jlord/patchwork.git
git remote -v

"""
7. Branches Aren't Just For Birds
"""
git status
git branch "add-AbdullahAlkhodiri"
git checkout "add-AbdullahAlkhodiri"
git status
git add <contributors/add-AbdullahAlkhodiri>
git commit -m "commit message"
git push origin <add-AbdullahAlkhodiri>

"""

8. It's A Small World
"""
https://github.com/AbdullahAlkhodiri/patchwork/settings/access?query=filter%3Acollaborators 

"""

9. Pull Never Out Of Date
"""
git pull origin "add-AbdullahAlkhodiri"

"""

10. Requesting You Pull Please
"""
https://github.com/jlord/patchwork/pull/50061

"""

11. Requesting You Pull Please
"""
git checkout gh-pages
git merge "add-AbdullahAlkhodiri"
git branch -d "add-AbdullahAlkhodiri"
git pull upstream gh-pages

"""
![](./Screenshot%20git%20it.png)
![](./Screenshot%202%20git%20it%20.png)