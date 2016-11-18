# accurev-git-migrate

**A Python 2.7 script which automatically migrates stream history from AccuRev into a TFS branch, given the destination is already under a tfs workspace.**

### Usage instructions:

To start the script simply run

`python migrate.py accurevBranch accurevStream repoLocation`

Note: repolocation should already be under a tfs workspace

The script will then get the AccuRev branch history and transition it into the specified tfs workspace.

The arguments the script uses are as follows, also displayed by running `python migrate.py -h`:

|         Argument           |                          Description                            |
| ---------------------------|-----------------------------------------------------------------|
| accurevBranch              |            name of AccuRev branch to be transitioned            |
| accurevStream              |            name of AccuRev stream to be transitioned            |
| repoLocation               |            path to folder in which to transition                |