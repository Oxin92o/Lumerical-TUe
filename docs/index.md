## Welcome to Lumerical Manualbook for TU Eindhoven

> update on 11/2021
> @ Hannover

### 1. Installation and Licensing

You  can also find more detailed information about this section from Lumerical official support website: https://support.lumerical.com/hc/en-us/categories/360001597473-Installation-Licensing

#### 1.1 Download installation files

If you already have the installation files of Lumerical, you can skip this part to next section. This part will mainly introduce how to download Lumerical installation files. 

Everyone can get 30-day free trail access of Lumerical after signing up to Ansys Lumerical. First, visiting [Lumerical Homepage](https://www.lumerical.com), then clicking top-right **"Login"** button to register an new account. After successful registration, you can log into your Ansys account.

Now, move back to [Lumerical Homepage](https://www.lumerical.com), click **“Evaluate for Free”** and you will be forward to trail download page. The website will automatically detect your operating system and directly give you the available download instruction, like the image shown below:

![Evaluate for Free](https://i.imgur.com/3ZV3fFl.png "Evaluate for Free")

Now, you already have an Ansys account, you can log in to your own account and download installation files  at any time. After visiting [Customer Downloads](https://www.lumerical.com/downloads/customer) website, you can find the latest Lumerical download link for all operating systems. In addition, you can also click on the **"Select a version"** button to switch to old version.

![Customer Downloads](https://i.imgur.com/xV4GGG9.png "Customer Downloads")

#### 1.2 Installation

According to the official description of Lumerical, only the following operating systems are officially supported and verified for operation (64-bit editions only):

> updated on 19.05.2021

+ Windows
  +  Windows® 10 (Professional, Enterprise & Education)	
  +  Windows Server® 2016, 2019 (Standard)

+ RedHat
  + RedHat® Enterprise 7 (7.6, 7.7 & 7.8)
  + RedHat® Enterprise 8 (8.1)

+ CentOS
  + CentOS® 7 (Community Enterprise OS 7.6, 7.7)
  + CentOS® 8 (Community Enterprise OS 8.1)

Lumerical software supports the following technologies:

+ Amazon EC2
+ Microsoft Azure
+ HPC network technologies including: Infiniband, Myrinet, Gb and 10Gb Ethernet
+ MPI frameworks: Microsoft MPI, MPICH, OpenMPI, IntelMPI and other commercial MPI distributions
+ HPC schedulers: SGE, PBS Pro, OpenPBS, Platform LSF, HTCondor, etc.

Lumerical software has limited support on other operating systems that are known to be compatible with the supported systems listed above (Red Hat) such as Fedora and Open SUSE. 

***Although Lumerical gave installation guide for Ubuntu, Debian based Linux distributions, like Ubuntu, Debian, Linux Mint, are not officially supported. Check more information [here](https://support.lumerical.com/hc/en-us/articles/1500005392522-Lumerical-installation-guide-on-Ubuntu).** 



##### 1.2.1 Windows

> Notes:
>
> + Administrator access is required.
>
> + Floating licenses must have the FlexNet license manager installed on one of the computer in the local network.

Lumerical product installation on Windows:

1. Open windows explorer and go to where you saved the downloaded zip file. 

2. Right click on the zip file and **“Extract All“**. 

3. Open the extracted folder and run **”Lumerical_Installer.exe“**. 

4. Click **”Install“** when prompted, to install the required MPI components.
   *The prompt only appears if the components are not found on your machine.*  

5. Choose the default options and click Next to complete the installation. 
   *Notes: Ansys SSO login exemption allows Lumerical to login into your Ansys account on "localhost:8096". Enabling the MPI firewall exemptions adds the rule to your firewall and allow running simulations using the bundled MPIs on localhost.*

6. Connect to License server.  Alternately, you may request a free 30-day evaluation license by logging in your account.   

   

##### 1.2.2 Linux

> Notes:
>
> + Administrator access is required.
> + Floating licenses must have the FlexNet license manager installed on one of the computer in the local network.

Lumerical product Installation on Linux:

1. Open terminal.

2. Change directory to the download location (*default, ~/Downloads*) and unpack the installation files.

   ```
   $ cd ~/Downloads
   $ tar -zxf Lumerical-[version].tar.gz
   ```

3. Installation on RHEL and CentOS
   *Note: The default installation process using the 'install.sh' script will install into the directory:

   ```
   /opt/lumerical/v211
   ```

4. Change directory to the extracted folder and run the install script with sudo access or as root. This will check your system and install any missing dependencies.

   ```
   $ cd ~/Downloads/Lumerical-[version]/
   $ sudo sh ./install.sh

5. Follow the directions on the screen and enter desired options to complete the installation.

6. Connect to your license server.

***Ubuntu and other Debian based Linux distributions are not officially supported. However Lumerical still gives installation guide. Check more information [here](https://support.lumerical.com/hc/en-us/articles/1500005392522-Lumerical-installation-guide-on-Ubuntu).** 

##### 1.2.3 macOS

> **End of Life**
> Support for Mac OS ended with Lumerical release 2020 R2. See this [article](https://forum.ansys.com/discussion/25625/2020-r2-release-notes#latest) for details. 

1. Change directory to the download location. 
2. Run the disk image file (.dmg) to mount the installer
3. Run the installation file (.pkg) and follow the instructions on the installation wizard. 
4. Select to Uninstall or Continue without uninstall, when prompted and complete the installation.
5. Connect to your License server.  Alternately, you may request a free 30-day evaluation license.  

#### 1.3 Licensing

Regarding software license and related questions, you need to contact [Dr. Yuqing Jiao](https://www.tue.nl/en/research/researchers/yuqing-jiao/) to obtain Lumerical license.



### 2. Lumerical Support

#### 2.1 Ansys Learning Forum (ALF)

#### 2.2 Application Gallery (APP)

#### 2.3 Knowledge Base (KB)

#### 2.4 Lumerical University (EDU) 

#### 2.5 Ideas Exchange (IX)



### 3. DEVICE Suite

#### 3.1 FDTD

##### 3.1.X Examples

#### 3.2 MODE

##### 3.2.X Examples



### 4. System Suite

#### 4.1 INTERCONNECT

##### 4.1.X Examples



### 5. Scripting Language

#### 5.1 Lumerical University

#### 5.2 Scripting language - Category Listed (updating)



### 6. Tool integrations

#### 6.1 MATLAB

#### 6.2 More Software


### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
