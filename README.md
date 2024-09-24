# Social App Systems

### ID Types
+ 10 - User Id
+ 11 - DM Id
+ 12 - Message Id

### ID System
id(16) = idType(2) + unixTimestamp(10) + randomNumber(4)

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

### Friend Value Types
+ 0 - No Friend
+ 1 - Friend
+ 2 - Pending
+ 3 - Accept Decline
+ 4 - Remove Friend

### Error Types
+ s101 - Database query error
+ cs101 - Token is required
+ cs102 - User id(s) are required
+ cs103 - Token is not matching with user id (Suspicious Situation!)
