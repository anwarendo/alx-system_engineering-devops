##### Scripts and their functions
      * 0-iam_betty ==> switches the current user to betty
      * 1-who_am_i ==> prints the current user
      * 2-groups ==> prints all the groups the current user is part of
      * 3-new_owner ==> changes file ownership of the file hello
      * 4-empty ==> creates empty file "hello"
      * 5-execute ==> gives execute access permission for the owner of the file
      * 6-multiple_permissions ==> gives permissions like: executing for owner and group, and reaing only for others
      * 7-everybody ==> give permissions for all types of users to execute the file "hello"
      * 8-James_Bond ==> give all permissions for others but not allow any access for the owner and the group owner
      * 9-John_Doe ==> will result in the permission mode -rwxr-x-wx for the file "hello"
      * 10-mirror_permissions ==> copies the permissions of olleh and give it to hello
      * 11-directories_permissions ==> recursively change directories only permissions
      * 12-directory_permissions ==> make directory with permissions specified from the beginning
      * 13-change_group ==> change group ownership of the file "hello" to school

      * 100-change_owner_and_group ==> changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
      * 101-symbolic_link_permissions ==> changes the owner and the group owner of _hello to vincent and staff respectively
      * 102-if_onyl ==> changes the owner of the file hello to betty only if it is owned by the user guillaume
      