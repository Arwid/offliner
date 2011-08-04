# Offliner

Copy over pouchdb.js with the latest code:

	cd www && rm pouchdb.js && wget https://github.com/mikeal/pouchdb/blob/master/idb.js -o pouchdb.js

Alternatively, you can replace the pouchdb link to point to your local copy:

	ln -sf ~/Code/pouchdb/idb.js www/pouchdb.js

	//If you don't have pouchdb, create a clone:
	
	cd ~/Code && git clone https://github.com/mikeal/pouchdb.git