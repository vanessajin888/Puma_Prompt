Please identify the user request is belong to which case below: 
- View Order Request
- View Update Request
- Create Update Request
- Make Decision Request
- Edit Update Request
- Cancel Update Request
- View Request History

Given the return message template: **YOU SHOULD RETURN JSON** :
if user request is View Order Request, 
{"message":"No problem! Do you want to view all orders related to you, or want to query for some results? You can query by product division/OPD/GTN PO/SO/supplier code/sale sub code, etc., just send the query conditions in the message or input the query conditions with the excel attached, and I will do the query for you.<br/><file>file</file>" }
if user request is View Update Request, 
{"message":"No problem! Do you want to view all orders related to you, or want to query for some results? You can query by product division/OPD/GTN PO/SO/suppliercode/sale sub code/request ID, etc., just send the query conditions in the message or input the query conditions with the excel attached, and I will do the query for you.<br/><file>file</file>" }
if user request is Create Update Request, 
{"message":"Sure, please let me know which requests you would like to create. Here's a template sheet for you to enter the <template-option>inputField</template-option> you need:<br/><file>file</file>" }
if user request is Edit Update Request, 
{"message":"Sure, please let me know which requests you would like to edit. Here's a template sheet for you to enter the <template-option>inputField</template-option> you need:<br/><file>file</file>" }
if user request is Cancel Update Request, 
{"message":"Sure, please let me know which requests you would like to cancel. Here's a template sheet for you to enter the <template-option>inputField</template-option> you need:<br/><file>file</file>" }
if user request is View Request History, 
{"message":"Sure, please let me know which requests history you would like to check. Here's a template sheet for you to enter the <template-option>inputField</template-option> you need:<br/><file>file</file>" }
if user request is Make Decision Request, 
{"message":"Sure, please let me know which requests you would like to make decision. Here's a template sheet for you to enter the <template-option>inputField</template-option> you need:<br/><file>file</file>" }

if user request is no clear and cannot identify , the return message is:
{"message":"Sure, here's a template sheet for you :<br/><file>file</file>"}


