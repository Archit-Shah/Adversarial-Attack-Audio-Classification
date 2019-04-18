# CS848---PyTorch

## Instructions for version control of large files
Since we need to deal with large files, we use `git-lfs` for their version control. Commands to use them are simple:

1. Download and install the [git-lfs](https://git-lfs.github.com/) extension (one-time)
2. Run `git lfs install` from this repo's root (one-time command)
3. Run `git lfs track "*.pt"` (one-time command)
4. Add the large file by `git add large_file.pt`, commit by `git commit -m "Add large_file through git lfs"`, and push by `git push`. This would automatically push the large files to Git LFS and normal files to the repo. When pulling using `git pull` it would automatically download the large files to your local system.
