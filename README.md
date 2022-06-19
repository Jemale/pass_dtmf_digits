# pass_dtmf_digits
This python script will dial a number and pass the DTMF digits to the remote end.

# @jlockett modifications
I took this script and just used the parts necessary to answer a call and return
a single digit. This was specifically to answer guests to my apartment.


# ToDo
1. Dockerize script or just make service
2. Remove unneeded parts
3. Maybe add security code
4. Maybe just move this to arduino
5. Add parameter for num rings til answer
6. Make a status page to show status of service
7. Rename this to doorman
8. Add logging

# Idea
Could have person test / im some other service running on device
That service will then start this auto-door-answer script
Makes it such that other people aren't confused by door just opening
if they call
