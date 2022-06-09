## Install free ModelSim  
Read https://vhdlwhiz.com/free-vhdl-simulator-alternatives/  


1. Download Questa*-Intel FPGA Edition and install starter edition  


2. Get your license    
   1. sign in / up [Intel® FPGA Self-Service Licensing Center](https://fpgasupport.intel.com/Licensing/license/index.html).  
   2. click **Sign up for Evaluation or Free Licenses**.  
   3. get NIC ID by running command: `/sbin/ifconfig` in terminal,  
    search the line **ether 12:34:56:78:9a** and remove the colons before pasting .
   5. Receive the license file per e-mail and save the file anywhere you want.


3. Set **LM_LICENSE_FILE** to the system environment (for me, it is ~/.profile file):   
   copy `export LM_LICENSE_FILE=/path to license folder/LR-084372_License.dat:$PATH` to your `~/.profile`


4. Run the vsim script to start ModelSim by running command:
    `~/intelFPGA/*.*/questa_fse/bin/vsim`
