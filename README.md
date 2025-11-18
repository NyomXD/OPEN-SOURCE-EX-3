# OPEN-SOURCE-EX-3
# AIM:
To create user accounts and groups in a Linux system, assign appropriate group memberships, restrict shell access for a specific user, and set passwords for all created users.
# PROCEDURE
1. Start by logging into the Linux system with administrative (root) privileges.
2. Create a new group named “admin”.
3. Create a new user named “harry”.
4. Assign “harry” to the “admin” group as a secondary group (primary group remains default).
5. Create another user named “Natasha”.
6. Assign “Natasha” to the “admin” group as a secondary group.
7. Create a third user named “sarah”.
8. Configure sarah’s account so that she does not have access to an interactive shell (assign a non-interactive shell).
9. Ensure sarah is not added to the admin group.
10. Set the password “redhat” for all three users: harry, Natasha, and sarah.
    
# Output

<img width="737" height="499" alt="Screenshot 2025-11-13 111943" src="https://github.com/user-attachments/assets/dc5a5af2-c3f1-4ae8-bbcf-ea0fe91e74b1" />

<img width="737" height="181" alt="Screenshot 2025-11-13 112104" src="https://github.com/user-attachments/assets/ea441b82-29d9-49c1-9e10-8a83da9c0a14" />

# Result

The group admin was successfully created.
The users harry and Natasha were created and added to the admin group as secondary members.
The user sarah was created without interactive shell access and was not added to the admin group.
A common password redhat was set for all three users.
