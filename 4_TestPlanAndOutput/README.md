## Test Plan and Output
|Test ID|HLT ID|Description|Exp IN|Exp OUT|Actual OUT|PASS/FAIL|
|-------|------|-----------|------|-------|----------|---------|
|T_01|H_01|Provide required details for login to reserve a ticket|Password|Successfully logedin In|Successfully logedin In|Pass|
|T_02|H_01|When wrong password is entered|Password|Entered Password is wrong|Entered Password is wrong|Pass|
|T_03|H_02|Display the details of movie available|Enter Choice|Display list|Display list|Pass|
|T_04|H_02|Purchase a ticket for the movie available|Enter Choice|ThankYou for Reserving Ticket|ThankYou for Reserving Ticket|Pass|
|T_05|H_03|Summary of a ticket for purchased movie|Enter Choice|Reservation ID,Customer name,Show Name,Hallno,Price|Reservation ID,Customer name,Show Name,Hallno,Price|Pass|
|T_06|H_04|Cancel a ticket|ID Number|Your ticket is cancelled|Your ticket is cancelled|Pass|
|T_07|H_03|Change the price of ticket (only admin)|Password|Please enter new price|Please enter new price|Pass|
|T_08|H_03|Change the price of ticket after login (only admin)|Enter New Price-Price|Price Updated Successfully|Price Updated Successfully|Pass|
|T_09|H_03|When wrong password is entered while Changing the price of ticket (only admin)|Password|Entered Password is wrong|Entered Password is wrong|Pass|
|T_10|H_05|To view the reserved ticket|Password|Summary of ticket|Summary of ticket|Pass|
|T_11|H_05|When wrong password is entered to view the reserved ticket|Correct Password|Entered Password is wrong|Entered Password is wrong|Pass|
