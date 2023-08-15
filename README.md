# Data-Engineering1

Assignment Data Engineering

1. Convert All the columns names to this format:- firstword_secondword. Ex: User ID -> user_id.
2. Remove @ from “Username”  column Ex:  @adventureSeeker -> adventureSeeker
3. Derive the “Post ID” column data from “Post URL” by picking the number after last “/” Ex: http://instagram.com/adventureSeeker/82036 -> 82036.
4. Create a new column called “post_date” and derive it from “Post Timestamp”. 
5. Create a new column called “total_engagement” and derive it from the sum of “Likes/Reactions” + “Comments” + Shares/Retweets.
6. Create a new column called “account_verification” and derive it from “User Followers” column(logic:- if the count is 400 or more fill the value with “verified” else “unverified”)
7. Create a new column called “accessibility” and deserve it from “Privacy Settings” column (logic:- if the value is public fit the value with “accessible” else fill with “inaccessible”.

Note:- 
1. Use Python + pandas or python + pyspark for the transformation.
2. Write clean python code with necessary comments.
3. You can use whatever resources on the internet to  solve the problems.
