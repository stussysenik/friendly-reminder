# friendly-reminder
💙for your eyes only

CURATED ART DESSERT iDEAS YOU'D LIKE TO PRESERVE, PASS ON, CHERISH.

1. Jorja Smith - Blue Lights
https://youtu.be/fYwRsJAPfec?si=OUui44bkbJJfbTd9

2. Ira Glass - Creativity
3. Do what you can't - Casey Neistat

## Git Branch Management Lessons
1. When branches have different commit histories, use `--allow-unrelated-histories` to merge them
2. Always check branch relationships using `git log` and `git show-branch` before merging
3. Be careful with force pushes (`git push -f`) - only use when necessary and understand the implications
4. When updating branch content:
   - To make branch A match B: use `git reset --hard branchB` while on branchA
   - Always verify the direction of changes before force pushing
5. Keep `.gitignore` rules consistent across branches to avoid tracking/untracking issues
