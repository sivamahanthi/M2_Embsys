### 1.1 HIGH LEVEL TEST PLAN
* User Push Button Setpoint (25°C)
 
| Test ID |	Description |	Input |	Expected output |	Actual Output |	Passed Or Not |
|---------| ------------| ----- | ----------------| ------------- | --------------|
| 01 |	POT/Sensor |	Let sensor reads 20°C |	LED green heater ON |	LED green heater ON |	Pass |
| 02 |	POT/Sensor |	Let sensor reads 30°C |	LED red heater OFF  |	LED red heater OFF  |	Pass |
# Here below are the some of the unity test/ unity framework test plans there are so many but I have only mentiones some of the test cases here.
## 1.2 LOW LEVEL TEST PLAN
| Test ID(for LCD) |	Description |	Input |	Expected output |	Actual Output |	Passed Or Not |
| ---------------- | ------------ | ----- | --------------- | ------------- | ------------- |
| 01 |	Check for LCD_Char() |	P |	P |	P |	Pass |
| 02 |	Check for LCD_String() |	P |	P |	P |	Pass |
| 03 |	Check for LCD_String() |	Git |	Git |	Git |	Pass |

| Test ID (for ADC) |	Description |	Input |	Expected output |	Actual Output |	passed/not |
|-------------------| ----------- | ----- | --------------- | ------------- | ---------- |
| 01 |	Check for ADC_Read() |	0V |	0 |	0 | 	Pass |
| 02 |	Check for ADC_Read() |	5V |	1023 |	1023 |	Pass | 

|Test ID (for mapping, map) |	Description  |	Input |	Expected output |	Actual Output |	passed/not |
|-------------------------- | -----------  |  ----- | --------------- | ------------- | ---------- |
| 01 |	Check for map() |	map(20, 492, 478, 20, 35) |	525 |	525 |	Pass |
| 02 |	Check for map() |	map(25, 492, 478, 20, 35) |	520 |	520 |	Pass |
| 03 | Check for map() |	map(30, 492, 478, 20, 35) |	515 |	515 |	Pass |
| 04 | Check for map() |	map(35, 492, 478, 20, 35) |	509 |	509 |	Pass |
