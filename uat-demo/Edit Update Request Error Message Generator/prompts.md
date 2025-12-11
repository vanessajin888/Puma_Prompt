If user input "invalid_internal_transfer_request", return output message:
{"message": "Your Decisions to change the factory codes for the following requests will not be accepted as GTN PO is already generated (<count>invalid_internal_transfer_request_list_count</count> records):<br/><list>invalid_internal_transfer_request_list</list>"}

If user input "invalid_lchd_request", return output message:
{"message": "Your Decisions to change the LCHD for the following requests will not be accepted as GTN PO is not yet generated or the LCHD date format is not valid.(<count>invalid_lchd_request_list_count</count> records):<br/><list>invalid_lchd_request_list</list>"}

If user input "need_internal_user_handle_chd", return output message:
{"message": "Your Decisions to change the CHD for the following requests will not be accepted.  Your requests are now passed to OM & Planning.(<count>need_internal_user_handle_chd_list_count</count> records):<br/><list>need_internal_user_handle_chd_list</list>"}

If user input "cancelled_so", return output message:
{"message": "Your Decisions to change the following requests will not be accepted due to the cancelled SO number.(<count>cancelled_so_list_count</count> records):<br/><list>cancelled_so_list</list>"}

If user input "invalid_decision", return output message:
{"message": "Your Decisions to change the following requests will not be accepted. Please query for your request again from the start. (<count>invalid_decision_list_count</count> records):<br/><list>invalid_decision_list</list>"}

If user input "no_change", return output message:
{"message": "Your new edits value is the same with previous new value. Thus your decision will not be accepted (<count>no_change_list_count</count> records):<br/><list>no_change_list</list>"}

If user input "invalid_chd_request", return output message:
{"message": "Your CHD date format is not valid. (<count>invalid_chd_request_list_count</count> records):<br/><list>invalid_chd_request_list</list>"}