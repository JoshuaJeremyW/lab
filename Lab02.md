# Lab02A - Windows VM CPU and Memory Analysis Report

**Student Name:** [Your Full Name]  
**Student ID:** [Your Student ID]  
**Course Section:** [Your Section Number]  
**Completion Date:** [YYYY-MM-DD]  
**Lab Duration:** [Actual time taken]

---

## Part 1: Virtual Machine Setup and Configuration

### 1.1 VM Configuration Summary
- **Hypervisor Name:** win10-jwilliams137
- **Hypervisor Version:** [Version number]
- **CPU Cores:** 2
- **Memory:** 4096 MB
- **Storage:** Hard disk capacity :60 GB Current used:33 GB 
- **Network:** NAT

### 1.2 VM Import and Startup Process
- **VM File Source:** [\\mydrive\courses\SPR100\Win10]
- **Import Method:** Downloaded win_nov22.ova to SSD file amd imported it into vmware.
- **VM Name:** win-10jwilliams137
- **Storage Path:** D:\SPR100-VM\win10-jwilliams137.vmdk
- **Startup Time:** 15 seconds

### 1.3 Initial System Configuration
- **Password Change Process:** [Describe how you changed the Student account password] 
- **Git Installation:** [Describe the Git for Windows installation process using winget]

---

## Part 2: Windows System Analysis

### 2.1 CPU Analysis Results

#### System Information (msinfo32)
- **Processor Name:** AMD Ryzen 7 7730U with Radeon Graphics
- **Number of Cores:** 2
- **Logical Processors:** 2

#### Task Manager CPU Analysis
- **Current CPU Utilization:** 2%
- **Number of Virtual Processors:** 2
- **CPU Base Speed:** 2.00 GHz
- **CPU Current Speed:** [Current operating speed from Task Manager]
- **System Up Time:** 0:01:30:02
- **CPU Utilization Observations:** Obsereved occasonial spikes in CPU utilization.

### 2.2 Memory Analysis Results

#### System Information Memory Details
- **Total Physical Memory:** 4
- **Available Physical Memory:** 2.06 GB 
- **Total Virtual Memory:** 4 GB
- **Available Virtual Memory:** 3.43 GB
- **Virtual Memory Explanation:** [Explain what Total and Available Virtual Memory means in your own words]

#### PowerShell Memory Commands Output
**Physical Memory Information:**
__GENUS              : 2
__CLASS              : Win32_PhysicalMemory
__SUPERCLASS         : CIM_PhysicalMemory
__DYNASTY            : CIM_ManagedSystemElement
__RELPATH            : Win32_PhysicalMemory.Tag="Physical Memory 0"
__PROPERTY_COUNT     : 36
__DERIVATION         : {CIM_PhysicalMemory, CIM_Chip,
                       CIM_PhysicalComponent, CIM_PhysicalElement...}
__SERVER             : DESKTOP-4H9E4CT
__NAMESPACE          : root\cimv2
__PATH               : \\DESKTOP-4H9E4CT\root\cimv2:Win32_PhysicalMemor
                       y.Tag="Physical Memory 0"
Attributes           : 0
BankLabel            : RAM slot #0
Capacity             : 4294967296
Caption              : Physical Memory
ConfiguredClockSpeed : 4800
ConfiguredVoltage    :
CreationClassName    : Win32_PhysicalMemory
DataWidth            : 64
Description          : Physical Memory
DeviceLocator        : RAM slot #0
FormFactor           : 8
HotSwappable         :
InstallDate          :
InterleaveDataDepth  :
InterleavePosition   :
Manufacturer         : VMware Virtual RAM
MaxVoltage           :
MemoryType           : 2
MinVoltage           :
Model                :
Name                 : Physical Memory
OtherIdentifyingInfo :
PartNumber           : VMW-4096MB
PositionInRow        :
PoweredOn            :
Removable            :
Replaceable          :
SerialNumber         : 00000001
SKU                  :
SMBIOSMemoryType     : 3
Speed                :
Status               :
Tag                  : Physical Memory 0
TotalWidth           : 64
TypeDetail           : 128
Version              :
PSComputerName       : DESKTOP-4H9E4CT

- **Document:** __PATH and Capacity values from the output
**__PATH** \\DESKTOP-4H9E4CT\root\cimv2:Win32_PhysicalMemory.Tag="Physical Memory 0"
**Capacity** 4294967296
**Available Memory Information:**
\\desktop-4h9e4ct\memory\available mbytes : 2169
- **Available Memory:** [Document the Available MBytes value]

### 2.3 System Performance Monitoring Results

#### Performance Monitor Data Collector Set
- **Data Collector Set Name:** Lab02A_Performance_Monitoring
- **Sample Interval:** 5 seconds
- **Duration:** [Recorded duration of the monitoring]
- **Counters Monitored:**
  - Processor: % Processor Time
  - Memory: Available MBytes
  - Physical Disk: % Disk Time
- **Log Location:** [C:\Users\Student\Documents or your chosen location]

#### Performance Data Summary
- **CPU Usage Range:** [Minimum - Maximum % during 2-minute monitoring]
- **Memory Available Range:** [Minimum - Maximum MB during monitoring]
- **Disk Usage Range:** [Minimum - Maximum % during monitoring]
- **Performance Patterns Observed:** [Describe any patterns, spikes, or notable changes]

#### Resource Monitor Observations
- **Peak CPU Usage:** 3%
- **Peak Memory Usage:** 50%
- **Resource Usage During Activities:** CPU, Disk, and memory all spiked.

#### Performance Monitor Data Collector Graph
[Put your `performance_chart.gif` image here]
- **How You Extracted:** [Describe how you moved the file from VM to host]

---

## Analysis and Conclusions

### Key Findings
1. **VM Configuration:** [Summarize your VM setup experience and final configuration]
2. **CPU Performance:** [Summarize what you learned about the CPU specifications and performance]
3. **Memory Management:** [Summarize memory analysis findings and understanding of virtual vs physical memory]
4. **Performance Monitoring:** [Summarize insights from performance monitoring tools]

### Technical Insights
- **System Architecture Understanding:** [What did you learn about CPU cores, logical processors, and memory hierarchy?]
- **Virtualization Concepts:** [What did you learn about VM configuration and resource allocation?]
- **Performance Monitoring Tools:** [What did you learn about Windows performance monitoring capabilities?]
- **PowerShell Commands:** [What did you learn about using PowerShell for system analysis?]

### Challenges and Solutions
- **VM Setup Challenges:** [Any difficulties with VM import, configuration, or resource allocation]
- **Performance Monitoring Issues:** [Any problems with data collector sets or performance tools]
- **File Transfer Challenges:** [How did you solve moving files between VM and host?]
- **Solutions Applied:** [How did you resolve any challenges encountered?]
- **Lessons Learned:** [What would you do differently next time?]

### Understanding Questions
- **Virtual Memory Concept:** [Explain in your own words what virtual memory is and why it's important]
- **VM Resource Allocation:** [Explain how VM resource allocation affects performance]
- **Performance Monitoring Value:** [Explain why performance monitoring is important in system administration]

---

**Report Completion Time:** [Total time spent on lab]  
**Confidence Level:** [Rate your understanding 1-10]  
