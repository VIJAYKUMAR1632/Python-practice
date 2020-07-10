Microsoft Windows [Version 10.0.18363.900]
(c) 2019 Microsoft Corporation. All rights reserved.

C:\Users\VIJAY KUMAR>git status
fatal: not a git repository (or any of the parent directories): .git

C:\Users\VIJAY KUMAR>cd Devweb

C:\Users\VIJAY KUMAR\DevWeb>git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Practice/Week3/Restaurant.html
        modified:   Practice/Week3/css/styles.css

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Practice/week3/img/

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\VIJAY KUMAR\DevWeb>git config --list --show-origin
file:C:/Program Files/Git/etc/gitconfig diff.astextplain.textconv=astextplain
file:C:/Program Files/Git/etc/gitconfig filter.lfs.clean=git-lfs clean -- %f
file:C:/Program Files/Git/etc/gitconfig filter.lfs.smudge=git-lfs smudge -- %f
file:C:/Program Files/Git/etc/gitconfig filter.lfs.process=git-lfs filter-process
file:C:/Program Files/Git/etc/gitconfig filter.lfs.required=true
file:C:/Program Files/Git/etc/gitconfig http.sslbackend=openssl
file:C:/Program Files/Git/etc/gitconfig http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
file:C:/Program Files/Git/etc/gitconfig core.autocrlf=true
file:C:/Program Files/Git/etc/gitconfig core.fscache=true
file:C:/Program Files/Git/etc/gitconfig core.symlinks=false
file:C:/Program Files/Git/etc/gitconfig core.editor="C:\\Program Files\\Sublime Text 3\\subl.exe" -w
file:C:/Program Files/Git/etc/gitconfig pull.rebase=false
file:C:/Program Files/Git/etc/gitconfig credential.helper=manager
file:C:/Users/VIJAY KUMAR/.gitconfig    user.email=2016uch1632@mnit.ac.in
file:C:/Users/VIJAY KUMAR/.gitconfig    user.name=VIJAYKUMAR1632
file:.git/config        core.repositoryformatversion=0
file:.git/config        core.filemode=false
file:.git/config        core.bare=false
file:.git/config        core.logallrefupdates=true
file:.git/config        core.symlinks=false
file:.git/config        core.ignorecase=true
file:.git/config        remote.origin.url=https://github.com/VIJAYKUMAR1632/Coursera-test.git
file:.git/config        remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
file:.git/config        branch.master.remote=origin
file:.git/config        branch.master.merge=refs/heads/master
file:.git/config        branch.gh-pages.remote=origin
file:.git/config        branch.gh-pages.merge=refs/heads/gh-pages

C:\Users\VIJAY KUMAR\DevWeb>cd..

C:\Users\VIJAY KUMAR>cd Python-practice

C:\Users\VIJAY KUMAR\python-practice>git status
fatal: not a git repository (or any of the parent directories): .git

C:\Users\VIJAY KUMAR\python-practice>git init
Initialized empty Git repository in C:/Users/VIJAY KUMAR/python-practice/.git/

C:\Users\VIJAY KUMAR\python-practice>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .ipynb_checkpoints/
        Analyzing data/
        Example2.txt
        Example3.txt
        Logistic_Regression_with_a_Neural_Network_mindset_v6a.ipynb
        Matplotlib/
        Neural Network/
        Python_basics/
        Revision_classes.ipynb
        first_python_code.ipynb

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\VIJAY KUMAR\python-practice>git log
fatal: your current branch 'master' does not have any commits yet

C:\Users\VIJAY KUMAR\python-practice>git add .
warning: LF will be replaced by CRLF in .ipynb_checkpoints/1.3_notebook_quizz_String_Operations-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/2.1_notebook_quizz_list_tuplesv4-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/2.2_notebook_quizz_sets-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/4.3_notebook_quizz_pandas-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/4.4_notebook_quizz_pandas-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/DA0101EN-Review-Introduction-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/DV0101EN-Exercise-Introduction-to-Matplotlib-and-Line-Plots-py-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/Logistic_Regression_with_a_Neural_Network_mindset_v6a-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/PY0101EN-2-1-Tuples-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/PY0101EN-2-3-Sets-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/PY0101EN-2-4-Dictionaries-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/PY0101EN-3-1-Conditions-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/PY0101EN-3-2-Loops-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/PY0101EN-3-3-Functions-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/PY0101EN-3-4-Classes-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/PY0101EN-4-1-ReadFile-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/PY0101EN-4-2-WriteFile-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/PY0101EN-4-3-LoadData-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/Practice-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/Python_Basics_With_Numpy_v3a-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/Revision_classes-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .ipynb_checkpoints/first_python_code-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/.ipynb_checkpoints/DA0101EN-Review-Data-Wrangling-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/.ipynb_checkpoints/DA0101EN-Review-Exploratory-Data-Analysis-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/.ipynb_checkpoints/DA0101EN-Review-Introduction-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/.ipynb_checkpoints/DA0101EN-Review-Model-Development-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/.ipynb_checkpoints/DA0101EN-Review-Model-Evaluation-and-Refinement-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/DA0101EN-Review-Data-Wrangling.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/DA0101EN-Review-Exploratory-Data-Analysis.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/DA0101EN-Review-Introduction.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/DA0101EN-Review-Model-Development.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/DA0101EN-Review-Model-Evaluation-and-Refinement.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/Practice1/.ipynb_checkpoints/DA0101EN-Review-Data-Wrangling-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/Practice1/DA0101EN-Review-Data-Wrangling.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/Practice1/DA0101EN-Review-Exploratory-Data-Analysis.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/Practice1/DA0101EN-Review-Introduction.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/Practice1/DA0101EN-Review-Model-Development.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Analyzing data/Practice1/DA0101EN-Review-Model-Evaluation-and-Refinement.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Logistic_Regression_with_a_Neural_Network_mindset_v6a.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Matplotlib/DV0101EN-Exercise-Introduction-to-Matplotlib-and-Line-Plots-py.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Neural Network/.ipynb_checkpoints/Logistic_Regression_with_a_Neural_Network_mindset_v6a-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Neural Network/.ipynb_checkpoints/Logistic_regression-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Neural Network/.ipynb_checkpoints/Python_Basics_With_Numpy_v3a-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Neural Network/Logistic_Regression_with_a_Neural_Network_mindset_v6a.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Neural Network/Logistic_regression.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Neural Network/Python_Basics_With_Numpy_v3a.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/.ipynb_checkpoints/Example1-checkpoint.txt.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/.ipynb_checkpoints/PY0101EN-3-4-Classes-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/.ipynb_checkpoints/PY0101EN-4-1-ReadFile-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/.ipynb_checkpoints/Practice-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/.ipynb_checkpoints/load_files-checkpoint.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/1.1_notebook_quizz_v2.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/1.3_notebook_quizz_String_Operations.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/2.1_notebook_quizz_list_tuplesv4.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/2.2_notebook_quizz_sets.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/4.3_notebook_quizz_pandas.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/4.4_notebook_quizz_pandas.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/Example1.txt.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/PY0101EN-2-1-Tuples.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/PY0101EN-2-3-Sets.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/PY0101EN-2-4-Dictionaries.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/PY0101EN-3-1-Conditions.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/PY0101EN-3-2-Loops.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/PY0101EN-3-3-Functions.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/PY0101EN-3-4-Classes.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/PY0101EN-4-1-ReadFile.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/PY0101EN-4-2-WriteFile.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/PY0101EN-4-3-LoadData.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/Practice.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Python_basics/load_files.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Revision_classes.ipynb.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in first_python_code.ipynb.
The file will have its original line endings in your working directory

C:\Users\VIJAY KUMAR\python-practice>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .ipynb_checkpoints/1.3_notebook_quizz_String_Operations-checkpoint.ipynb
        new file:   .ipynb_checkpoints/2.1_notebook_quizz_list_tuplesv4-checkpoint.ipynb
        new file:   .ipynb_checkpoints/2.2_notebook_quizz_sets-checkpoint.ipynb
        new file:   .ipynb_checkpoints/4.3_notebook_quizz_pandas-checkpoint.ipynb
        new file:   .ipynb_checkpoints/4.4_notebook_quizz_pandas-checkpoint.ipynb
        new file:   .ipynb_checkpoints/DA0101EN-Review-Introduction-checkpoint.ipynb
        new file:   .ipynb_checkpoints/DV0101EN-Exercise-Introduction-to-Matplotlib-and-Line-Plots-py-checkpoint.ipynb
        new file:   .ipynb_checkpoints/Logistic_Regression_with_a_Neural_Network_mindset_v6a-checkpoint.ipynb
        new file:   .ipynb_checkpoints/PY0101EN-2-1-Tuples-checkpoint.ipynb
        new file:   .ipynb_checkpoints/PY0101EN-2-3-Sets-checkpoint.ipynb
        new file:   .ipynb_checkpoints/PY0101EN-2-4-Dictionaries-checkpoint.ipynb
        new file:   .ipynb_checkpoints/PY0101EN-3-1-Conditions-checkpoint.ipynb
        new file:   .ipynb_checkpoints/PY0101EN-3-2-Loops-checkpoint.ipynb
        new file:   .ipynb_checkpoints/PY0101EN-3-3-Functions-checkpoint.ipynb
        new file:   .ipynb_checkpoints/PY0101EN-3-4-Classes-checkpoint.ipynb
        new file:   .ipynb_checkpoints/PY0101EN-4-1-ReadFile-checkpoint.ipynb
        new file:   .ipynb_checkpoints/PY0101EN-4-2-WriteFile-checkpoint.ipynb
        new file:   .ipynb_checkpoints/PY0101EN-4-3-LoadData-checkpoint.ipynb
        new file:   .ipynb_checkpoints/Practice-checkpoint.ipynb
        new file:   .ipynb_checkpoints/Python_Basics_With_Numpy_v3a-checkpoint.ipynb
        new file:   .ipynb_checkpoints/Revision_classes-checkpoint.ipynb
        new file:   .ipynb_checkpoints/first_python_code-checkpoint.ipynb
        new file:   Analyzing data/.ipynb_checkpoints/DA0101EN-Review-Data-Wrangling-checkpoint.ipynb
        new file:   Analyzing data/.ipynb_checkpoints/DA0101EN-Review-Exploratory-Data-Analysis-checkpoint.ipynb
        new file:   Analyzing data/.ipynb_checkpoints/DA0101EN-Review-Introduction-checkpoint.ipynb
        new file:   Analyzing data/.ipynb_checkpoints/DA0101EN-Review-Model-Development-checkpoint.ipynb
        new file:   Analyzing data/.ipynb_checkpoints/DA0101EN-Review-Model-Evaluation-and-Refinement-checkpoint.ipynb
        new file:   Analyzing data/.ipynb_checkpoints/clean_df-checkpoint.csv
        new file:   Analyzing data/DA0101EN-Review-Data-Wrangling.ipynb
        new file:   Analyzing data/DA0101EN-Review-Exploratory-Data-Analysis.ipynb
        new file:   Analyzing data/DA0101EN-Review-Introduction.ipynb
        new file:   Analyzing data/DA0101EN-Review-Model-Development.ipynb
        new file:   Analyzing data/DA0101EN-Review-Model-Evaluation-and-Refinement.ipynb
        new file:   Analyzing data/Practice1/.ipynb_checkpoints/DA0101EN-Review-Data-Wrangling-checkpoint.ipynb
        new file:   Analyzing data/Practice1/DA0101EN-Review-Data-Wrangling.ipynb
        new file:   Analyzing data/Practice1/DA0101EN-Review-Exploratory-Data-Analysis.ipynb
        new file:   Analyzing data/Practice1/DA0101EN-Review-Introduction.ipynb
        new file:   Analyzing data/Practice1/DA0101EN-Review-Model-Development.ipynb
        new file:   Analyzing data/Practice1/DA0101EN-Review-Model-Evaluation-and-Refinement.ipynb
        new file:   Analyzing data/clean_df.csv
        new file:   Analyzing data/module_5_auto.csv
        new file:   Example2.txt
        new file:   Example3.txt
        new file:   Logistic_Regression_with_a_Neural_Network_mindset_v6a.ipynb
        new file:   Matplotlib/DV0101EN-Exercise-Introduction-to-Matplotlib-and-Line-Plots-py.ipynb
        new file:   Neural Network/.ipynb_checkpoints/Logistic_Regression_with_a_Neural_Network_mindset_v6a-checkpoint.ipynb
        new file:   Neural Network/.ipynb_checkpoints/Logistic_regression-checkpoint.ipynb
        new file:   Neural Network/.ipynb_checkpoints/Python_Basics_With_Numpy_v3a-checkpoint.ipynb
        new file:   Neural Network/Logistic_Regression_with_a_Neural_Network_mindset_v6a.ipynb
        new file:   Neural Network/Logistic_regression.ipynb
        new file:   Neural Network/Python_Basics_With_Numpy_v3a.ipynb
        new file:   Python_basics/.ipynb_checkpoints/Example1-checkpoint.txt
        new file:   Python_basics/.ipynb_checkpoints/PY0101EN-3-4-Classes-checkpoint.ipynb
        new file:   Python_basics/.ipynb_checkpoints/PY0101EN-4-1-ReadFile-checkpoint.ipynb
        new file:   Python_basics/.ipynb_checkpoints/Practice-checkpoint.ipynb
        new file:   Python_basics/.ipynb_checkpoints/load_files-checkpoint.ipynb
        new file:   Python_basics/1.1_notebook_quizz_v2.ipynb
        new file:   Python_basics/1.3_notebook_quizz_String_Operations.ipynb
        new file:   Python_basics/2.1_notebook_quizz_list_tuplesv4.ipynb
        new file:   Python_basics/2.2_notebook_quizz_sets.ipynb
        new file:   Python_basics/4.3_notebook_quizz_pandas.ipynb
        new file:   Python_basics/4.4_notebook_quizz_pandas.ipynb
        new file:   Python_basics/Example1.txt
        new file:   Python_basics/Example_lines.txt
        new file:   Python_basics/PY0101EN-2-1-Tuples.ipynb
        new file:   Python_basics/PY0101EN-2-3-Sets.ipynb
        new file:   Python_basics/PY0101EN-2-4-Dictionaries.ipynb
        new file:   Python_basics/PY0101EN-3-1-Conditions.ipynb
        new file:   Python_basics/PY0101EN-3-2-Loops.ipynb
        new file:   Python_basics/PY0101EN-3-3-Functions.ipynb
        new file:   Python_basics/PY0101EN-3-4-Classes.ipynb
        new file:   Python_basics/PY0101EN-4-1-ReadFile.ipynb
        new file:   Python_basics/PY0101EN-4-2-WriteFile.ipynb
        new file:   Python_basics/PY0101EN-4-3-LoadData.ipynb
        new file:   Python_basics/Practice.ipynb
        new file:   Python_basics/load_files.ipynb
        new file:   Python_basics/songs.csv
        new file:   Revision_classes.ipynb
        new file:   first_python_code.ipynb


C:\Users\VIJAY KUMAR\python-practice>git commit -m "Machine Learning Project Dawn"
[master (root-commit) ab3ace1] Machine Learning Project Dawn
 79 files changed, 94117 insertions(+)
 create mode 100644 .ipynb_checkpoints/1.3_notebook_quizz_String_Operations-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/2.1_notebook_quizz_list_tuplesv4-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/2.2_notebook_quizz_sets-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/4.3_notebook_quizz_pandas-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/4.4_notebook_quizz_pandas-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/DA0101EN-Review-Introduction-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/DV0101EN-Exercise-Introduction-to-Matplotlib-and-Line-Plots-py-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/Logistic_Regression_with_a_Neural_Network_mindset_v6a-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/PY0101EN-2-1-Tuples-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/PY0101EN-2-3-Sets-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/PY0101EN-2-4-Dictionaries-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/PY0101EN-3-1-Conditions-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/PY0101EN-3-2-Loops-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/PY0101EN-3-3-Functions-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/PY0101EN-3-4-Classes-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/PY0101EN-4-1-ReadFile-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/PY0101EN-4-2-WriteFile-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/PY0101EN-4-3-LoadData-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/Practice-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/Python_Basics_With_Numpy_v3a-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/Revision_classes-checkpoint.ipynb
 create mode 100644 .ipynb_checkpoints/first_python_code-checkpoint.ipynb
 create mode 100644 Analyzing data/.ipynb_checkpoints/DA0101EN-Review-Data-Wrangling-checkpoint.ipynb
 create mode 100644 Analyzing data/.ipynb_checkpoints/DA0101EN-Review-Exploratory-Data-Analysis-checkpoint.ipynb
 create mode 100644 Analyzing data/.ipynb_checkpoints/DA0101EN-Review-Introduction-checkpoint.ipynb
 create mode 100644 Analyzing data/.ipynb_checkpoints/DA0101EN-Review-Model-Development-checkpoint.ipynb
 create mode 100644 Analyzing data/.ipynb_checkpoints/DA0101EN-Review-Model-Evaluation-and-Refinement-checkpoint.ipynb
 create mode 100644 Analyzing data/.ipynb_checkpoints/clean_df-checkpoint.csv
 create mode 100644 Analyzing data/DA0101EN-Review-Data-Wrangling.ipynb
 create mode 100644 Analyzing data/DA0101EN-Review-Exploratory-Data-Analysis.ipynb
 create mode 100644 Analyzing data/DA0101EN-Review-Introduction.ipynb
 create mode 100644 Analyzing data/DA0101EN-Review-Model-Development.ipynb
 create mode 100644 Analyzing data/DA0101EN-Review-Model-Evaluation-and-Refinement.ipynb
 create mode 100644 Analyzing data/Practice1/.ipynb_checkpoints/DA0101EN-Review-Data-Wrangling-checkpoint.ipynb
 create mode 100644 Analyzing data/Practice1/DA0101EN-Review-Data-Wrangling.ipynb
 create mode 100644 Analyzing data/Practice1/DA0101EN-Review-Exploratory-Data-Analysis.ipynb
 create mode 100644 Analyzing data/Practice1/DA0101EN-Review-Introduction.ipynb
 create mode 100644 Analyzing data/Practice1/DA0101EN-Review-Model-Development.ipynb
 create mode 100644 Analyzing data/Practice1/DA0101EN-Review-Model-Evaluation-and-Refinement.ipynb
 create mode 100644 Analyzing data/clean_df.csv
 create mode 100644 Analyzing data/module_5_auto.csv
 create mode 100644 Example2.txt
 create mode 100644 Example3.txt
 create mode 100644 Logistic_Regression_with_a_Neural_Network_mindset_v6a.ipynb
 create mode 100644 Matplotlib/DV0101EN-Exercise-Introduction-to-Matplotlib-and-Line-Plots-py.ipynb
 create mode 100644 Neural Network/.ipynb_checkpoints/Logistic_Regression_with_a_Neural_Network_mindset_v6a-checkpoint.ipynb
 create mode 100644 Neural Network/.ipynb_checkpoints/Logistic_regression-checkpoint.ipynb
 create mode 100644 Neural Network/.ipynb_checkpoints/Python_Basics_With_Numpy_v3a-checkpoint.ipynb
 create mode 100644 Neural Network/Logistic_Regression_with_a_Neural_Network_mindset_v6a.ipynb
 create mode 100644 Neural Network/Logistic_regression.ipynb
 create mode 100644 Neural Network/Python_Basics_With_Numpy_v3a.ipynb
 create mode 100644 Python_basics/.ipynb_checkpoints/Example1-checkpoint.txt
 create mode 100644 Python_basics/.ipynb_checkpoints/PY0101EN-3-4-Classes-checkpoint.ipynb
 create mode 100644 Python_basics/.ipynb_checkpoints/PY0101EN-4-1-ReadFile-checkpoint.ipynb
 create mode 100644 Python_basics/.ipynb_checkpoints/Practice-checkpoint.ipynb
 create mode 100644 Python_basics/.ipynb_checkpoints/load_files-checkpoint.ipynb
 create mode 100644 Python_basics/1.1_notebook_quizz_v2.ipynb
 create mode 100644 Python_basics/1.3_notebook_quizz_String_Operations.ipynb
 create mode 100644 Python_basics/2.1_notebook_quizz_list_tuplesv4.ipynb
 create mode 100644 Python_basics/2.2_notebook_quizz_sets.ipynb
 create mode 100644 Python_basics/4.3_notebook_quizz_pandas.ipynb
 create mode 100644 Python_basics/4.4_notebook_quizz_pandas.ipynb
 create mode 100644 Python_basics/Example1.txt
 create mode 100644 Python_basics/Example_lines.txt
 create mode 100644 Python_basics/PY0101EN-2-1-Tuples.ipynb
 create mode 100644 Python_basics/PY0101EN-2-3-Sets.ipynb
 create mode 100644 Python_basics/PY0101EN-2-4-Dictionaries.ipynb
 create mode 100644 Python_basics/PY0101EN-3-1-Conditions.ipynb
 create mode 100644 Python_basics/PY0101EN-3-2-Loops.ipynb
 create mode 100644 Python_basics/PY0101EN-3-3-Functions.ipynb
 create mode 100644 Python_basics/PY0101EN-3-4-Classes.ipynb
 create mode 100644 Python_basics/PY0101EN-4-1-ReadFile.ipynb
 create mode 100644 Python_basics/PY0101EN-4-2-WriteFile.ipynb
 create mode 100644 Python_basics/PY0101EN-4-3-LoadData.ipynb
 create mode 100644 Python_basics/Practice.ipynb
 create mode 100644 Python_basics/load_files.ipynb
 create mode 100644 Python_basics/songs.csv
 create mode 100644 Revision_classes.ipynb
 create mode 100644 first_python_code.ipynb

C:\Users\VIJAY KUMAR\python-practice>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\Users\VIJAY KUMAR\python-practice>git push python-practice
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream python-practice master


C:\Users\VIJAY KUMAR\python-practice>git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
core.editor="C:\\Program Files\\Sublime Text 3\\subl.exe" -w
pull.rebase=false
credential.helper=manager
user.email=2016uch1632@mnit.ac.in
user.name=VIJAYKUMAR1632
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true

C:\Users\VIJAY KUMAR\python-practice>git remote add python-practice https://github.com/VIJAYKUMAR1632/python-practice.git

C:\Users\VIJAY KUMAR\python-practice>git status
On branch master
nothing to commit, working tree clean

C:\Users\VIJAY KUMAR\python-practice>git log
commit ab3ace11f0464a2ccb0eed910d8c0a9156cf0d15 (HEAD -> master)
Author: VIJAYKUMAR1632 <2016uch1632@mnit.ac.in>
Date:   Thu Jul 9 11:45:53 2020 +0530

    Machine Learning Project Dawn

C:\Users\VIJAY KUMAR\python-practice>git clone https://github.com/VIJAYKUMAR1632/python-practice.git
Cloning into 'python-practice'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 619 bytes | 29.00 KiB/s, done.

C:\Users\VIJAY KUMAR\python-practice>git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        python-practice/

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\VIJAY KUMAR\python-practice>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\Users\VIJAY KUMAR\python-practice>git add python-practice
warning: adding embedded git repository: python-practice
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> python-practice
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint:   git rm --cached python-practice
hint:
hint: See "git help submodule" for more information.

C:\Users\VIJAY KUMAR\python-practice>git rm --cached  python-practice
error: the following file has staged content different from both the
file and the HEAD:
    python-practice
(use -f to force removal)

C:\Users\VIJAY KUMAR\python-practice>git rm -f --cached  python-practice
rm 'python-practice'

C:\Users\VIJAY KUMAR\python-practice>git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        python-practice/

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\VIJAY KUMAR\python-practice>git status
On branch master
nothing to commit, working tree clean

C:\Users\VIJAY KUMAR\python-practice>git ls-remote python-practice
5e73b23c019f76c1a0dc9b0c2645f86cd04c9754        HEAD
5e73b23c019f76c1a0dc9b0c2645f86cd04c9754        refs/heads/master

C:\Users\VIJAY KUMAR\python-practice>git pull python-practice --allow-unrelated-histories
warning: no common commits
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 619 bytes | 36.00 KiB/s, done.
From https://github.com/VIJAYKUMAR1632/python-practice
 * [new branch]      master     -> python-practice/master
You asked to pull from the remote 'python-practice', but did not specify
a branch. Because this is not the default configured remote
for your current branch, you must specify a branch on the command line.

C:\Users\VIJAY KUMAR\python-practice>git status
On branch master
nothing to commit, working tree clean

C:\Users\VIJAY KUMAR\python-practice>git push -u python-practice master
To https://github.com/VIJAYKUMAR1632/python-practice.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/VIJAYKUMAR1632/python-practice.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\Users\VIJAY KUMAR\python-practice>git  pull --help

C:\Users\VIJAY KUMAR\python-practice>git fetch --help

C:\Users\VIJAY KUMAR\python-practice>git fetch python practice
fatal: 'python' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

C:\Users\VIJAY KUMAR\python-practice>git fetch python-practice

C:\Users\VIJAY KUMAR\python-practice>git status
On branch master
nothing to commit, working tree clean

C:\Users\VIJAY KUMAR\python-practice>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\Users\VIJAY KUMAR\python-practice>git push --set-upstream python-practice master
To https://github.com/VIJAYKUMAR1632/python-practice.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/VIJAYKUMAR1632/python-practice.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\Users\VIJAY KUMAR\python-practice>git pull python-practice master --allow-unrelated-histories
From https://github.com/VIJAYKUMAR1632/python-practice
 * branch            master     -> FETCH_HEAD
Merge made by the 'recursive' strategy.
 README.md | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 README.md

C:\Users\VIJAY KUMAR\python-practice>git push python-practice
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream python-practice master


C:\Users\VIJAY KUMAR\python-practice>git push --set-upstream python-practice master
Enumerating objects: 73, done.
Counting objects: 100% (73/73), done.
Delta compression using up to 8 threads
Compressing objects: 100% (70/70), done.
Writing objects: 100% (72/72), 774.50 KiB | 6.92 MiB/s, done.
Total 72 (delta 38), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (38/38), done.
To https://github.com/VIJAYKUMAR1632/python-practice.git
   5e73b23..c550d19  master -> master
Branch 'master' set up to track remote branch 'master' from 'python-practice'.

C:\Users\VIJAY KUMAR\python-practice>git status
On branch master
Your branch is up to date with 'python-practice/master'.

nothing to commit, working tree clean

C:\Users\VIJAY KUMAR\python-practice>git push
Everything up-to-date

C:\Users\VIJAY KUMAR\python-practice>cd..

C:\Users\VIJAY KUMAR>cd Coursera-test
The system cannot find the path specified.

C:\Users\VIJAY KUMAR>cd devweb

C:\Users\VIJAY KUMAR\DevWeb>git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Practice/Week3/Restaurant.html
        modified:   Practice/Week3/css/styles.css

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Practice/week3/img/

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\VIJAY KUMAR\DevWeb>git branch
  gh-pages
* master

C:\Users\VIJAY KUMAR\DevWeb>git branch
  gh-pages
* master

C:\Users\VIJAY KUMAR\DevWeb>git checkout -b edit
Switched to a new branch 'edit'

C:\Users\VIJAY KUMAR\DevWeb>git branch
* edit
  gh-pages
  master

C:\Users\VIJAY KUMAR\DevWeb>git status
On branch edit
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Practice/Week3/Restaurant.html
        modified:   Practice/Week3/css/styles.css

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Practice/week3/img/

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\VIJAY KUMAR\DevWeb>git push
fatal: The current branch edit has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin edit


C:\Users\VIJAY KUMAR\DevWeb>git push --set-upstream Coursera-test edit
fatal: 'Coursera-test' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

C:\Users\VIJAY KUMAR\DevWeb>git remote -v
origin  https://github.com/VIJAYKUMAR1632/Coursera-test.git (fetch)
origin  https://github.com/VIJAYKUMAR1632/Coursera-test.git (push)

C:\Users\VIJAY KUMAR\DevWeb>git push --set-upstream origin edit
Everything up-to-date
Branch 'edit' set up to track remote branch 'edit' from 'origin'.

C:\Users\VIJAY KUMAR\DevWeb>git staus
git: 'staus' is not a git command. See 'git --help'.

The most similar command is
        status

C:\Users\VIJAY KUMAR\DevWeb>git status
On branch edit
Your branch is up to date with 'origin/edit'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Practice/Week3/Restaurant.html
        modified:   Practice/Week3/css/styles.css

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Practice/week3/img/

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\VIJAY KUMAR\DevWeb>git add .

C:\Users\VIJAY KUMAR\DevWeb>git commit -m "Creating a version
[edit edb73eb] Creating a version
 9 files changed, 35 insertions(+), 3 deletions(-)
 create mode 100644 Practice/Week3/img/jumbotron_1200.jpg
 create mode 100644 Practice/Week3/img/jumbotron_768.jpg
 create mode 100644 Practice/Week3/img/menu-tile.jpg
 create mode 100644 Practice/Week3/img/restaurant-logo_large.png
 create mode 100644 Practice/Week3/img/specials-tile.jpg
 create mode 100644 Practice/Week3/img/spinner.svg
 create mode 100644 Practice/Week3/img/star-k-logo.png

C:\Users\VIJAY KUMAR\DevWeb>git status
On branch edit
Your branch is ahead of 'origin/edit' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\VIJAY KUMAR\DevWeb>git push
Enumerating objects: 21, done.
Counting objects: 100% (21/21), done.
Delta compression using up to 8 threads
Compressing objects: 100% (15/15), done.
Writing objects: 100% (15/15), 613.46 KiB | 22.72 MiB/s, done.
Total 15 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 4 local objects.
To https://github.com/VIJAYKUMAR1632/Coursera-test.git
   e589d09..edb73eb  edit -> edit

C:\Users\VIJAY KUMAR\DevWeb>


