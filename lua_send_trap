-- Lua SNMP Traps via Net-SNMP

trapexe = "D:\\nsnmp\\usr\\bin\\snmptrap.exe"
mswitch = "-M"
mibpath = "D:\\nsnmp\\usr\\share\\snmp\\your_mib"
vswitch = "-v"
comver = "2c"
cswitch = "-c"
comstrg = "YOUR_STRING"
sendhost = "SEND_HOST"
dubquote = "''"
SomeString1 = "CustomString"
SomeString2 = "CustomString"
sswitch = "s"
SomeString3 = "CustomString"
iswitch = "i" 
SomeString4 = "CustomString"
sswitch = "s"
SomeString5 = "CustomString"
SomeString6 = "CustomString"

-- The below filter certian string values suitable for passing through the net-snmp .exe's

-- Messy_String1 = string.gsub(Messy_String1,'\n'," ") 

-- Messy_String2 = Messy_String2:gsub("%s+", "_")

-- Messy_String3 = Messy_String3:gsub(">", "greater_than")

-- Messy_String4 = Messy_String4:gsub("<", "less_than")

-- Below is the Lua Syntax to run the NetSNMP binaries with the vars we called up there. 

os.execute(
trapexe
.." "..mswitch
.." "..mibpath
.." "..vswitch
.." "..comver
.." "..cswitch
.." "..comstrg
.." "..sendhost
.." "..dubquote
.." "..SomeString1
.." "..SomeString2
.." "..sswitch
.." "..current_alarm
.." "..SomeString3
.." "..iswitch 
.." "..SomeString4
.." "..sswitch
.." "..SomeString5
.." "..sswitch
.." "..SomeString6)

-- Author = bbecomp99
