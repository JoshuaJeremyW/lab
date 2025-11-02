# Lab02A - Windows VM CPU and Memory Analysis Report

**Student Name:** [Your Full Name]  
**Student ID:** [Your Student ID]  
**Course Section:** [Your Section Number]  
**Completion Date:** [YYYY-MM-DD]  
**Lab Duration:** [Actual time taken]

---

## Part 1: Virtual Machine Setup and Configuration

### 1.1 VM Configuration Summary
- **Hypervisor Name:** [VMware Workstation Pro]
- **Hypervisor Version:** [Version number]
- **CPU Cores:** [Number of CPU cores allocated to this VM]
- **Memory:** [Memory (RAM) allocated]
- **Storage:** [Hard disk capacity and current used hard disk size]
- **Network:** [Network connection type]

### 1.2 VM Import and Startup Process
- **VM File Source:** [\\mydrive\courses\SPR100\Win10]
- **Import Method:** [Describe how you imported win_nov22.ova]
- **VM Name:** [win10-[your username]]
- **Storage Path:** [Path on your external SSD drive]
- **Startup Time:** [Time from power-on to login screen]

### 1.3 Initial System Configuration
- **Password Change Process:** [Describe how you changed the Student account password]
- **Git Installation:** [Describe the Git for Windows installation process using winget]

---

## Part 2: Windows System Analysis

### 2.1 CPU Analysis Results

#### System Information (msinfo32)
- **Processor Name:** [Full processor name from System Summary]
- **Number of Cores:** [Physical cores from Processor section]
- **Logical Processors:** [Total logical processors from Processor section]

#### Task Manager CPU Analysis
- **Current CPU Utilization:** [Percentage from Performance tab]
- **Number of Virtual Processors:** [Count from Task Manager]
- **CPU Base Speed:** [Base speed from Task Manager]
- **CPU Current Speed:** [Current operating speed from Task Manager]
- **System Up Time:** [How long the OS has been running]
- **CPU Utilization Observations:** [Describe what you observed during monitoring]

### 2.2 Memory Analysis Results

#### System Information Memory Details
- **Total Physical Memory:** [Amount from msinfo32 System Summary]
- **Available Physical Memory:** [Amount from msinfo32 System Summary]
- **Total Virtual Memory:** [Amount from msinfo32 System Summary]
- **Available Virtual Memory:** [Amount from msinfo32 System Summary]
- **Virtual Memory Explanation:** [Explain what Total and Available Virtual Memory means in your own words]

#### PowerShell Memory Commands Output
**Physical Memory Information:**[Paste the output of: Get-WmiObject -Class Win32_PhysicalMemory]

- **Document:** __PATH and Capacity values from the output

**Available Memory Information:**
[Paste the output of: Get-Counter "\Memory\Available MBytes"]
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
- **Peak CPU Usage:** [Highest observed percentage from resmon]
- **Peak Memory Usage:** [Highest observed usage from resmon]
- **Resource Usage During Activities:** [Describe what happened when you performed different tasks while monitoring]

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
