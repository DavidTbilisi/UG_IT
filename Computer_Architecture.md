### Open Questions

*Q1: Explain what are Northbridge and Southbridge chipsets and clarify the difference between them?*  
*Answer:*  
Northbridge - CPU; Southbridge - I/O  
*Description:* Northbridge connects the CPU to high-speed components; Southbridge handles I/O and peripherals.

*Q2: Describe what is the CPU Overclocking and Turbo-Boost and demonstrate the difference between them?*  
*Answer:*  
CPU overclocking is manual, while Turbo-Boost is automatic.  
*Description:* Overclocking increases CPU speed manually; Turbo-Boost adjusts CPU speed dynamically.

*Q3: Provide insight into single bus architecture and dual independent bus architecture and clarify the difference between them?*  
*Answer:*  
Single bus architecture uses one bus for all communications, dual independent bus separates data paths for performance.  
*Description:* Single bus handles all data flow together; dual bus separates memory and I/O data paths.

*Q4: Define what is Hyperthreading Technology and explain its difference with Multicore Technology?*  
*Answer:*  
Hyperthreading creates virtual cores; multicore involves multiple physical cores.  
*Description:* Hyperthreading simulates additional cores; multicore uses multiple actual cores.

*Q5: Suppose you have a CPU with the CPU multiplier value of 220 MHz and the Clock speed value of 3.3 GHz, determine the value of Bus speed?*  
*Answer:*  
Bus speed = 3.3 GHz / 220 = 15 MHz  
*Description:* The calculation shows how to determine bus speed using clock speed and multiplier.

*Q6: Elaborate what DIMM Data Path is*  
*Answer:*  
The data channels within a DIMM that transfer data to and from the memory controller.  
*Description:* DIMM data path is the route data takes within a memory module.

*Q7: Describe Accelerate Hub Architecture (AHA)*  
*Answer:*  
A modern design improving data transfer efficiency between CPU, memory, and other components.  
*Description:* AHA optimizes communication between CPU and other system parts.

*Q8: Expound upon Direct Media Interface (DMI)*  
*Answer:*  
A high-speed connection between the CPU and the chipset.  
*Description:* DMI facilitates efficient data transfer between the CPU and chipset.

*Q9: Which of the following statements best describes the difference between DDR RAM and non-DDR RAM?*  
*Answer:*  
DDR RAM has higher data transfer speeds and lower latency than non-DDR RAM.  
*Description:* DDR RAM is faster and more efficient than non-DDR RAM.

*Q10: Which of the following statements accurately distinguishes between SIMM (Single Inline Memory Module) and DIMM (Dual Inline Memory Module) RAM?*  
*Answer:*  
DIMM RAM modules have separate electrical contacts on each side, allowing for greater memory capacity.  
*Description:* DIMM provides higher capacity and bandwidth compared to SIMM.

*Q11: Which of the following best describes a RAM module?*  
*Answer:*  
A physical hardware component that provides temporary storage for data and instructions.  
*Description:* RAM is temporary storage for active data and instructions.

*Q12: Which of the following best describes the role of speed in RAM compared to SSDs and HDDs?*  
*Answer:*  
RAM is faster than both SSDs and HDDs, providing quick access to data for the CPU.  
*Description:* RAM offers the quickest access speed compared to other storage types.

*Q13: Illustrate what the RAM component is in a computer*  
*Answer:*  
RAM stores data temporarily and is faster than HDDs but loses data when powered off.  
*Description:* RAM is fast, temporary storage that clears when the computer shuts down.

*Q14: Outline what the CPU multiplier is*  
*Answer:*  
A factor that, when multiplied by the base clock speed, determines the CPU's clock speed.  
*Description:* CPU multiplier defines the overall clock speed based on the base speed.

### Tests

*Q15: Which of the following is not considered as a key processor specification?*  
*Answer:*  
Clock Watch  
*Description:* Clock Watch is not a key specification of a processor.

*Q16: Which option is correct regarding Dual Independent Bus Architecture?*  
*Answer:*  
One bus is dedicated to instructions, the other to data.  
*Description:* Dual buses separate instruction and data pathways.

*Q17: Which of the following options is not a part of dynamic execution approach within a CPU?*  
*Answer:*  
Superscalar Execution  
*Description:* Superscalar execution is not part of dynamic execution.

*Q18: Based on the explanation given below regarding the dynamic execution select the right approach refers to the mentioned sentence. “It's like organizing tasks based on what can be done at the same time. If you can wash dishes while waiting for water to boil, you save time.”*  
*Answer:*  
Dataflow Analysis  
*Description:* Dataflow analysis organizes simultaneous tasks efficiently.

*Q19: What is the function of a math coprocessor in a CPU?*  
*Answer:*  
To execute complex mathematical calculations  
*Description:* Math coprocessors handle advanced math operations.

*Q20: What are the stages involved in one complete execution cycle in a CPU?*  
*Answer:*  
Fetch, Decode, Execute, Memory Access, Write-back  
*Description:* The execution cycle consists of five main stages.

*Q21: What is the best description of CPU clock speed?*  
*Answer:*  
The number of complete execution cycles a CPU can perform per second.  
*Description:* Clock speed measures how fast the CPU operates.

*Q22: Which option do you think accurately describes Hyper-Threading technology and multiple-core technology?*  
*Answer:*  
Multiple cores refer to physical cores, Hyper-Threading creates virtual cores.  
*Description:* Hyper-Threading simulates additional cores, while multicore uses real ones.

*Q23: What is the best description of an Address Bus?*  
*Answer:*  
A set of wires used to transmit memory addresses between the CPU and the RAM.  
*Description:* The address bus carries memory addresses to and from the CPU.

*Q24: Which option is not considered as processor mode?*  
*Answer:*  
IA-32 Virtual Real Mode  
*Description:* IA-32 Virtual Real Mode is not a processor mode.

*Q25: What facilities are provided by the Hyperthreading technology (Two Correct Answers)?*  
*Answer:*  
Increases performance by allowing multiple threads to run on each core; Allows for better utilization of CPU resources  
*Description:* Hyperthreading enhances performance and resource usage.

*Q26: Northbridge and southbridge chipsets …?*  
*Answer:*  
Were traditional chipsets that do not exist in new motherboards  
*Description:* Older chipsets, no longer used in modern systems.

*Q27: Accelerated Hub Architecture …?*  
*Answer:*  
Is a modern chipset that helps to improve system performance and efficiency by optimizing data transfer between these components.  
*Description:* AHA optimizes data transfer in modern systems.

*Q28: What does the term "number of cores" refer to in a CPU?*  
*Answer:*  
The number of physical processors in the CPU  
*Description:* It refers to the count of physical processing units.

*Q29: What is System Management Mode (SMM) in a computer system?*  
*Answer:*  
A mode for managing system resources such as memory and CPU usage  
*Description:* SMM handles low-level system management tasks.

*Q30: Which statement accurately describes the role of Level 1 cache (L1) in a CPU?*  
*Answer:*  
L1 cache holds the most critical and frequently accessed data.  
*Description:* L1 cache stores the most important and frequently used data.

*Q31: What is Processor Manufacturing primarily concerned with?*  
*Answer:*  
Fabricating integrated circuits on silicon wafers focusing on maximizing performance and efficiency  
*Description:* It involves creating efficient, high-performance circuits.

*Q32: Based on the explanation given below regarding the dynamic execution select the right approach refers to the mentioned sentence.“Imagine starting a task before you're sure it's needed. If it turns out you do need it, you're already ahead, saving time and keeping things moving smoothly.”*  
*Answer:*  
Speculative Execution  
*Description:* Speculative execution predicts future tasks to save time.

*Q33: Which option do you think accurately describes Turbo Boost and Overclocking?*  
*Answer:*  
Turbo Boost is a feature implemented by CPU manufacturers that automatically and dynamically increases the clock speed’s default range when necessary, while overclocking is the manual process carried out by users to deliberately increase the clock speed of the CPU beyond its rated specifications.  
*Description:* Turbo Boost is automatic, overclocking is manual.

*Q34: What is the best description of a Data (I/O) Bus?*  
*Answer:*  
A communication pathway used to transfer data between the CPU, memory, and other peripheral devices.  
*Description:* The data bus transfers information between the CPU and peripherals.

*Q35: Which statement accurately describes the role of Level 3 cache (L3) in a CPU?*  
*Answer:*  
L3 cache acts as a larger pool of memory for data that is less frequently accessed by CPU cores, higher latency than L1 and L2 caches.  
*Description:* L3 cache provides additional memory for less critical data.

*Q36: Execution is a processor architecture that allows multiple instructions to be executed simultaneously. It has multiple execution units that can operate independently, enabling parallel execution of instructions and improved performance.*  
*Answer:*  
Dynamic Execution  
*Description:*

 Dynamic execution allows parallel processing of instructions.

*Q37: Based on the explanation given below regarding the dynamic execution select the right approach refers to the mentioned sentence. “It's like guessing which path you'll take while driving before you reach the intersection. By predicting which way you'll go, the system avoids delays.”*  
*Answer:*  
Speculative Execution  
*Description:* Speculative execution predicts future instructions to reduce delays.

*Q38: What does RAM clock cycle refer to?*  
*Answer:*  
The time it takes for a single operation (read or write) to be performed in RAM  
*Description:* RAM clock cycle measures the duration of a read/write operation.

*Q39: What does the term "DIMM data path" refer to?*  
*Answer:*  
Refers to the number of data lines used to transfer data to and from the DIMM module.  
*Description:* DIMM data path indicates the data transfer lines in a memory module.

*Q40: What sets SDRAM apart from traditional DRAM?*  
*Answer:*  
SDRAM uses a synchronous interface, while DRAM uses an asynchronous interface  
*Description:* SDRAM operates synchronously with the system clock, unlike DRAM.

*Q41: Which of the following are types of system buses found in computer systems?*  
*Answer:*  
Front Side Bus; Universal Serial Bus (USB)  
*Description:* Types of buses include the Front Side Bus and USB.

*Q42: What are BIOS and UEFI?*  
*Answer:*  
Firmware interfaces that initialize hardware during boot-up  
*Description:* BIOS and UEFI start hardware initialization at boot-up.

*Q43: What is the primary difference between UEFI and BIOS?*  
*Answer:*  
UEFI is more secure and offers advanced features like secure boot and secure firmware updates.  
*Description:* UEFI is an advanced, secure version of BIOS.

*Q44: What does Instruction Set Architecture (ISA) define in a computer system?*  
*Answer:*  
The set of instructions understood by the CPU  
*Description:* ISA defines the CPU's instruction set.

*Q45: What is the primary function of the Program Counter (PC) in a CPU?*  
*Answer:*  
Holds the address of the next instruction to be executed  
*Description:* The Program Counter tracks the next instruction address.

*Q46: What is the primary function of the status register in a CPU?*  
*Answer:*  
Holds flags that indicate the current state of the CPU, such as zero, carry, sign, overflow, etc.  
*Description:* Status register stores flags for the CPU's current state.

*Q47: What is the primary function of the Instruction Register (IR) in a CPU?*  
*Answer:*  
Stores the current instruction being executed  
*Description:* The Instruction Register holds the instruction currently being executed.

*Q48: What is the primary function of CMOS in a computer system?*  
*Answer:*  
Retains BIOS/UEFI settings when the computer is powered off  
*Description:* CMOS saves BIOS/UEFI settings when the system is off.

*Q49: What is the primary difference between PCI Express (PCIe) and PCI buses?*  
*Answer:*  
PCIe offers higher bandwidth and greater scalability than PCI  
*Description:* PCIe is faster and more scalable than PCI.

*Q50: What does PCI stand for in computer terminology?*  
*Answer:*  
Peripheral Component Interconnect  
*Description:* PCI stands for Peripheral Component Interconnect.
