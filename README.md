# CRUD-check-wrapper-class
Simple util method to check fls and CURD permission by passing 



Define name space using

ORGNAMESPACE variable (Note:Dont add __ as suffix)

Supported ENUMS for CRUD Checks are

CrudPermision.CURDOpration.CREATE  (Insert perm)

CrudPermision.CURDOpration.MODIFY (Update perm)

CrudPermision.CURDOpration.READ (View perm)

CrudPermision.CURDOpration.REMOVE (Delete perm)


Example

1.Checking view permsion on Account object

    CrudPermision.checkCurd('Account',CrudPermision.CURDOpration.READ)
    
2.Checking Update permsion on contact object

    CrudPermision.checkCurd('SELECT LastName FROM Contact',CrudPermision.CURDOpration.READ)

