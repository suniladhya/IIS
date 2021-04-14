# IIS

## Anonymous Authentication: (Allows users to access public area of Website without asking for a username and a password)
1. By default IIS APPPOOL\web2.com is used by the IIS to access the Application

## Anonymous Authentication with Impersonation
1. Built in Windows Authentication -> IUSR is used to accomplish this authentication.
2. Application Pool Identity should run in "Classic" in Pipepleine mode
3. Website -> Authentication ->  Anonymous Authentication -> Enabled

## Windows Authentication
1. App Pool -> Advanced Setting -> Same Domain Identity
2. Website -> Authentication ->  Windows Authentication -> Enabled(others disabled)
7. Anonymous Authentication -> Enabled
8. Authentication -> ASP .Net Impersonation ->  
