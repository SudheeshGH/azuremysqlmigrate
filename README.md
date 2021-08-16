# Migrating Azure Databases for MySQLfrom One server to other

## How to Use the script azuremysqlmigrate.sh

* Download the scritp file  : **wget -L https://raw.githubusercontent.com/SudheeshGH/azuremysqlmigrate/main/azuremysqlmigfinal.sh**
* Download the parameter file : **wget -L https://raw.githubusercontent.com/SudheeshGH/azuremysqlmigrate/main/migrateparameter.json**
* Make the script Executable : **chmod +x azuremysqlmigfinal.sh**
* Edit the Parameter file and provide the migration details 
* Edit the *migrateparameter.json*  (Or create a paramater file with this template)
* Run the scripts : **./azuremysqlmigfinal.sh** *Parameterfilename*
> If you dont specify the parameter file name it will check the default file migrateparameter.json is same folder
