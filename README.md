LAB 6
Nội dung: Hệ thống quản lý phiên bản trong làm việc nhóm

---updated2-----
Mục tiêu:
● Sử dụng thành thạo hệ thống quản lý phiên bản git trong làm việc nhóm. Đối
với bài lab này, khuyến khích SV làm việc theo nhóm.

Bài tập 1:

1. First, one person in the group should create a public repository using their
   GitHub account.
2. This same person should then follow the instructions from Github to add a
   remote, and then push their repository. Remember the -u flag, as suggested by
   GitHub.
3. All of the other members of the group should then be added as collaborators, so
   they can commit to the repository also.
4. Next, everyone else in the group should clone the repository from GitHub.
5. One of the group members who just cloned should now make a local commit,
   and then push it. Everyone should verify that when they pull, that commit is
   added to their local repository (use git log to check for it).
6. Look at each other’s git log output. Notice how the SHA-1 is the same for a
   given commit across every copy of the repository. Why is this important?
7. Two members of the group should now make a commit locally, and race to push
   it. To keep things simple, be sure to edit different files. What happens to the
   runner-up?
8. The runner-up should now pull. As a group, look at the output of the command.
   Additionally, look at the git log and notice that there is a merge commit. You
   may also wish to view the DAG in gitk.
