# automatic-irrigation-system
 SpringBoot application that automates the irrigation of land plots
A SpringBoot application that automates the irrigation of land plots. The Application works as the following:
1-Admin adds land plot with the time slot of when its first irrigation will start
2-With every call to irrigate, the land plot's time slot will be updated to its next irrigation time slot
3-The time slot is updated with respect to the first time slot, not current time

Testing
Integration Tests are implemented using Jupiter(Junit 5) library
