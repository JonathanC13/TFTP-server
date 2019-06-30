## TFTP-server - January 2016 – April 2016
https://github.com/JonathanC13/TFTP-server

Winter 2016 server side of a TFTP group project. Client and error simulator components are in friend repos that are unavailable.

Based on https://tools.ietf.org/html/rfc1350 protocol standards to create the server, like packet format and error handling.

## Description

-	Designed and developed the Server side of a Trivial File Transfer System based on the TFTP specifications found online and implemented design decisions made by the team. An example of a design decision if the server receives a write request to a file with a name that already exists on the server's directory then it replies with an error code 6 ; if the client wants to read and save to a file with a name that already exists in its directory then is will overwrite and continues the transfer until completion.

-	The testing method used was to have an error simulator in-between the client and server to alter packet contents to cause certain errors and/or simulate network errors.

-	Assisted team mates on their responsibilities relating to the client side, error simulator, diagrams, and documentation.

## End Remark

    The team had its ups and downs, but in the end I'm proud of what we were able to accomplish. 
    
    Thank you
    
    Jeremy Sawh
    Obinna Elobi
    Yan Liao
    Yash Patel
