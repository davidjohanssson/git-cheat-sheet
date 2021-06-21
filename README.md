<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><h1 id="git-cheat-sheet">Git Cheat Sheet</h1>
<h2 id="branches">Branches</h2>
<p><strong>Create branch</strong><br>
git branch feature-1</p>
<p><strong>Go to branch</strong><br>
git checkout feature-1</p>
<p><strong>Merge feature-1 to master</strong><br>
git checkout master<br>
git pull origin master<br>
git merge feature-1<br>
git push origin master</p>
<p><strong>Remove local branch</strong><br>
git branch -D feature-1</p>
<p><strong>Remove remote branch</strong><br>
git push origin --delete feature-1</p>
<h2 id="changes">Changes</h2>
<p><strong>Undo changes (not commited)</strong><br>
git stash</p>
<p><strong>Undo changes (commited)</strong><br>
git reflog<br>
<em>Note down the ID of the commit we want to go back to, e.g. 6b6271a</em><br>
git reset --hard <em>6b6271a</em></p>
</div>
</body>

</html>
