# Compressor Status PCB
## Wemos D1 Mini Shield to monitor the A/C control signals.

My A/C has a two stage compressor.  The system should run on stage 1 the majority of the time and run on stage 2 when the
themostat detects a temperture delta at or greater than the programmed value.  Unfortunatly the thermostat doesn't report
what stage is engaged, only that the system is cooling. More importantly, the thermostat will cool beyond the temperature 
set point to lower the humidity in the house but it does not report this state to the cloud service.  Since I want to 
track when the A/C is running I had to find a creative way of monitoring the system. And this little project came to be.