# vikashdev
vikash development branch

#intial discussion


master_table
	id 		// 1
	name	// Karnataka
	description	// state description
	group  // state
	
city -
	city_id
	city_name
	state_id //1

locality -
	locality_id
	locality_name
	city_id
	
project -
	project_id
	project_name
	project_desc
	user_id
	
property -
	property_id
	property_name
	property_category // residential or commercial or agricultre
	property_type     // plot, flat, office_space , PG
	property_size
	unit_area // sqft or ft
	user_id
	project_id
	price
	adress
	description
images -
	image_id
	property_id
	image_path
user -
	user_id
	user_name
	user_type // owner, builder

credential_manager -
	user_id
	password(encrypted)
	

use case - 
	1. I will login to the system
		- user have to signup
		- user have to login
	2. I will post property
		- 
	

==============================================================


Controller -
	path http:\\google.com | localhost:8080\xyz\xy 
	method type - get or post or put or delete
	request body - request data / request paamaeter
	response - 
Service 
	BL
Dao
	DB access
