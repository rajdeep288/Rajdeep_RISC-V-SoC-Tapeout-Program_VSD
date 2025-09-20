## **VSD RISCV SoC Tapeout Program**

 Week 0:  Tool Setup

### **Tools Installation**

**All the instructions for installation of required tools can be found here:**

**System Requirements**

- 6 GB RAM
- 50 GB HDD
- Ubuntu 20.04 or higher
- 4 vCPU

**TOOL CHECK**

### **🧠 1. Yosys – RTL Synthesis Tool**

**✅ Yosys Installation**

```bash
# Clone the Yosys repository
git clone <https://github.com/YosysHQ/yosys.git>
cd yosys

# Install required dependencies
sudo apt update
sudo apt install make
sudo apt-get install build-essential clang bison flex \\
    libreadline-dev gawk tcl-dev libffi-dev git \\
    graphviz xdot pkg-config python3 libboost-system-dev \\
    libboost-python-dev libboost-filesystem-dev zlib1g-dev

# Initialize submodules (for abc directory)
git submodule update --init --recursive

# Build and install Yosys
make
sudo make install

```

**Installation Verification**

![image.png](images/yosys_installation_completed.png)

## **2.Iverilog**

```bash
$ sudo apt-get update 
$ sudo apt-get install iverilog
```

**Installation Verification**

![image.png](images/iverilog_installation_completed.png)

### **3.gtkwave**

```bash
$ sudo apt-get update
$ sudo apt install gtkwave
```

**Installation Verification**

![image.png](images/gtkwave_installation_completed.png)
