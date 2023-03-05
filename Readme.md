# **04.GitOps**

## **YAML** ##

```bash
Current runner version: '2.302.1'
Operating System
Runner Image
Runner Image Provisioner
GITHUB_TOKEN Permissions
Secret source: Actions
Prepare workflow directory
Prepare all required actions
Getting action download info
Download action repository 'actions/checkout@v2' (SHA:dc323e67f16fb5f7663d20ff7941f27f5809e9b6)
Complete job name: tab-finder
3s
Run actions/checkout@v2
Syncing repository: sorokatyie/04.GitOps
Getting Git version info
  Working directory is '/home/runner/work/04.GitOps/04.GitOps'
  /usr/bin/git version
  git version 2.39.2
Temporarily overriding HOME='/home/runner/work/_temp/263cdee8-a165-4921-a03f-4bd6f2bf61bb' before making global git config changes
Adding repository directory to the temporary git global config as a safe directory
/usr/bin/git config --global --add safe.directory /home/runner/work/04.GitOps/04.GitOps
Deleting the contents of '/home/runner/work/04.GitOps/04.GitOps'
Initializing the repository
Disabling automatic garbage collection
Setting up auth
Fetching the repository
Determining the checkout info
Checking out the ref
/usr/bin/git log -1 --format='%H'
'c7aac9f47fc85187316c7bcec5631f3c5a63f9c7'
0s
Run TOTAL_TABS=0
fatal: ambiguous argument 'HEAD~1': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'
Found 0 tabs in total
0s
Run echo ::set-output name=tabcount::$TOTAL_TABS
Warning: The `set-output` command is deprecated and will be disabled soon. Please upgrade to using Environment Files. For more information see: https://github.blog/changelog/2022-10-11-github-actions-deprecating-save-state-and-set-output-commands/
0s
0s
Cleaning up orphan processes

```