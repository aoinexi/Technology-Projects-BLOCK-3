# Understanding File Permissions

## Task 1 --- Create a File

Run:

    touch secret.txt
    ls -l secret.txt

### Screenshot

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/4ee1be58-5ed7-4bb6-b048-6193c5bbced5" />


### Questions

1.  Who owns the file? Codingcomets
2.  What are the default permissions? Permissions to read, write, and edit the file.

### Reflection

Why is file ownership important in Linux systems?
To prevent important files by being edited or tampered by other users that do not have the right privelages.
------------------------------------------------------------------------

## Task 2 --- Restrict File Permissions

Run:

    chmod 600 secret.txt
    ls -l secret.txt

### Screenshot

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/dccdcaec-5a85-4d0a-a09f-4bd5f96e37c2" />


### Questions

1.  Who can read the file now? Codingcomets
2.  Who cannot access it? Other users that are not codingcomets


------------------------------------------------------------------------

## Task 3 --- Open Permissions (Security Risk)

Run:

    chmod 777 secret.txt
    ls -l secret.txt

### Screenshot

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/b3cc4ae0-143e-487f-80c6-0c44bcdb587e" />


### Questions

1.  Who can access the file now? Every user in the system
2.  Why might this configuration be dangerous? It allows for sensitive or important files to be tampered with by any user.

