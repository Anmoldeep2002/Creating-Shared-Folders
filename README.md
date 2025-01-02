<h1>Creating Shared Folders</h1>


<h2>Description</h2>
<p>Shared folders provide a widely used method for storing, retrieving, and controlling file access among team members. Shared network folders provide files to entire teams, rather than to individual owners. File accessibility is unaffected and all files remain centrally located and accessible to authorized users. </p>
<p>In this scenario, I want to build 2 shared folders that will be assigned to new users and shared across the network. I will establish a "personal folder" in which individuals can store their own files privately, as well as a "department folder" in which all users within a certain department can share and access materials.
</p>


<br />

<h2>Step-by-Step Walk-Through:</h2>


<p align="center"> 
STEP 1: <br/>
<img src="https://i.imgur.com/OXOsVFh.png" height="70%" width="70%"/> </p>


<p align="center">The first step is to open "Server Manager" on the Windows Server 2016 device. I can do numerous things from here, but in this case, I need to create shared folders, so I select the "FILE AND STORAGE SERVICES" option.</p>


<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 2: <br/>
<img src="https://i.imgur.com/2qLWkIQ.png" height="70%" width="70%"/> </p>


<p align="center">This is the "FILE AND STORAGE SERVICES" area, and from here I select "Shares". This option will allow me to create the actual shared folders within the domain.</p>


<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 3: <br/>
<img src="https://i.imgur.com/ObSpjaN.png" height="80%" width="80%"/> </p>


<p align="center">This is the "SHARES" section in the Server Manager. From here, I can set up new shared folders within the domain. In this scenario, I right-click on the shares section to access further settings, then select the option "NEW SHARE".</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/jdVK7Ui.png" height="70%" width="70%"/> </p>


<p align="center">It is asking me which "file share profile" to select, and as you can see, there are multiple options. In this case, I select "SMB SHARE - QUICK," which allows me to build a shared folder quickly without having to go through any advanced options. I then move on to the next step by clicking on "NEXT".</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/VmNFHTd.png" height="70%" width="70%"/> </p>


<p align="center">In this step, I specify a location for the shared folder. In this scenario, I select the C drive as the storage volume for the shared folder. I then select "NEXT" to move on to the next phase.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/KucuKTa.png" height="70%" width="70%"/> </p>


<p align="center">In this stage, I must choose a name for the shared folder. In this case, I put the name "HR" for the shared folder, and at the bottom, you can see the shared folder remote path, which is very useful. I then move on to the next phase.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/HYP9W5N.png" height="70%" width="70%"/> </p>


<p align="center">In this step, I select the default option, and this enables to cache the share. I then move on to the next phase.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/J4mCG8N.png" height="70%" width="70%"/> </p>


<p align="center">This step specifies the permissions for the shared folder. In this case, I leave everything as default because I intend to make adjustments later. I then move on to the next phase.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/I0an04j.png" height="70%" width="70%"/> </p>


<p align="center">This is a summary of the shared folder configurations. I'm satisfied, so I click the "CREATE" button to successfully create the shared folder named "HR".</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/fXWJJdW.png" height="50%" width="50%"/> </p>


<p align="center">As you can see, I successfully created both the HR and the "Personal" shared folders. They are now both available on the domain and can be shared to the appropriate users.</p>



<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/eXpskeA.png" height="90%" width="90%"/> </p>


<p align="center">As can be seen, both shared drive folders have been established on the Server 2016 device's C drive. They can now be shared with HR department users.</p>



<a href="https://www.example.com">
  <button>NEXT</button>
</a>
