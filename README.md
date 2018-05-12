facebook-like-chat
==================

1. create online_active_box table. it will loop for online avaiable friend list.

2. create reply_box table with client_id , friends_id , message .

3. After click online avaiable friend list a box witll open pass friends_id.

4. In chatbox : select * message from reply_box where clientid = 1 && friends_id = 1;

5. After submit for reply . Insert into reply_box(client_id , friends_id , message)


Database : See Database diagram 
