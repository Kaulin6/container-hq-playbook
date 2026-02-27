Read build-brief.md in this directory. Build the visual explainer page exactly as described.

Output: a single index.html file in this directory.

After building:
1. git add index.html && git commit -m "feat: Container HQ cold email playbook visual explainer" && git push -u origin main
2. Enable GitHub Pages: gh api repos/Kaulin6/container-hq-playbook/pages --method POST -f source[branch]=main -f source[path]=/
3. Wait 15 seconds
4. Print the GitHub Pages URL: https://kaulin6.github.io/container-hq-playbook/
5. Report done.
