Archives of repositories
========================

The archives of various GitHub repositories found in this directory were produced using the following steps:

1. I ran version 0.33.1 of [github-backup](https://pypi.org/project/github-backup/) using the following command line (where _REPO-OWNER_ stands for the owner of the target repository and _REPO_ is the repository name):  
    ```
    github-backup --all --pull-details --prefer-ssh --repository REPO REPO-OWNER -u mhucka
    ```
2. I changed directory to `repositories` (where `github-backup` writes its output) and ran `zip -r` to create a single-file ZIP archive of the files written by `github-backup`.

The following is a list of the origins of the repository backups found here and the dates they were produced:

* [seurtem/ocrd_typegroups_classifier](https://github.com/seurtem/ocrd_typegroups_classifier) was produced on 2020-07-07 

* [seurtem/typegroups-classification-projection](https://github.com/seurtem/typegroups-classification-projection) was produced on 2020-07-07 

* [seurtem/printed-vs-handwritten](https://github.com/seurtem/printed-vs-handwritten) was produced on 2020-07-07 

