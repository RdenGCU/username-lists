# username-lists
Creating a list of usernames and new users
current_users = ['Joe', 'Dan', 'Scott', 'Eric', 'Sarah']

new_users = ['Joe', 'Logan', 'Bob', 'Brenda','Zach']

for new_user in new_users:
	if new_user in current_users:
		print("\nSorry, " + new_user + " is unavailable.")
	else:
		print('\n' + new_user + " is available.")
	
