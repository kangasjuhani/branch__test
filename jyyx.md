git checkout -b fancy_new_feature
<br>
git add .
<br>
git commit -a -m "commit"
<br>
git push origin fancy_new_feature
<br>
git checkout -b bug_fixes_to_fancy_new_feature
<br>
git add .
<br>
git commit -a -m "commit"
<br>
git push origin bug_fixes_to_fancy_new_feature
<br>
git checkout develop
<br>
git checkout -b not_so_fancy_new_feature
<br>
git add .
<br>
git commit -a -m "commit"
<br>
git push origin not_so_fancy_new_feature
<br>
git checkout develop
<br>
git checkout -b cool_upcoming_feature
git add .
<br>
git commit -a -m "commit"
<br>
git push origin cool_upcoming_feature
<br>
git checkout develop
<br>
git checkout -b release_candidate
<br>
git add .
<br>
git commit -a -m "commit"
<br>
git push origin release_candidate
<br>
git merge fancy_new_feature
