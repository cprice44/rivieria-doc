What Computing Resources are Available?
========================================

Disc over Your System Resources
-------------------------------
.. tabs::

   .. tab:: Linux
      To check available resources on a Linux system, try running the following commands in your terminal:

      - **CPU Information:**
        
        ::
        
           lscpu

      - **Memory Usage:**
        
        ::
        
           free -h

      - **Disk Usage:**
        
        ::
        
           df -h

      - **Process Overview:**
        
        ::
        
           top


   .. tab:: Windows
      On Windows, you can discover system resources using these commands in Command Prompt or PowerShell:

      - **System Information:**
        
        ::
        
           systeminfo

      - **CPU Details:**
        
        ::
        
           wmic cpu get name,NumberOfCores,NumberOfLogicalProcessors

      - **Comprehensive System Info (PowerShell):**
        
        ::
        
           Get-ComputerInfo


   .. tab:: MacOS
      For MacOS systems, use these Terminal commands to view your system resources:

      - **Hardware Overview:**
        
        ::
        
           system_profiler SPHardwareDataType

      - **Current Resource Usage:**
        
        ::
        
           top -l 1

      - **CPU Model:**
        
        ::
        
           sysctl -n machdep.cpu.brand_string