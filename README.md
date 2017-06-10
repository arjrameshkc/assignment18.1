# assignment18.1


create 'customer',{NAME => 'details'}, {SPLITS => ['ID','NAME','LOCATION','AGE'] }
put 'customer' 'rw1','details','id:1'
put 'customer' 'rw1','details','name:Amit'
put 'customer' 'rw1','details','location:IND'
put 'customer' 'rw1','details','age:18'
put 'customer' 'rw2','details','id:2'
put 'customer' 'rw2','details','name:Sumit'
put 'customer' 'rw2','details','location:PAK'
put 'customer' 'rw2','details','age:20'
put 'customer' 'rw3','details','id:3'
put 'customer' 'rw3','details','name:rohit'
put 'customer' 'rw3','details','location:AUS'
put 'customer' 'rw3','details','age:26'
put 'customer' 'rw4','details','id:4'
put 'customer' 'rw4','details','name:Namit'
put 'customer' 'rw4','details','location:UK'
put 'customer' 'rw4','details','age:24'
