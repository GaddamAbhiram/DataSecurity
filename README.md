***Clone the Repository***
1. Open your terminal and navigate to the directory where you want to clone the repository: **cd /path/to/your/directory**
2. Clone the repository: **git clone https://github.com/GaddamAbhiram/DataSecurity.git**
3. Navigate to the cloned directory: **cd DataSecurity**


<ins>***Level 1 Instructions***</ins>

**Prerequisites**

1. Ensure Python and pip are installed on your system:


Verify Python installation: **python --version   (or)    python3 --version**

Verify pip installation: **pip --version**


2. Install the Required Dependencies:

Run the following command to install the necessary libraries:  **pip install torch torchvision matplotlib**





**Running the Code:**

1. navigate to the directory containing level_1.py:  **cd /path/to/your/level_1.py**

2. Execute the script: **python level_1.py**


**Resolving SSL Errors**

If you encounter the following error:
<urlopen error [SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: unable to get local issuer certificate (_ssl.c:1000)>


Then do the following: 

Update Certificates on macOS: Run the following command in your terminal: **/Applications/Python\ 3.12/Install\ Certificates.command**. 

Replace 3.12 with your installed Python version (e.g., 3.11, 3.9).
Retry running the script: **python level_1.py**



<ins>***Level 2,3 Instructions :***<ins>

Similarly follow the same for level_2.py and level_3.py. If you have already executed Level 1, then just run python level_2.py or level_3.py. As the dependencies are installed while running Level 1.
If you haven’t executed Level 1, follow the Prerequisites and Running the Code steps mentioned above for Level 1, and then run the respective script.








