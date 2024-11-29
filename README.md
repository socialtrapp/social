# Social App Systems

### ID Types
+ 10 - User Id
+ 11 - Channel Id
+ 12 - Message Id
+ 13 - Server Id
+ 14 - Category Id
+ 15 - Role Id

### ID System
id(20) = idType(2) + unixTimestamp(10) + millisecond(4) + randomNumber(4)

### Account Badge Ranking
+ 1 - Social Founder
+ 2 - Social Director
+ 3 - Social Team
+ 4 - Social Team Moderator
+ 5 - Social Team Developer
+ 6 - Social Team Designer
+ 7 - Bug Hunter
+ 8 - Premium Subscriber
+ 9 - Early Supporter

### Account Status Types
+ 0 - Offline
+ 1 - Active
+ 2 - Idle
+ 3 - Do Not Disturb
+ 4 - In Game
  
### Error Types
|Error Code|Error Description|
|----------|-----------------|
|**s101**|Unknown error|
|**s102**|Database query error|
|**s103**|Database error|
|**cs101**|Token is required|
|**cs102**|User id(s) are required|
|**cs103**|User id and token are required|
|**cs104**|Token is not matching with user id **(Suspicious Situation!)**|
|**cs105**|Invalid token|
