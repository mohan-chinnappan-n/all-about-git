# Creation

```
ls -l
total 16
-rw-r--r--  1 mchinnappan  staff  65 Apr 22 07:45 app.js
-rw-r--r--  1 mchinnappan  staff  76 Apr 22 07:44 util.js

```

```
ls -a
```
```
.	..	app.js	util.js
```

```
git init .
```

```
tree .git
```

```
.git
├── HEAD
├── config
├── description
├── hooks
│   ├── applypatch-msg.sample
│   ├── commit-msg.sample
│   ├── fsmonitor-watchman.sample
│   ├── post-update.sample
│   ├── pre-applypatch.sample
│   ├── pre-commit.sample
│   ├── pre-merge-commit.sample
│   ├── pre-push.sample
│   ├── pre-rebase.sample
│   ├── pre-receive.sample
│   ├── prepare-commit-msg.sample
│   ├── push-to-checkout.sample
│   └── update.sample
├── info
│   └── exclude
├── objects
│   ├── info
│   └── pack
└── refs
    ├── heads
    └── tags

8 directories, 17 files
```

```
git branch -M develop
git add -A
git commit -m init
```
```
[develop (root-commit) 5bdc9b3] init
 2 files changed, 10 insertions(+)
 create mode 100644 app.js
 create mode 100644 util.js

```

```
git branch
```

```
* develop
```

```
ls -a
```
```
.	..	.git	app.js	util.js
```

```
tree .git  
.git
├── COMMIT_EDITMSG
├── HEAD
├── config
├── description
├── hooks
│   ├── applypatch-msg.sample
│   ├── commit-msg.sample
│   ├── fsmonitor-watchman.sample
│   ├── post-update.sample
│   ├── pre-applypatch.sample
│   ├── pre-commit.sample
│   ├── pre-merge-commit.sample
│   ├── pre-push.sample
│   ├── pre-rebase.sample
│   ├── pre-receive.sample
│   ├── prepare-commit-msg.sample
│   ├── push-to-checkout.sample
│   └── update.sample
├── index
├── info
│   └── exclude
├── logs
│   ├── HEAD
│   └── refs
│       └── heads
│           └── develop
├── objects
│   ├── 37
│   │   └── 4caab8034b72bb049462e8e30673af461e1fd0
│   ├── 44
│   │   └── 88afa3a0d346373865700b12308ef1b5195bcb
│   ├── 5b
│   │   └── dc9b3b6609e3c66e5fc9b21a735a3833c20b97
│   ├── e6
│   │   └── 2d1d01eefdbd89235df893448ada7f4c1ae890
│   ├── info
│   └── pack
└── refs
    ├── heads
    │   └── develop
    └── tags

15 directories, 26 files
```