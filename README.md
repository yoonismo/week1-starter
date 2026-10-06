# Week 1 starter

Practice repository for **Week 1: Tools of Reproducible Work**.
Full instructions: <https://yoonismo.github.io/causal-computing/week1.html>

## What is in here

| File | Purpose |
|---|---|
| `week1.ipynb` | A notebook with two planted bugs |
| `requirements.txt` | The packages the automatic check installs |
| `.github/workflows/ci.yml` | The automatic check: runs the notebook on GitHub's computer after every push |

## Labs

1. **Planted bugs.** Run `week1.ipynb` in order and answer the questions in it.
2. **Fix, commit, push.** Replace the one-point check with a check on many points, fix `squared`, clear all outputs, then `git add`, `git commit`, `git push`. Watch the **Actions** tab turn green.
3. **A deliberate red X.** Install `pandas` only on your own computer and add `import pandas as pd` to the first code cell. Push, watch the check fail, read the log, then add `pandas` to `requirements.txt` and push again.
4. **Pull.** Add your name below on the GitHub website, then run `git pull` on your computer.

## Name

(write your name here in Lab 4)
