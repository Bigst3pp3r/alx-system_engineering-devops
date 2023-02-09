0. My name is betty - Create a script that switches the current user to the user betty: su betty
1. Who am i - Write a script that prints the effective username of the current user: whoami
2. Groups - Write a script that prints all the groups the current user is part of: groups
3. New owner - Write a script that changes the owner of the file hello to the user betty : sudo chown betty hello
4. Empty! - Write a script that creates an empty file called hello : touch hello
5. Execute - Write a script that adds execute permission to the owner of the file hello : chown 744 ./hello
6. Multiple permissions - Write a script that adds execute permission to the owner and the group owner, and read permission to other   users, to the file hello : chmod ug+x
