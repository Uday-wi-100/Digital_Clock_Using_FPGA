# # Digital_Clock_Using_FPGA
digital clock is to display the time digitally using 7-segment display on FPGA Board. The digital clock by default displays the run time and time can be set by using time set assigned to switch on board.The digital clock designed is a 24-clock hour format. It displays the time in format of h2 h1 : m2 m1 : s2 s1 
# hours:minutes:seconds

# # Concept
To design a full digital clock first we designed clocks of different frequencies for minutes and hours. and maxing time clock can show is 23:59 so Using these clock, we implemented counter with following constrains:

Minute Unit-digit with clock of frequency 1/60 Hz, that counts from 0-9

Minute Tenth-digit with clock of frequency 1/600 Hz, that counts from 0-5

Hour Unit-digit with clock of frequency 1/3600 Hz, that counts from 0-3

Hour Tenth-digit with clock of frequency 1/36000 Hz, that counts from 0-2

For displaying these counter as decimal digits, we used 7 segment displays and implemented logic ac
