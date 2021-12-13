## Welcome to Lumerical Manualbook for TU Eindhoven

> update on 26.11/2021
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
Because of the update of the ANSYS support system, the specific web pages will be different. The details are subject to ANSYS. 


#### 2.1 Ansys Learning Forum (ALF)
URL: <https://forum.ansys.com/categories/photonics>
![Photonics Forum](https://i.imgur.com/eUA6mQw.png)

Lumerical Knowledge Exchange (KX) has moved to the Ansys Learning Forum (ALF) on April 16, 2021.

Here you can communicate with ANSYS employees for any questions about the use of the software, whether it is technical or software function questions, you can put them on the forum. A key difference between ALF and KX is that Ansys employees (including the Lumerical team) are not permitted to download any attachments (learn more here). Screenshots are recommended if you want feedback on the settings in your project files.

The following is a list of classic Q&As listed by ANSYS employee [gsun](https://forum.ansys.com/profile/gsun):
<https://forum.ansys.com/discussion/34217/index-of-ansys-insight-posts-english-forum#latest>

The following is a list of classic FAQs about installation and use listed by ANSYS employee [Lito](https://forum.ansys.com/profile/Lito)
<https://forum.ansys.com/discussion/33561/ansys-insight-faqs-lumerical-user-support-resources-install-and-licensing#latest>


#### 2.2 Application Gallery (APP)
URL: <https://support.lumerical.com/hc/en-us#app-anchor>
![APPs](https://i.imgur.com/vlHSCnU.png)

Here are some models of commonly used devices, most of the devices have matching tutorials, which can help you better understand and use Lumerical.

![](https://i.imgur.com/iXNKDlY.png)

#### 2.3  Ansys Innovation Courses (AIC) / Lumerical University (EDU) 

URL: <https://courses.ansys.com/index.php/learning-tracks/?course_catid=1483>

Lumerical University (EDU) has moved to the Ansys Innovation Courses (AIC) platform. AIC hosts a wide range of free, online physics and engineering courses, as well as Ansys product training courses. AIC courses are available to everyone.

![AIC](https://i.imgur.com/9krKrBc.png)

Lumerical University was shut down on Sept 27, 2021. Your course progress and grades reports have been deleted with the shutdown.

Some quick links to Lumerical's product training learning tracks in AIC:

EME <https://courses.ansys.com/index.php/courses/ansys-lumerical-eme/>

FDE <https://courses.ansys.com/index.php/courses/lumerical-fde/>

FDTD <https://courses.ansys.com/index.php/courses/ansys-lumerical-fdtd/>

varFDTD <https://courses.ansys.com/index.php/courses/ansys-lumerical-varfdtd/>

Scripting <https://courses.ansys.com/index.php/courses/ansys-lumerical-scripting/> 

**Early learning can create models in lumerical for simulation and analysis. For more precise control of variables and subsequent optimization, script commands are very important. After learning the basic solver course, script commands need to be emphatically understood.**

#### 2.4. Knowledge Base (KB)
URL: <https://support.lumerical.com/hc/en-us#kb-anchor>

Here is the theoretical library of Lumerical software. The numerical methods and brief examples used by each solver can be found here. The theories used in the corresponding modules and the realization principles of each function in the software are all enumerated in detail and classified in KB.

![](https://i.imgur.com/L0ZKRDZ.png)
![](https://i.imgur.com/562grK4.png)

### 3. DEVICE Suite
DEVICE Suite: <https://support.lumerical.com/hc/en-us/categories/360001618153-DEVICE-Suite>
![](https://i.imgur.com/DfsEdJu.png)

#### 3.1 FDTD

FDTD Course <https://courses.ansys.com/index.php/courses/ansys-lumerical-fdtd/>

![](https://i.imgur.com/cRKtwJY.png)

The figure above is a view of the FDTD module. An FDTD window only needs to consist of the following price areas:

> + 1: Menu bar
> + 2: Commonly used operating areas, focusing on materials, structures, and simulation parts
> + 3: object tree
> + 4: Quick operations, such as zoom, copy and paste, etc.
> + 5: Simulation result area, the data will be displayed in this area after the simulation runs
> + 6: Command area, you can directly enter commands, and software errors are also displayed here
> + 7: Optimize the command area
> + 8: Script editor
> + 9: Model view display area

![](https://i.imgur.com/TRwgFWe.png) 
![](https://i.imgur.com/4h0GC1G.png)


The computer resources need to be configured before simulation. For details, please refer to this article: https://support.lumerical.com/hc/en-us/articles/360025161033-Compute-resource-configuration-use-cases

It should be noted that on the Windows operating system, Microsoft MPI or Intel MPI is recommended. When the server has a large number of cores, it is recommended to use Intel MPI (Intel CPU only). Microsoft MPI cannot identify the number of cores errorless.

##### 3.1.X Examples

#### 3.2 MODE
EME Course <https://courses.ansys.com/index.php/courses/ansys-lumerical-eme/>

FDE Course <https://courses.ansys.com/index.php/courses/lumerical-fde/>

varFDTD Course <https://courses.ansys.com/index.php/courses/ansys-lumerical-varfdtd/>

![](https://i.imgur.com/2nNZhBb.png)

The MODE module window is similar to the FDTD module window. The difference is that the solver is different. Under varFDTD, you can select different light sources and add different simulators. Under FDE/EME, these are not available.

##### 3.2.X Examples



### 4. System Suite





### 5. Scripting Language

#### 5.1 Lumerical University

#### 5.2 Scripting language - Category Listed (updating)



### 6. Tool integrations

#### 6.1 MATLAB

#### 6.2 More Software


### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
