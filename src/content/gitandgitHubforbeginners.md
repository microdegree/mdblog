---
title: 'ಬಿಗಿನರ್ಸ್‌ಗಾಗಿ-ಗಿಟ್-ಮತ್ತು-ಗಿಟ್‌ಹಬ್‌ನ-ಒಂದು-ಪರಿಚಯ'
author: [Ghost]
tags: []
image: img/marvin-meyer-794521-unsplash.jpg
date: '2020-11-03T10:00:00.000Z'
draft: false
---




# **ಬಿಗಿನರ್ಸ್‌ಗಾಗಿ ಗಿಟ್ ಮತ್ತು**  **ಗಿಟ್‌ಹಬ್‌ನ**  /**ಒಂದು ಪರಿಚಯ**

[![Akshaamin](https://miro.medium.com/fit/c/96/96/1*YnJXah645uKePPO_bC_DCA.jpeg)](https://medium.com/@akshaamin2097?source=post_page-----3c09b72cdad6--------------------------------)

[Akshaamin](https://medium.com/@akshaamin2097?source=post_page-----3c09b72cdad6--------------------------------)

Follow

[Nov 5](https://medium.com/microdegree/%E0%B2%AC%E0%B2%BF%E0%B2%97%E0%B2%BF%E0%B2%A8%E0%B2%B0%E0%B3%8D%E0%B2%B8%E0%B3%8D-%E0%B2%97%E0%B2%BE%E0%B2%97%E0%B2%BF-%E0%B2%97%E0%B2%BF%E0%B2%9F%E0%B3%8D-%E0%B2%AE%E0%B2%A4%E0%B3%8D%E0%B2%A4%E0%B3%81-%E0%B2%97%E0%B2%BF%E0%B2%9F%E0%B3%8D-%E0%B2%B9%E0%B2%AC%E0%B3%8D-%E0%B2%A8-%E0%B2%92%E0%B2%82%E0%B2%A6%E0%B3%81-%E0%B2%AA%E0%B2%B0%E0%B2%BF%E0%B2%9A%E0%B2%AF-3c09b72cdad6?source=post_page-----3c09b72cdad6--------------------------------)  ·  10  min read

**ಗಿಟ್‌ಹಬ್**  **ಎಂದರೇನು?**

GitHub Version control ಮತ್ತು ಸಹಯೋಗಕ್ಕಾಗಿ ಕೋಡ್ ಹೋಸ್ಟಿಂಗ್ ವೇದಿಕೆಯಾಗಿದೆ. ಇದು ನಿಮಗೆ ಮತ್ತು ಇತರರಿಗೆ ಎಲ್ಲಿಂದಲಾದರೂ ಯೋಜನೆಗಳಲ್ಲಿ ಒಟ್ಟಾಗಿ ಕೆಲಸ ಮಾಡಲು ಅನುವು ಮಾಡಿಕೊಡುತ್ತದೆ.

ಈ blog ನಿಮಗೆ Repositoryಗಳು, Branches, Commites ಮತ್ತು Pull Requestಗಳಂತಹ ಗಿಟ್‌ಹಬ್ essentialಗಳನ್ನು ಕಲಿಸುತ್ತದೆ. ನಿಮ್ಮ ಸ್ವಂತ ‘‘Hello World’’ repositoryಯನ್ನು ನೀವು ರಚಿಸುತ್ತೀರಿ ಮತ್ತು ಕೋಡ್ ರಚಿಸಲು ಮತ್ತು ವಿಮರ್ಶಿಸಲು ಜನಪ್ರಿಯ ಮಾರ್ಗವಾದ ಗಿಟ್‌ಹಬ್‌ನ Pull Request Workflow ಅನ್ನು ಕಲಿಯುತ್ತೀರಿ.

![Image for post](https://miro.medium.com/max/60/1*2hWfwgI2WwfkkD4QNdUpbQ.jpeg?q=20)

![Image for post](https://miro.medium.com/max/4999/1*2hWfwgI2WwfkkD4QNdUpbQ.jpeg)

Photo by  [Markus Winkler](https://unsplash.com/@markuswinkler?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)  on  [Unsplash](https://unsplash.com/s/photos/github?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

**ಹಂತ 0.**  **Git ಅನ್ನು Install ಮತ್ತು GitHub account ರಚಿಸಿ**

ನೀವು ಮಾಡಲು ಬಯಸುವ ಮೊದಲ ಎರಡು ವಿಷಯಗಳು Git ಅನ್ನು Install ಮತ್ತು ಉಚಿತ GitHub account ರಚಿಸಿ.

Git ಅನ್ನು ಸ್ಥಾಪಿಸಲು/install ಇಲ್ಲಿ ಸೂಚನೆಗಳನ್ನು ಅನುಸರಿಸಿ (ಅದನ್ನು ಈಗಾಗಲೇ ಸ್ಥಾಪಿಸದಿದ್ದರೆ). ಈ ಟ್ಯುಟೋರಿಯಲ್ ಗಾಗಿ ನಾವು Command Lineನಲ್ಲಿ ಮಾತ್ರ Git ಅನ್ನು ಬಳಸುತ್ತೇವೆ ಎಂಬುದನ್ನು ಗಮನಿಸಿ. ಕೆಲವು ಉತ್ತಮವಾದ Git GUI(ಗ್ರಾಫಿಕಲ್ ಯೂಸರ್ ಇಂಟರ್ಫೇಸ್ಗಳು) ಇದ್ದರೂ, ಮೊದಲು Git-ನಿರ್ದಿಷ್ಟ Command ಗಳನ್ನು ಬಳಸಿಕೊಂಡು Git ಕಲಿಯುವುದು ಸುಲಭ ಎಂದು ನಾನು ಭಾವಿಸುತ್ತೇನೆ ಮತ್ತು ನಂತರ ನೀವು commandಯೊಂದಿಗೆ ಹೆಚ್ಚು ಆರಾಮದಾಯಕವಾದ ನಂತರ Git GUI ಅನ್ನು ಪ್ರಯತ್ನಿಸಿ.

ನೀವು ಅದನ್ನು ಮಾಡಿದ ನಂತರ, ಇಲ್ಲಿ GitHub accountನ್ನು ರಚಿಸಿ. (Public ರೆಪೊಸಿಟರಿಗಳಿಗೆ accounts ಉಚಿತ, ಆದರೆ Private ರೆಪೊಸಿಟರಿಗಳಿಗೆ ಶುಲ್ಕವಿದೆ.)

**ಹಂತ 1. Repository ರಚಿಸಿ**

ಒಂದೇ Planಅನ್ನು organize ರೆಪೊಸಿಟರಿಯನ್ನು ಸಾಮಾನ್ಯವಾಗಿ ಬಳಸಲಾಗುತ್ತದೆ. ರೆಪೊಸಿಟರಿಗಳು ಫೋಲ್ಡರ್‌ಗಳು ಮತ್ತು ಫೈಲ್‌ಗಳು, pictures, videos, spreadsheet ಮತ್ತು datasetಗಳನ್ನು ಒಳಗೊಂಡಿರಬಹುದು — ನಿಮ್ಮ ಯೋಜನೆಗೆ ಏನು ಬೇಕಾದರೂ. README, ಅಥವಾ ನಿಮ್ಮ ಪ್ರಾಜೆಕ್ಟ್ ಬಗ್ಗೆ ಮಾಹಿತಿಯೊಂದಿಗೆ ಫೈಲ್ ಅನ್ನು ಸೇರಿಸಲು ನಾವು ಶಿಫಾರಸು ಮಾಡುತ್ತೇವೆ. ನಿಮ್ಮ New repositoryನ್ನು ನೀವು ರಚಿಸುವ ಸಮಯದಲ್ಲಿ ಒಂದನ್ನು ಸೇರಿಸಲು GitHub ಸುಲಭಗೊಳಿಸುತ್ತದೆ. ಇದು License ಆಗಿ ಫೈಲ್‌ನಂತಹ ಇತರ ಸಾಮಾನ್ಯ ಆಯ್ಕೆಗಳನ್ನು ಸಹ ನೀಡುತ್ತದೆ.

ನಿಮ್ಮ Hello World ರೆಪೊಸಿಟರಿಯು ನೀವು Thinking, Resourceಗಳನ್ನು ಸಂಗ್ರಹಿಸುವ ಸ್ಥಳವಾಗಬಹುದು ಅಥವಾ ಇತರರೊಂದಿಗೆ ವಿಷಯಗಳನ್ನು ಹಂಚಿಕೊಳ್ಳಬಹುದು ಮತ್ತು ಚರ್ಚಿಸಬಹುದು.

**ಹೊಸ ರೆಪೊಸಿಟರಿನ್ನು ರಚಿಸಲು**

1.  ಮೇಲಿನ ಬಲ Cornerಲ್ಲಿ, ನಿಮ್ಮ Avatar ಅಥವಾ Identification ಪಕ್ಕದಲ್ಲಿ, ಕ್ಲಿಕ್ ಮಾಡಿ ಮತ್ತು ನಂತರ new ರೆಪೊಸಿಟರಿಯನ್ನು ಆರಿಸಿ.
2.  ನಿಮ್ಮ ರೆಪೊಸಿಟರಿ hello world ಅನ್ನು ಹೆಸರಿಸಿ.
3.  ಸಣ್ಣ ವಿವರಣೆಯನ್ನು ಬರೆಯಿರಿ.
4.  README ನೊಂದಿಗೆ ಈ ರೆಪೊಸಿಟರಿಯನ್ನು ಪ್ರಾರಂಭಿಸಿ ಆಯ್ಕೆಮಾಡಿ.

![Image for post](https://miro.medium.com/max/60/1*fJS6nxhmC7Syt4MH7lrQxQ.png?q=20)

![Image for post](https://miro.medium.com/max/2044/1*fJS6nxhmC7Syt4MH7lrQxQ.png)

Git ಬಳಸಲು ನಾವು terminal ಅನ್ನು ಬಳಸುತ್ತೇವೆ. ಪ್ರಾರಂಭಿಸಲು, terminal ಅನ್ನು open ಮತ್ತು CD (ಡೈರೆಕ್ಟರಿಯನ್ನು ಬದಲಾಯಿಸಿ) Commandನ್ನು ಬಳಸಿಕೊಂಡು ನಿಮ್ಮ Local machineಲ್ಲಿ planನ್ನು ಇರಿಸಲು ಬಯಸುವ ಸ್ಥಳಕ್ಕೆ ತೆರಳಿ. ಉದಾಹರಣೆಗೆ, ನಿಮ್ಮ desktopನಲ್ಲಿ ನೀವು ‘Projects’ folder ಹೊಂದಿದ್ದರೆ, ನೀವು ಈ ರೀತಿ ಏನಾದರೂ ಮಾಡುತ್ತೀರಿ:

mnelson:Desktop mnelson$ cd ~/Desktop

mnelson:Desktop mnelson$ mkdir myproject

mnelson:Desktop mnelson$ cd myproject/

Folder ಮೂಲದಲ್ಲಿ Git ರೆಪೊಸಿಟರಿಯನ್ನು ಪ್ರಾರಂಭಿಸಲು,  **git init**  commandನ್ನು Run ಮಾಡಿ:

mnelson:myproject mnelson$ git init

Initialized empty Git repository in/Users/mnelson/Desktop/myproject/.git/

**ಹಂತ 2: Repoಗೆ**  **new**  **ಫೈಲ್**  **ಅನ್ನು**  **ಸೇರಿಸಿ**

ನೀವು ಇಷ್ಟಪಡುವ ಯಾವುದೇ Text editorನ್ನು ಬಳಸಿ ಅಥವಾ Touch commandಯನ್ನು run ಮಾಡಿ ,planಗೆ new ಫೈಲ್ ಅನ್ನು ಸೇರಿಸಿ.

ಒಮ್ಮೆ ನೀವು Git repo ಹೊಂದಿರುವ ಫೋಲ್ಡರ್‌ನಲ್ಲಿ ಫೈಲ್‌ಗಳನ್ನು ಸೇರಿಸಿದ ಅಥವಾ ಮಾರ್ಪಡಿಸಿದ ನಂತರ, repo ಒಳಗೆ ಬದಲಾವಣೆಗಳನ್ನು ಮಾಡಲಾಗಿದೆ ಎಂದು Git ಗಮನಿಸುತ್ತದೆ. ಆದರೆ, ನೀವು ಅದನ್ನು Clear ಆಗಿ ಹೇಳದ ಹೊರತು Git Official ಆಗಿ ಫೈಲ್ ಅನ್ನು track ಮಾಡುವುದಿಲ್ಲ (ಅಂದರೆ, ಅದನ್ನು Abideಗಿ ಇರಿಸಿ — ಮುಂದಿನ Commitಗಳ ಬಗ್ಗೆ ನಾವು ಹೆಚ್ಚು ಮಾತನಾಡುತ್ತೇವೆ).

mnelson: myproject mnelson $ touch mnelson.txt

mnelson: myproject mnelson $ ls

mnelson.txt

GitHub ನೊಂದಿಗೆ host ಮಾಡಲಾದ rawaddfile.md ವೀಕ್ಷಿಸಿ

ಹೊಸ ಫೈಲ್ ಅನ್ನು ರಚಿಸಿದ ನಂತರ, ಯಾವ ಫೈಲ್‌ಗಳು Existenceಲ್ಲಿವೆ ಎಂದು ತಿಳಿಯಲು ನೀವು Git status commandನ್ನು ಬಳಸಬಹುದು.

mnelson:myproject mnelson $ git status

On branch master

Initial commit

Untracked files:

(use “git add <file>…” to include in what will be committed)

mnelson.txt

nothing added to commit but untracked files present (use “git add” to track)

ಇದು ಮೂಲತಃ ಹೇಳುವುದೇನೆಂದರೆ, “ಹೇ, ನೀವು mnelson.txt ಎಂಬ ಹೊಸ ಫೈಲ್ ಅನ್ನು ರಚಿಸಿರುವುದನ್ನು ನಾವು ಗಮನಿಸಿದ್ದೇವೆ, ಆದರೆ ನೀವು  **‘git add’**  command ನ್ನು ಬಳಸದ ಹೊರತು ನಾವು ಅದರೊಂದಿಗೆ ಏನನ್ನೂ ಮಾಡಲು ಹೋಗುವುದಿಲ್ಲ.”

An interval: Atmosphere of the stage, Committment ಮತ್ತು ನೀವು ಮೊದಲು Git ಕಲಿಯುತ್ತಿರುವಾಗ ಅತ್ಯಂತ ಗೊಂದಲಮಯವಾದ ಭಾಗವೆಂದರೆ platform environment concept ಮತ್ತು ಅದು commitment ಗೆ ಹೇಗೆ ಸಂಬಂಧಿಸಿದೆ.

Commit ಎನ್ನುವುದು ನೀವು ಕೊನೆಯ ಬಾರಿ commitment/ಬದ್ಧತೆಯನ್ನು ಮಾಡಿದ ನಂತರ ನೀವು ಯಾವ ಫೈಲ್‌ಗಳನ್ನು ಬದಲಾಯಿಸಿದ್ದೀರಿ ಎಂಬುದರ Documentationಗಿದೆ. Basically, ನಿಮ್ಮ repoದಲ್ಲಿ ನೀವು Changes ಮಾಡುತ್ತೀರಿ (ಉದಾಹರಣೆಗೆ, ಫೈಲ್ ಅನ್ನು ಸೇರಿಸುವುದು ಅಥವಾ ಒಂದನ್ನು ಮಾರ್ಪಡಿಸುವುದು) ಮತ್ತು ಆ ಫೈಲ್‌ಗಳನ್ನು commitment/ಬದ್ಧವಾಗಿಡಲು Gitಗೆ ಹೇಳಿ.

Commitಗಳು ನಿಮ್ಮ ಪ್ರಾಜೆಕ್ಟ್‌ನ essence ನ್ನು ರೂಪಿಸುತ್ತವೆ ಮತ್ತು ಯಾವುದೇ ಹಂತದಲ್ಲಿ plan/ಯೋಜನೆಯ ಸ್ಥಿತಿಗೆ ಹಿಂತಿರುಗಲು ನಿಮಗೆ ಅನುವು ಮಾಡಿಕೊಡುತ್ತದೆ.

ಆದ್ದರಿಂದ, ಯಾವ ಫೈಲ್‌ಗಳನ್ನು commitಗೆ ಹಾಕಬೇಕೆಂದು ನೀವು Gitಗೆ ಹೇಗೆ ಹೇಳುತ್ತೀರಿ? Staging environment ಅಥವಾ Index ಇಲ್ಲಿಗೆ ಬರುತ್ತದೆ. ಹಂತ 2 ರಲ್ಲಿ ನೋಡಿದಂತೆ, ನಿಮ್ಮ repoಗೆ ನೀವು ಬದಲಾವಣೆಗಳನ್ನು ಮಾಡಿದಾಗ, ಫೈಲ್ ಬದಲಾಗಿದೆ ಎಂದು Git ಗಮನಿಸುತ್ತದೆ ಆದರೆ ಅದರೊಂದಿಗೆ ಏನನ್ನೂ ಮಾಡುವುದಿಲ್ಲ (ಅದನ್ನು commitment/ಬದ್ಧತೆಯಲ್ಲಿ ಸೇರಿಸುವ ಹಾಗೆ).

Committment/ಬದ್ಧತೆಗೆ ಫೈಲ್ ಅನ್ನು ಸೇರಿಸಲು, ನೀವು ಮೊದಲು ಅದನ್ನು Staging environment ಸೇರಿಸಬೇಕಾಗುತ್ತದೆ. ಇದನ್ನು ಮಾಡಲು, ನೀವು  **git add <filename>**  comment ನ್ನು ಬಳಸಬಹುದು (ಕೆಳಗಿನ ಹಂತ 3 ನೋಡಿ).

Staging environment ಗೆ ನೀವು ಬಯಸುವ ಎಲ್ಲಾ ಫೈಲ್‌ಗಳನ್ನು ಸೇರಿಸಲು ನೀವು ಒಮ್ಮೆ The  **git add** commandನ್ನು ಬಳಸಿದರೆ, ನಂತರ ನೀವು ಅವುಗಳನ್ನು **Git commit**  commandನ್ನು ಬಳಸಿಕೊಂಡು commitment/ಬದ್ಧತೆಗೆ package ಮಾಡಲು Gitಗೆ ಹೇಳಬಹುದು.

**Note**: Staging environment ನ್ನು ‘Staging’ ಎಂದೂ ಕರೆಯಲಾಗುತ್ತದೆ, ಇದಕ್ಕಾಗಿ new preferred term ಆಗಿದೆ, ಆದರೆ ಇದನ್ನು ‘**index’**  ಎಂದು ಕರೆಯುವುದನ್ನು ಸಹ ನೀವು ನೋಡಬಹುದು.

**ಹಂತ 3: Stage Environment**ಗೆ  **ಫೈಲ್**  **ಸೇರಿಸಿ**

‘git add ‘commandನ್ನು ಬಳಸಿಕೊಂಡು staging environment ಫೈಲ್ ಅನ್ನು ಸೇರಿಸಿ.

ನೀವು Git Status commandನ್ನು Re-driving ಮಾಡಿದರೆ, git ಫೈಲ್ ಅನ್ನು staging environmentಗೆ ಸೇರಿಸಿದೆ ಎಂದು ನೀವು ನೋಡುತ್ತೀರಿ (“Changes to commitment” line ಗಮನಿಸಿ).

mnelson:myproject mnelson$ git status

On branch master

Initial commit

Changes to be committed:

(use “git rm — cached <file>…” to unstage)

new file: mnelson.txt

ಪುನರುಚ್ಚರಿಸಲು, ಫೈಲ್ ಅನ್ನು ಇನ್ನೂ commitment/ಬದ್ಧತೆಗೆ ಸೇರಿಸಲಾಗಿಲ್ಲ, ಆದರೆ ಅದು ಆಗಲಿದೆ.

**ಹಂತ 4: Commitment/ಬದ್ಧತೆಯನ್ನು**  **ರಚಿಸಿ**

ನಿಮ್ಮ ಮೊದಲ ಬದ್ಧತೆಯನ್ನು ರಚಿಸಲು ಇದು ಸಮಯ!

**git commit -m git commit -m “Your message about the commit”**

mnelson:myproject mnelson$ git commit -m “This is my first commit!”

[master (root-commit) b345d9a] This is my first commit!

1 file changed, 1 insertion(+)

create mode 100644 mnelson.txt

ಬದ್ಧತೆಯ ಕೊನೆಯಲ್ಲಿರುವ ಸಂದೇಶವು commitment/ಬದ್ಧತೆಯನ್ನು ಒಳಗೊಂಡಿರುವ ವಿಷಯಕ್ಕೆ ಸಂಬಂಧಿಸಿರಬೇಕು — ಬಹುಶಃ ಇದು New Feature,ಬಹುಶಃ ಇದು Bug fix, ಬಹುಶಃ ಇದು typoನ್ನು ಸರಿಪಡಿಸುವುದು. “Asdfadsf” ಅಥವಾ “foobar” ನಂತಹ ಹಾಕಬೇಡಿ. ಅದು ನಿಮ್ಮ commitment/ಬದ್ಧತೆಯನ್ನು ನೋಡುವ ಇತರ ಜನರನ್ನು Grief(ದುಃಖ)ಗೊಳಿಸುತ್ತದೆ.

**ಹಂತ 5: ಹೊಸ**  **ಶಾಖೆಯನ್ನು(branch)**  **ರಚಿಸಿ**

ಈಗ ನೀವು ಹೊಸ ಬದ್ಧತೆಯನ್ನು ಮಾಡಿದ್ದೀರಿ, ಸ್ವಲ್ಪ ಹೆಚ್ಚು ಸುಧಾರಿತವಾದದನ್ನು ಪ್ರಯತ್ನಿಸೋಣ.

ನೀವು new featuresನ್ನು ಮಾಡಲು ಬಯಸುತ್ತೀರಿ ಎಂದು ಹೇಳಿ ಆದರೆ featuresನ್ನು ಅಭಿವೃದ್ಧಿಪಡಿಸುವಾಗ ಮುಖ್ಯ ಯೋಜನೆಯಲ್ಲಿ ಬದಲಾವಣೆಗಳನ್ನು ಮಾಡುವ ಬಗ್ಗೆ ಚಿಂತಿತರಾಗಿರಿ. Git branchಗಳು ಇಲ್ಲಿಗೆ ಬರುತ್ತವೆ.

Plan/ಯೋಜನೆಯ ‘ states ‘ ನಡುವೆ Back ಮತ್ತು fornt ಚಲಿಸಲು branches ನಿಮಗೆ ಅವಕಾಶ ಮಾಡಿಕೊಡುತ್ತವೆ. ಉದಾಹರಣೆಗೆ, ನಿಮ್ಮ ವೆಬ್‌ಸೈಟ್‌ಗೆ new pageನ್ನು ಸೇರಿಸಲು ನೀವು ಬಯಸಿದರೆ ನೀವು ಯೋಜನೆಯ main partಗೆ Damageಯಾಗದಂತೆ ಆ ಪುಟಕ್ಕಾಗಿ new branchನ್ನು ರಚಿಸಬಹುದು. ನೀವು ಪುಟವನ್ನು Fulfill ಮಾಡಿದ ನಂತರ, ನಿಮ್ಮ branchಯಿಂದ ನಿಮ್ಮ Changesಗಳನ್ನು Primary Branchಗೆ ವಿಲೀನಗೊಳಿಸಬಹುದು. ನೀವು new branchನ್ನು ರಚಿಸಿದಾಗ, ನಿಮ್ಮ branchನ್ನು ‘ Branching ‘ ಯಾವ ಕಾರ್ಯವನ್ನು Git ಟ್ರ್ಯಾಕ್ ಮಾಡುತ್ತದೆ, ಆದ್ದರಿಂದ ಎಲ್ಲಾ ಫೈಲ್‌ಗಳ ಹಿಂದಿನ historyನ್ನು ಅದು ತಿಳಿದಿದೆ.

ನೀವು primary branchಯಲ್ಲಿದ್ದೀರಿ ಮತ್ತು ನಿಮ್ಮ ವೆಬ್ ಪುಟವನ್ನು ಅಭಿವೃದ್ಧಿಪಡಿಸಲು new branchನ್ನು ರಚಿಸಲು ಬಯಸುತ್ತೇವೆ ಎಂದು ಹೇಳೋಣ. ನೀವು ಏನು ಮಾಡುತ್ತೀರಿ ಎಂಬುದು ಇಲ್ಲಿದೆ:  **git checkout -b <my branch name>**  ಅನ್ನು Run ಮಾಡಿ. ಈ comment Automatic new branchನ್ನು ರಚಿಸುತ್ತದೆ ಮತ್ತು ಅದರ ಮೇಲೆ ‘Tests you ‘, ಅಂದರೆ Git ನಿಮ್ಮನ್ನು primary branch outside ಆ branchಗೆ ಸರಿಸುತ್ತದೆ.

ಮೇಲಿನ commentನ್ನು run ಮಾಡಿದ ನಂತರ, ನಿಮ್ಮ branchನ್ನು ರಚಿಸಲಾಗಿದೆ ಎಂದು ಖಚಿತಪಡಿಸಲು ನೀವು  **git branch**  commentನ್ನು ಬಳಸಬಹುದು:

mnelson:myproject mnelson$ git branch

master

* my-new-branch

ಅದರ ಪಕ್ಕದಲ್ಲಿರುವ strar signಯೊಂದಿಗೆ branch name, ಆ ಸಮಯದಲ್ಲಿ ನೀವು ಯಾವ branchನ್ನು ಸೂಚಿಸಿದ್ದೀರಿ ಎಂಬುದನ್ನು ಸೂಚಿಸುತ್ತದೆ.

ಈಗ, ನೀವು primary branchಗೆ ಹಿಂತಿರುಗಿ ಮತ್ತು ಇನ್ನೂ ಕೆಲವು commitಗಳನ್ನು ಮಾಡಿದರೆ, ಆ ಬದಲಾವಣೆಗಳನ್ನು ನಿಮ್ಮ new branch ಅಲ್ಲಿ Mergeಗೊಳಿಸುವವರೆಗೆ ನಿಮ್ಮ new branch ಆ ಯಾವುದೇ Changesಗಳನ್ನು ನೋಡುವುದಿಲ್ಲ.

**ಹಂತ 6: ಗಿಟ್‌ಹಬ್‌ನಲ್ಲಿ**  **ಹೊಸ**  **ರೆಪೊಸಿಟರಿಯನ್ನು**  **ರಚಿಸಿ**

ನಿಮ್ಮ code ಅನ್ನು local ಆಗಿ ಮಾತ್ರ track ಮಾಡಲು ನೀವು ಬಯಸಿದರೆ, ನೀವು GitHub ಅನ್ನು ಬಳಸಬೇಕಾಗಿಲ್ಲ. ಆದರೆ ನೀವು team/ತಂಡದೊಂದಿಗೆ ಕೆಲಸ ಮಾಡಲು ಬಯಸಿದರೆ, plan code ಅನ್ನು ಸಹಯೋಗದಿಂದ ಮಾರ್ಪಡಿಸಲು ನೀವು GitHubಅನ್ನು ಬಳಸಬಹುದುGitHub ನಲ್ಲಿ new repo ರಚಿಸಲು, ಲಾಗ್ ಇನ್ ಮಾಡಿ ಮತ್ತು GitHub Home Pageಗೆ ಹೋಗಿ. ನೀವು ಹಸಿರು  **‘+ New repository’** button: ನೋಡಬೇಕು

![Image for post](https://miro.medium.com/max/60/1*bwx-MoHu1Z4JxtzG5eMqHg.png?q=20)

![Image for post](https://miro.medium.com/max/839/1*bwx-MoHu1Z4JxtzG5eMqHg.png)

Button ಕ್ಲಿಕ್ ಮಾಡಿದ ನಂತರ, ನಿಮ್ಮ repoಗೆ ಹೆಸರಿಸಲು ಮತ್ತು Brief description ನೀಡಲು GitHub ನಿಮ್ಮನ್ನು ಕೇಳುತ್ತದೆ:

![Image for post](https://miro.medium.com/max/60/1*mrq8rM6RglipaSlsG2NUAw.png?q=20)

![Image for post](https://miro.medium.com/max/839/1*mrq8rM6RglipaSlsG2NUAw.png)

ನೀವು information fill ಮಾಡಿದ ನಂತರ, ನಿಮ್ಮ new repo ಮಾಡಲು ‘Create a repository’ button ಒತ್ತಿರಿ.

ನೀವು To create a new repo from scratch ಬಯಸುತ್ತೀರಾ ಅಥವಾ The repo you created locally ಸೇರಿಸಲು ಬಯಸುತ್ತೀರಾ ಎಂದು GitHub ಕೇಳುತ್ತದೆ. ಈ ಸಂದರ್ಭದಲ್ಲಿ, ನಾವು ಈಗಾಗಲೇ repo you created locally ನ್ನು ರಚಿಸಿದ್ದರಿಂದ, ನಾವು ಅದನ್ನು GitHubಗೆ push ಮಾಡಲು ಬಯಸುತ್ತೇವೆ ಆದ್ದರಿಂದ ‘…. or command line to push an existing repository ‘ ವಿಭಾಗವನ್ನು ಅನುಸರಿಸಿ:

mnelson:myproject mnelson$ git remote add origin  [https://github.com/cubeton/mynewrepository.git](https://github.com/cubeton/mynewrepository.git)

mnelson:myproject mnelson$ git push -u origin master

Counting objects: 3, done.

Writing objects: 100% (3/3), 263 bytes | 0 bytes/s, done.

Total 3 (delta 0), reused 0 (delta 0)

To  [https://github.com/cubeton/mynewrepository.git](https://github.com/cubeton/mynewrepository.git)

* [new branch] master -> master

Branch master set up to track remote branch master from origin.

(ನಿಮ್ಮ GitHub Username ಮತ್ತು repo name ವಿಭಿನ್ನವಾಗಿರುವುದರಿಂದ ಮೊದಲ command lineನಲ್ಲಿರುವ URL ಅನ್ನು ಈ ವಿಭಾಗದಲ್ಲಿ GitHub List ಮಾಡುವಂತೆ ಬದಲಾಯಿಸಲು ನೀವು ಬಯಸುತ್ತೀರಿ.)

**ಹಂತ 7: ಗಿಟ್‌ಹಬ್‌ಗೆ**  **branch ನ್ನು**  **Push** ಮಾಡಿ

ಈಗ ನಾವು ನಿಮ್ಮ branch ನ ಬದ್ಧತೆಯನ್ನು ನಿಮ್ಮ new GitHub repo push up ಮಾಡುತ್ತವೆ**.**  ನೀವು ಮಾಡಿದ Changesಗಳನ್ನು ನೋಡಲು ಇತರ ಜನರಿಗೆ ಇದು allow/ಅನುಮತಿಸುತ್ತದೆ. ಅವುಗಳನ್ನು repository owner approve/ಅನುಮೋದಿಸಿದರೆ, ಬದಲಾವಣೆಗಳನ್ನು ನಂತರ primary branchಲ್ಲಿ Mergeಗೊಳಿಸಬಹುದು.

Changesಗಳನ್ನು GitHub ನಲ್ಲಿ new branchಗೆ push ಮಾಡಲು, ನೀವು  [**git push**](http://git-scm.com/docs/git-push)  **origin your branchname**  ಅನ್ನು run/ಚಲಾಯಿಸಲು ಬಯಸುತ್ತೀರಿ. Remote repositoryಯಲ್ಲಿ GithHub ನಿಮಗಾಗಿ branchನ್ನು Automatic ರಚಿಸುತ್ತದೆ:

mnelson:myproject mnelson$ git push origin my-new-branch

Counting objects: 3, done.

Delta compression using up to 8 threads.

Compressing objects: 100% (2/2), done.

Writing objects: 100% (3/3), 313 bytes | 0 bytes/s, done.

Total 3 (delta 0), reused 0 (delta 0)

To  [https://github.com/cubeton/mynewrepository.git](https://github.com/cubeton/mynewrepository.git)

* [new branch] my-new-branch -> my-new-branch

ಮೇಲಿನ commandಲ್ಲಿ ಆ  **“Origin”**  ಪದದ ಅರ್ಥವೇನು ಎಂದು ನೀವು ಆಶ್ಚರ್ಯ ಪಡಬಹುದು. ಏನಾಗುತ್ತದೆ ಎಂದರೆ ನಿಮ್ಮ local machine ನೀವು Remote repository’s ನ್ನು clone ಮಾಡಿದಾಗ, git ನಿಮಗಾಗಿ Alias ಅನ್ನು ರಚಿಸುತ್ತದೆ. ಬಹುತೇಕ ಎಲ್ಲಾ ಸಂದರ್ಭಗಳಲ್ಲಿ ಈ ಅಲಿಯಾಸ್ ಅನ್ನು  **“Origin”**  ಎಂದು ಕರೆಯಲಾಗುತ್ತದೆ. ಇದು remote repository’s URL ಗಾಗಿ ಸಂಕ್ಷಿಪ್ತ ರೂಪವಾಗಿದೆ. ಆದ್ದರಿಂದ, ನಿಮ್ಮ ಬದಲಾವಣೆಗಳನ್ನು remote repository’s ಕ್ಕೆ push ಮಾಡಲು, ನೀವು commandನ್ನು ಬಳಸಬಹುದಿತ್ತು:  **git push git@github.com:git/git.git yourbranchname**  or  **git push origin yourbranchname**

(Local ಆಗಿ GitHub ಅನ್ನು ಬಳಸುವುದು ಇದು ನಿಮ್ಮ ಮೊದಲ ಬಾರಿಗೆ ಆಗಿದ್ದರೆ, ನಿಮ್ಮ GitHub username ಮತ್ತು password/ಪಾಸ್‌ವರ್ಡ್‌ನೊಂದಿಗೆ login ಮಾಡಲು ಇದು ನಿಮ್ಮನ್ನು ಕೇಳುತ್ತದೆ.)

ನೀವು GitHub pageನ್ನು refresh ಮಾಡಿದರೆ, ನಿಮ್ಮ name branchನ್ನು ರೆಪೊಸಿಟರಿಗೆ push ಮಾಡಲಾಗಿದೆ ಎಂದು ಹೇಳುವ noteನ್ನು ನೀವು ನೋಡುತ್ತೀರಿ. ನಿಮ್ಮ brachನ್ನು ಅಲ್ಲಿ list ಮಾಡಲು ನೀವು ‘ Branches ‘ link ಅನ್ನು ಸಹ ಕ್ಲಿಕ್ ಮಾಡಬಹುದು.

![Image for post](https://miro.medium.com/max/60/1*VoFidCNoJkUL3W1JpndQag.png?q=20)

![Image for post](https://miro.medium.com/max/1084/1*VoFidCNoJkUL3W1JpndQag.png)

ಈಗ ಮೇಲಿನ ಸ್ಕ್ರೀನ್‌ಶಾಟ್‌ನಲ್ಲಿರುವ green button ಕ್ಲಿಕ್ ಮಾಡಿ. ನಾವು ಮಾಡಲು ಹೊರಟಿದ್ದೇವೆ **pull request**!

**ಹಂತ 8: Pull Request (ಪಿಆರ್) ರಚಿಸಿ**

Pull Request (ಅಥವಾ PR) ಎಂಬುದು repo owner ನ orderಗೆ ಒಂದು ಮಾರ್ಗವಾಗಿದ್ದು, ನೀವು ಅವರ ಕೋಡ್‌ನಲ್ಲಿ ಕೆಲವು ಬದಲಾವಣೆಗಳನ್ನು ಮಾಡಲು ಬಯಸುತ್ತೀರಿ. Code ಅನ್ನು check ಮತ್ತು ನಿಮ್ಮ changesನ್ನು primary branchಲ್ಲಿ ಇಡುವ ಮೊದಲು ಅದು ಉತ್ತಮವಾಗಿ ಕಾಣುತ್ತದೆ ಎಂದು ಖಚಿತಪಡಿಸಿಕೊಳ್ಳಲು ಇದು ಅವರಿಗೆ Allow ಮಾಡುತ್ತವೆ..

ನೀವು ಅದನ್ನು ಸಲ್ಲಿಸುವ ಮೊದಲು PR page ಹೀಗಿರುತ್ತದೆ:

![Image for post](https://miro.medium.com/max/60/1*9cUuk5JgBJNZRZcWPD-0pw.png?q=20)

![Image for post](https://miro.medium.com/max/1086/1*9cUuk5JgBJNZRZcWPD-0pw.png)

ನೀವು ಒಮ್ಮೆ PR requestನ್ನು ಸಲ್ಲಿಸಿದ ನಂತರ ಇದು ಕಾಣುತ್ತದೆ:

![Image for post](https://miro.medium.com/max/60/1*xOwul9o3_EhDur9w5g3ECQ.png?q=20)

![Image for post](https://miro.medium.com/max/1086/1*xOwul9o3_EhDur9w5g3ECQ.png)

‘Merge pull request’ ಎಂದು ಹೇಳುವ ದೊಡ್ಡ green buttonನ್ನು ನೀವು ಕೆಳಭಾಗದಲ್ಲಿ ನೋಡಬಹುದು. ಇದನ್ನು ಕ್ಲಿಕ್ ಮಾಡುವುದರಿಂದ ನಿಮ್ಮ ಬದಲಾವಣೆಗಳನ್ನು ನೀವು primary branchಲ್ಲಿ mergeಗೊಳಿಸುತ್ತೀರಿ ಎಂದರ್ಥ.

ಈ ಬಟನ್ ಯಾವಾಗಲೂ green ಬಣ್ಣದಲ್ಲಿರುವುದಿಲ್ಲ ಎಂಬುದನ್ನು ಗಮನಿಸಿ. ಕೆಲವು ಸಂದರ್ಭಗಳಲ್ಲಿ ಇದು Gray ಬಣ್ಣದ್ದಾಗಿರುತ್ತದೆ, ಇದರರ್ಥ ನೀವು Merger conflictನ್ನು ಎದುರಿಸುತ್ತಿರುವಿರಿ. ಒಂದು ಫೈಲ್‌ನಲ್ಲಿ ಬದಲಾವಣೆಯಾದಾಗ ಮತ್ತೊಂದು ಫೈಲ್‌ನಲ್ಲಿನ ಬದಲಾವಣೆಯೊಂದಿಗೆ conflict/ಸಂಘರ್ಷಗೊಳ್ಳುತ್ತದೆ ಮತ್ತು ಯಾವ editionನ್ನು ಬಳಸಬೇಕೆಂದು Gitಗೆ ಕಂಡುಹಿಡಿಯಲಾಗುವುದಿಲ್ಲ. ನೀವು Manualವ ಆಗಿ inside ಹೋಗಿ ಯಾವ editionನ್ನು ಬಳಸಬೇಕೆಂದು Gitಗೆ ತಿಳಿಸಬೇಕು.

ಕೆಲವೊಮ್ಮೆ ನೀವು co-owner ಅಥವಾ sole owner of the repo ಆಗುತ್ತೀರಿ, ಈ ಸಂದರ್ಭದಲ್ಲಿ ನಿಮ್ಮ ಬದಲಾವಣೆಗಳನ್ನು mergeಗೊಳಿಸಲು ನೀವು PR ಅನ್ನು ರಚಿಸಬೇಕಾಗಿಲ್ಲ. ಆದಾಗ್ಯೂ, ಒಂದನ್ನು ಮಾಡುವುದು ಇನ್ನೂ ಒಳ್ಳೆಯದು ಆದ್ದರಿಂದ ನಿಮ್ಮ updateಗಳ ಸಂಪೂರ್ಣ historyನ್ನು ನೀವು ಇರಿಸಿಕೊಳ್ಳಬಹುದು ಮತ್ತು ಬದಲಾವಣೆಗಳನ್ನು ಮಾಡುವಾಗ ನೀವು ಯಾವಾಗಲೂ new branchನ್ನು ರಚಿಸುತ್ತೀರಿ ಎಂದು ಖಚಿತಪಡಿಸಿಕೊಳ್ಳಬಹುದು.

**‘Merger Pull Request’**  ಎಂದು ಹೇಳುವ ದೊಡ್ಡ green buttonನ್ನು ನೀವು ಕೆಳಭಾಗದಲ್ಲಿ ನೋಡಬಹುದು. ಇದನ್ನು ಕ್ಲಿಕ್ ಮಾಡುವುದರಿಂದ ನಿಮ್ಮ changesಗಳನ್ನು ನೀವು primary branchಲ್ಲಿ mergeಗೊಳಿಸುತ್ತೀರಿ ಎಂದರ್ಥ.

**ಹಂತ 9: PR**  **ಅನ್ನು**  **Mergeಗೊಳಿಸಿ**

ಮುಂದುವರಿಯಿರಿ ಮತ್ತು ಹಸಿರು ‘Merger Pull Request’ ಬಟನ್ ಕ್ಲಿಕ್ ಮಾಡಿ. ಇದು ನಿಮ್ಮ ಬದಲಾವಣೆಗಳನ್ನು primary branchಯಲ್ಲಿ mergeಗೊಳಿಸುತ್ತದೆ.

![Image for post](https://miro.medium.com/max/60/1*EfCX-wzzfRkKda75n2P1vQ.png?q=20)

![Image for post](https://miro.medium.com/max/1086/1*EfCX-wzzfRkKda75n2P1vQ.png)

ನೀವು ಪೂರ್ಣಗೊಳಿಸಿದಾಗ, ನಿಮ್ಮ branchನ್ನು delete ಮಾಡಲು ನಾನು ಶಿಫಾರಸು ಮಾಡುತ್ತೇವೆ (ಹಲವಾರು branchಗಳು ಗೊಂದಲಮಯವಾಗಬಹುದು), ಆದ್ದರಿಂದ grey ಬಣ್ಣದ ‘Delete the branch ‘ buttonನ್ನು ಒತ್ತಿರಿ.

ನಿಮ್ಮ ಹೊಸ repoದ ಮೊದಲ ಪುಟದಲ್ಲಿರುವ ‘commits’ ಲಿಂಕ್ ಅನ್ನು ಕ್ಲಿಕ್ ಮಾಡುವುದರ ಮೂಲಕ ನಿಮ್ಮ commits mergeಗೊಳಿಸಲಾಗಿದೆ ಎಂದು ನೀವು ಎರಡು ಬಾರಿ ಪರಿಶೀಲಿಸಬಹುದು.

![Image for post](https://miro.medium.com/max/60/1*f1amOCOGimM8G0QZMVIQ5A.png?q=20)

![Image for post](https://miro.medium.com/max/1085/1*f1amOCOGimM8G0QZMVIQ5A.png)

ಆ branchನ ಎಲ್ಲಾ commits listನ್ನು ಇದು ನಿಮಗೆ ತೋರಿಸುತ್ತದೆ. ನಾನು ಮೇಲ್ಭಾಗದಲ್ಲಿ merge/ವಿಲೀನಗೊಂಡದ್ದನ್ನು ನೀವು ನೋಡಬಹುದು (pull request # 2 ಅನ್ನು merge/ವಿಲೀನಗೊಳಿಸಿ).

![Image for post](https://miro.medium.com/max/60/1*g4TjElSzSuzljoMf_u-1AQ.png?q=20)

![Image for post](https://miro.medium.com/max/1086/1*g4TjElSzSuzljoMf_u-1AQ.png)

ನೀವು ಬಲಗೈಯಲ್ಲಿ commitment/ಬದ್ಧತೆಯ hash code ಅನ್ನು ಸಹ ನೋಡಬಹುದು. Hash code ನಿರ್ದಿಷ್ಟ ಬದ್ಧತೆಗೆ ಅನನ್ಯ ಗುರುತಿಸುವಿಕೆಯಾಗಿದೆ. Specific Commitsಗಳನ್ನು refer ಮತ್ತು ಬದಲಾವಣೆಗಳನ್ನು cancelಗೊಳಿಸುವಾಗ ಇದು ಉಪಯುಕ್ತವಾಗಿದೆ (Use the  **git revert <hash code number>**  command to backtrack).

**ಹಂತ 10: ನಿಮ್ಮ**  **ಕಂಪ್ಯೂಟರ್‌ಗೆ GitHub ನಲ್ಲಿ**  **ಬದಲಾವಣೆಗಳನ್ನು**  **ಪಡೆಯಿರಿ**

ಇದೀಗ, ನಿಮ್ಮ local machineನಲ್ಲಿ githubನಲ್ಲಿನ repo ಸ್ವಲ್ಪ ಭಿನ್ನವಾಗಿದೆ. ಉದಾಹರಣೆಗೆ, ನಿಮ್ಮ branchಲ್ಲಿ ನೀವು ಮಾಡಿದ ಮತ್ತು primary branchಲ್ಲಿ merge/ವಿಲೀನಗೊಂಡ ಬದ್ಧತೆ ನಿಮ್ಮ local machineನ primary branchಲ್ಲಿ existence/ಅಸ್ತಿತ್ವದಲ್ಲಿಲ್ಲ.

ನೀವು ಅಥವಾ ಇತರರು GitHubನಲ್ಲಿ merge/ವಿಲೀನಗೊಂಡಿರುವ ಇತ್ತೀಚಿನ changes ಪಡೆಯಲು, Git Pull Origin Master commandನ್ನು ಬಳಸಿ (primary branchಲ್ಲಿ ಕೆಲಸ ಮಾಡುವಾಗ).

mnelson:myproject mnelson$ git pull origin master

remote: Counting objects: 1, done.

remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0

Unpacking objects: 100% (1/1), done.

From  [https://github.com/cubeton/mynewrepository](https://github.com/cubeton/mynewrepository)

* branch master -> FETCH_HEAD

b345d9a..5381b7c master -> origin/master

Merge made by the ‘recursive’ strategy.

mnelson.txt | 1 +

1 file changed, 1 insertion(+)

ಬದಲಾದ ಎಲ್ಲಾ ಫೈಲ್‌ಗಳು ಮತ್ತು ಅವು ಹೇಗೆ ಬದಲಾಗಿದೆಯೆಂದು ಇದು ನಿಮಗೆ ತೋರಿಸುತ್ತದೆ.ಎಲ್ಲಾ ಹೊಸ commitಗಳನ್ನು ನೋಡಲು ಈಗ ನಾವು ಮತ್ತೆ  [**git log**](http://git-scm.com/docs/git-log)  commandನ್ನು ಬಳಸಬಹುದು.(ನೀವು branchesನ್ನು ಮತ್ತೆ primary branchಗೆ ಬದಲಾಯಿಸಬೇಕಾಗಬಹುದು.  **git checkout master**  ಯನ್ನು ಬಳಸಿಕೊಂಡು ನೀವು ಅದನ್ನು ಮಾಡಬಹುದು.)

mnelson:myproject mnelson$ git log

commit 3e270876db0e5ffd3e9bfc5edede89b64b83812c

Merge: 4f1cb17 5381b7c

Author: Meghan Nelson <mnelson@hubspot.com>

Date: Fri Sep 11 17:48:11 2015 -0400

Merge branch ‘master’ of  [https://github.com/cubeton/mynewrepository](https://github.com/cubeton/mynewrepository)

commit 4f1cb1798b6e6890da797f98383e6337df577c2a

Author: Meghan Nelson <mnelson@hubspot.com>

Date: Fri Sep 11 17:48:00 2015 -0400

added a new file

commit 5381b7c53212ca92151c743b4ed7dde07d9be3ce

Merge: b345d9a 1e8dc08

Author: Meghan Nelson <meghan@meghan.net>

Date: Fri Sep 11 17:43:22 2015 -0400

Merge pull request #2 from cubeton/my-newbranch

Added some more text to my file

commit 1e8dc0830b4db8c93efd80479ea886264768520c

Author: Meghan Nelson <mnelson@hubspot.com>

Date: Fri Sep 11 17:06:05 2015 -0400

Added some more text to my file

commit b345d9a25353037afdeaa9fcaf9f330effd157f1

Author: Meghan Nelson <mnelson@hubspot.com>

Date: Thu Sep 10 17:42:15 2015 -0400

This is my first commit!

**ಹಂತ 11: ನಿಮ್ಮ**  **Git gloryಲ್ಲಿ**  **ಬಾಸ್ಕ್**  **ಮಾಡಿ(Bask in your Git glory)**

ನೀವು ಯಶಸ್ವಿಯಾಗಿ PR ಅನ್ನು ಮಾಡಿದ್ದೀರಿ ಮತ್ತು ನಿಮ್ಮ ಕೋಡ್ ಅನ್ನು primary branchಗೆ (merge)ವಿಲೀನಗೊಳಿಸಿದ್ದೀರಿ. ಅಭಿನಂದನೆಗಳು! ನೀವು ಸ್ವಲ್ಪ ಆಳವಾಗಿ ಧುಮುಕುವುದಿಲ್ಲದಿದ್ದರೆ, Git ಮತ್ತು GitHub ಅನ್ನು ಬಳಸುವ ಕುರಿತು ಇನ್ನಷ್ಟು ಸಲಹೆಗಳು ಮತ್ತು Strategyಗಳಿಗಾಗಿ ಈ Git101 ಫೋಲ್ಡರ್‌ನಲ್ಲಿರುವ ಫೈಲ್‌ಗಳನ್ನು ಪರಿಶೀಲಿಸಿ.

ನಾವು ಇಲ್ಲಿ ಮಾಡಿದಂತೆ Small group projectನ್ನು Imitate/ಅನುಕರಿಸುವಲ್ಲಿ ನಿಮ್ಮ team/ತಂಡದೊಂದಿಗೆ ಕೆಲಸ ಮಾಡಲು ಸ್ವಲ್ಪ ಸಮಯವನ್ನು ಹುಡುಕಲು ನಾನು ಶಿಫಾರಸು ಮಾಡುತ್ತೇವೆ. ನಿಮ್ಮ ತಂಡದ ಹೆಸರಿನೊಂದಿಗೆ ನಿಮ್ಮ ತಂಡವು ಹೊಸ ಫೋಲ್ಡರ್ ಮಾಡಿ, ಮತ್ತು Text/ಪಠ್ಯದೊಂದಿಗೆ ಕೆಲವು ಫೈಲ್‌ಗಳನ್ನು ಸೇರಿಸಿ. ನಂತರ, ಈ ಬದಲಾವಣೆಗಳನ್ನು ಈ remote repoಗೆ push/ತಳ್ಳಲು ಪ್ರಯತ್ನಿಸಿ. ಆ ರೀತಿಯಲ್ಲಿ, ನಿಮ್ಮ ತಂಡವು ಮೂಲತಃ ರಚಿಸದ ಫೈಲ್‌ಗಳಲ್ಲಿ ಬದಲಾವಣೆಗಳನ್ನು ಮಾಡಲು ಪ್ರಾರಂಭಿಸಬಹುದು ಮತ್ತು PR featuresನ್ನು ಬಳಸಿ ಅಭ್ಯಾಸ ಮಾಡಬಹುದು. ಮತ್ತು, ಫೈಲ್‌ನಲ್ಲಿ ಯಾವ ಬದಲಾವಣೆಗಳನ್ನು ಮಾಡಲಾಗಿದೆ ಮತ್ತು ಯಾರು ಆ ಬದಲಾವಣೆಗಳನ್ನು ಮಾಡಿದ್ದಾರೆ ಎಂಬುದನ್ನು ಪತ್ತೆಹಚ್ಚಲು ಗಿಟ್‌ಹಬ್‌ನಲ್ಲಿರುವ Git Blame and Git History Tools ಬಳಸಿ.

ನೀವು ಹೆಚ್ಚು Gitಅನ್ನು ಬಳಸುತ್ತೀರಿ, ಹೆಚ್ಚು ಆರಾಮದಾಯಕವಾಗುತ್ತೀರಿ … ಅದರೊಂದಿಗೆ Git ಮಾಡಿ.

**Artical By: Akshatha Amin**

**Credits**:  [_https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners_](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)

MicroDegree is an edtech platform for learning Emerging Technologies such as Full-Stack Development, Data Science, Machine Learning using vernacular at an affordable price. For more details reach out to hello@microdegree.work

🚀 For Course Certification : [https://bit.ly/3gt2nY7](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqblAzcGQxZlRtSmdYZlppbDNUd2t0MFNSanV1QXxBQ3Jtc0tuS2VjaXpMd1hFS1I5NEFuMkxkYThlZE9MZkVzNGFmTXYxTTRtZjBsX0lkSTU3MEpEdnpCTnI3MUp2QVpNdWc0LXBjNEpVWEVhMTBuajBEeXRiMnZSWnpFVDJHMTlCRk91bkNpR24ySGxUSzJUblNfUQ%3D%3D&q=https%3A%2F%2Fbit.ly%2F3gt2nY7)

👍 Youtube::  [https://bit.ly/3ajK4Cz](https://bit.ly/3ajK4Cz)

Website : [https://microdegree.work](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqbjR2M3JJekdSZTZlTVFCNkt5RFBTc1JNMlhpUXxBQ3Jtc0tuZHhRdjZtQW9ubmliWXAxSVNfMm5UemNrS2RMd1hDMmtIdEdGcmlFZmpkTDRkV1JFbkl3Wng1b2NRSXZJeWVlMjFGWmRpWmJSUU5jTGZmMFA0NTMxRUJtTnBlVlNESUdDYlA1QU4tcUdzZ1gwZHFUWQ%3D%3D&q=https%3A%2F%2Fmicrodegree.work)

LinkedIn : [https://www.linkedin.com/company/micr](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqa1Z1SEw5M182a2I3ZC1BN25WeFdYYVNaRWkzQXxBQ3Jtc0tsTmlGQkN5RExFekhvWWFjVHJEZUZadVZVNW5NTURjYkxaSWlVTzFJaVU0aUJ3Q1Y1QXZaRU5sbEJFaVpiOUp6a3V4a3dZczVlSVA4SzVvYU1Jc3A3SEVUMkROUEpNeFFSNkxrbldZOVhTQTBUQWdFbw%3D%3D&q=https%3A%2F%2Fwww.linkedin.com%2Fcompany%2Fmicr)...

Facebook : [https://www.facebook.com/microdegree](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqa3BNeV9oRnNsVmdiMW1malJ4M3M2REVXUVItUXxBQ3Jtc0tsN0V6MXIxOXRCSU9DMDVBQm0wemEyMnFWMWRNQVRNNlNxX2ZwOHdQLWRUWVQ1SnBSR3JFLUFnLV9VS2FYdk9QQ0x5MjZZOEMyV2JkV2o2emNVMHhZVEZUbDRKdTBoVnBXS3FGNERiZkN3aFNXOF9Xbw%3D%3D&q=https%3A%2F%2Fwww.facebook.com%2Fmicrodegree)

Instagram : [https://www.instagram.com/micro.degree](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqbU82YjFKOFBrMXZ4QkRrWWtlbTlzV1VvU1g1QXxBQ3Jtc0trYndfRGt1cUtVS3ZUaFRkVEJtSUd4M1VJTndfR2s1WDQ0Y3Axd0dXdzN1eVRNZHF2VEo5MFhyZkkxRmVXcXJZMUN0X1dXYTZsY1RyNS11OVJWWG0zd0ZKX1EzcXJMSFU4Tnd2QzF6dUJYLTdrZW0zaw%3D%3D&q=https%3A%2F%2Fwww.instagram.com%2Fmicro.degree)