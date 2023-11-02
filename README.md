# azure-integration-demo
a sample of how to integrate using azure cloud integration services

## workflow

- patient sent sms with link to web form

### questionare
- patient checks and confirms details
- answers questions regarding allergies
- picks appointment time

- doctor is sent message with patient name and appointment time
- kitchen is sent allergy information

## TO DO

[ ] Next JS web form for patient detials
[ ] logic app for saving form details to message bus
[ ] message bus sends to event bus
[ ] event bus has topics for appointment by clinic, demographic details and allergy details updated 
[ ] event bus sends events to logic app for sms to doctor
[ ] event bus sends event to kitchen


