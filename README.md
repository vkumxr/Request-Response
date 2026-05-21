# Modbus RTU Operations

For CRC, Modbus sends the lower byte first and then the upper byte.

---

# Procedure

1. Create request bytes  
2. Calculate CRC  
3. Append CRC  
4. Simulate response  
5. Convert to hex/string  
6. Display/log output  

---

# Operations

## Read Operations

- FC01 – Read Coils  
- FC02 – Read Discrete Inputs  
- FC03 – Read Holding Registers  
- FC04 – Read Input Registers  

## Write Operations

- FC05 – Write Single Coil  
- FC06 – Write Single Register  
- FC15 – Write Multiple Coils  
- FC16 – Write Multiple Registers  
