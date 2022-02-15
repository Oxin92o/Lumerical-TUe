## Welcome to Lumerical Manualbook for TU Eindhoven

> update on 01/2022
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

##### 3.1.2 Examples

The process of FDTD simulation is roughly defining the material, setting up the structure and FDTD simulation area, adding monitors to record data, and finally running the simulation. Before running a simulation, checks can be made to ensure that the material properties are accurately simulated and that the computer has sufficient memory to run the simulation. After a run, data can be collected from monitors and the results can be analyzed by plotting the data or performing additional post-processing using scripts. At the same time, performing a [convergence test](https://support.lumerical.com/hc/en-us/articles/360034915833-Convergence-testing) is also an important step to obtain high-accuracy results.

We take the simulation of back reflection as an example to explain the simulation process of FDTD.

1. First, two cuboids are established through Structure-Rectangle, one as the waveguide and the other as the base. The size of the waveguide is 200 nm in width and 800 nm in height, and the size of the substrate can be arbitrary, but it needs to be surrounded by the subsequent simulation area. ![](https://s2.loli.net/2022/02/15/IrUPadhV83qEwmu.png)
The final result is shown below:
![](https://s2.loli.net/2022/02/15/qZpm41vlGzNcQxH.png)


2. After right-clicking on the corresponding structure and Edit object, define the material on the Material tab. The waveguide material is Si and the base material is SiO2. 
![](https://s2.loli.net/2022/02/15/PsUj8iNz1ehwDdC.png)
![](https://s2.loli.net/2022/02/15/monUA6zukf721Ig.png)

3. Added FDTD simulation area and light source. The simulated region of the FDTD should be embedded in the structure so that a convergent result can be obtained. 
![](https://s2.loli.net/2022/02/15/jmRuoWCiO2Y4sK9.png)
At the same time, the BC condition is PML, which perfectly matches the layer, so the result obtained is closer to the reality.
![](https://s2.loli.net/2022/02/15/3841Z7D6fAFmnjk.png)
Add a mode light source along the X-axis with a wavelength of 1.55 microns.
![](https://s2.loli.net/2022/02/15/egydFSsfqj1DIvn.png)

4. Two monitors are placed in front of and behind the modal light source, and two simulators are placed in the immediate space, and four simulators are placed to receive the modal power in the space.
![](https://s2.loli.net/2022/02/15/zsM53drijhBHp8q.png)
![](https://s2.loli.net/2022/02/15/CUOrMV7aIGmjyKF.png)

5. Make sure that the mode light source is correct, and check the PC resources when it is sufficient for the simulation needs.
![](https://s2.loli.net/2022/02/15/6dupi4qIsjBRAy1.png)
![](https://s2.loli.net/2022/02/15/5vzfWod1ZYXjQKA.png)
![](https://s2.loli.net/2022/02/15/GCAsDHFyOVxeNQb.png)

6. After clicking RUN, wait for the simulation to end and observe whether the results converge.
![](https://s2.loli.net/2022/02/15/3z2OWNk4B8CKpcx.png)

7. Obtain and analyze simulation results through scripting tools.
   ```
   T = getresult("transmission","T");
   R = getresult("reflection","T");
   y1 = getresult("y1","T");
   y2 = getresult("y2","T");
   z1 = getresult("z1","T");
   z2 = getresult("z2","T");
   gIncidence = -y1.T + y2.T - z1.T + z2.T;
 
   #Display the confirmation
   ?"Transmitted power is " + num2str(T.T);
   ?"Reflected power is " + num2str(-R.T);
   ?"Unaccounted power at grazing incidence is " + num2str(gIncidence);
   ?"The total power in the system is " + num2str(T.T - R.T + gIncidence); 
   ```
   The transmitted power is 47.49%, the reflected power is 50.94%, and the other energy dissipated is 1.67%. Considering the error, it can be considered that the total energy is conserved in the simulation area.
   ![](https://s2.loli.net/2022/02/15/xgcpFQIruAisah1.png)

#### 3.2 MODE
EME Course <https://courses.ansys.com/index.php/courses/ansys-lumerical-eme/>

FDE Course <https://courses.ansys.com/index.php/courses/lumerical-fde/>

varFDTD Course <https://courses.ansys.com/index.php/courses/ansys-lumerical-varfdtd/>

![](https://i.imgur.com/2nNZhBb.png)

The MODE module window is similar to the FDTD module window. The difference is that the solver is different. Under varFDTD, you can select different light sources and add different simulators. Under FDE/EME, these are not available.

##### 3.2.2 Examples



### 4. System Suite
![](https://i.imgur.com/mWeBqNs.png)
[INTERCONNECT product reference manual](https://support.lumerical.com/hc/en-us/articles/360037304774)

The Interconnect Reference Manual provides detailed descriptions of the product and solver functionality. Interconnect is mainly used to build a complete system environment in Lumerical for overall system-level simulation during the designed independent period. Those who need it can visit the website for detailed information.



### 5. Scripting Language

#### 5.1 Lumerical University

Below is a link to Lumerical's official tutorial on Script. It is important to understand the relevant content of this section of Manipulating Variables. When defining the structure and performing data processing, Lumeircal is the corresponding command. After understanding the script, you can automate the simulation and data processing through the script.

https://support.lumerical.com/hc/en-us/sections/360007813714-SCRIPTING100-List-of-videos

![](https://s2.loli.net/2022/02/15/lNYLCZmQnqojA8p.png)

#### 5.2 Scripting language - Category Listed (updating)
Lumerical officially gives a list of all runnable commands, listed according to the initials and usage categories. Links are also given below for access.

[Lumerical scripting language - By category](https://support.lumerical.com/hc/en-us/articles/360037228834-Lumerical-scripting-language-By-category)
[Lumerical scripting language - Alphabetical list](https://support.lumerical.com/hc/en-us/articles/360034923553-Lumerical-scripting-language-Alphabetical-list)

##### 5.2.1 Examples

The following is an example of building a cube and getting the cube position parameters through script commands.
```
switchtolayout;
clc;

deleteall;
save("test");

addstructuregroup;
set("use relative coordinates",0);
set("name","group");
set("x",0);
set("y",0);
set("z",0);

set('script','
addrect;
set("use relative coordinates",0);
set("name","waveguide");
set("x min",2e-6);
set("x max",4e-6);
set("y",0);
set("y span",2e-6);
set("z",0);
set("z span",2e-6);
');

?getnamed("group::waveguide","x max");
```
The running result is shown as follows:
![](https://s2.loli.net/2022/02/15/Zl9kxEsRXdUjryS.png)


### 6. Tool integrations

#### 6.1 MATLAB
The MATLAB script integration feature allows calling MATLAB commands directly from Lumerical scripts. This provides access to MATLAB while working in the Lumerical environment and uses MATLAB's powerful analysis and visualization capabilities. 

[Once configured](https://support.lumerical.com/hc/en-us/articles/360026142074), Lumerical will launch MATLAB and create a connection between the two applications when the corresponding MATLAB function is called. Once the connection is established, you can transfer data from Lumerical to MATLAB (matlabput), transfer data from MATLAB to Lumerical (matlabget), and run MATLAB commands from the Lumerical script prompt (matlab).

The following will list several commonly used Matlab and Lumerical related script commands.

[matlab](https://support.lumerical.com/hc/en-us/articles/360034407974-matlab)
```
use MATLAB's "surf" command to make a surface plot of the real part of Ex

matlabput(x,y,Ex);
matlab("surf(y,x,real(Ex))");

```

[matlabget](https://support.lumerical.com/hc/en-us/articles/360034407994-matlabget)
```
The arguments to this command are one or more variable names that refer to variables in the MATLAB workspace.

This function does not return any data.
```

[matlabload](https://support.lumerical.com/hc/en-us/articles/360034408034-matlabload)
```
matlabload("myData.mat");  
```

[matlabput](https://support.lumerical.com/hc/en-us/articles/360034408014-matlabput)
```
The arguments to this command are one or more variable names that exist in the Lumerical variable workspace.

This function does not return any data.
```

[matlabsave](https://support.lumerical.com/hc/en-us/articles/360034928113-matlabsave)
```
x=1:10;
y=x^2;
matlabsave("x_squared_data", x, y);
```

[matlabsavelegacy](https://support.lumerical.com/hc/en-us/articles/360034928133-matlabsavelegacy)

#### 6.2 More Software
Lumerical lists all supported software, if you need it, you can visit the web page to check.
![](https://s2.loli.net/2022/02/15/ElsimNtbWQ1RyeS.png)

[Tool integration overview](https://support.lumerical.com/hc/en-us/articles/360037308014)

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
