# python-windows-setup

1. **Download this file:** 

https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-Windows-x86_64.exe

2. **I choosed "All Users"**
  
<img width="496" height="384" alt="image" src="https://github.com/user-attachments/assets/97cfde2b-2505-4416-9e5b-b49f39c5abb7" />


3. ❌ Register Miniforge as system Python ⚠️ **LEAVE UNCHECKED**
  
<img width="497" height="385" alt="image" src="https://github.com/user-attachments/assets/6a0aee03-7844-4947-8423-27af819a18c4" />


4. **After Installation, go to Windows start menu and find "Miniforge Prompt"**
  
<img width="781" height="636" alt="image" src="https://github.com/user-attachments/assets/26682dd5-1fa7-43f8-b835-424419205fa4" />

5. **Open the Miniforge Prompt, type:**
   conda --version

	 <img width="1950" height="248" alt="image" src="https://github.com/user-attachments/assets/7a669333-25b8-4c99-b0ef-cfe73fdc299c" />
	if it shows a version without error, then so far so good


6. **Study this command before typing in:**
   
	**conda create -n WhateverNameYouWant python=3.12**

	conda is a tool that installs Python, python packages, manages python environments

	Miniforge is an open source, no telemetry tool for installing conda, it's called "MiniForge" because there is already "Anaconda" "Miniconda" which has telemetry and owned by a corporation*

	conda let's you create multiple environments, imaging some programs need python 3.14, some python 3.13, some numpy version>2.0, some numpy version<2.0, an actual problem I ran into. To resolve this, you can create different python environments for different python programs so they don't have package version conflicts. usually 2 environments are enough for everything.

	<img width="1483" height="280" alt="image" src="https://github.com/user-attachments/assets/716bb762-487a-4374-bf82-0dcac22ffb3f" />


	**conda create -n WhateverNameYouWant python=3.12**

   	**conda create** 
	creates an environment
   
    **-n**
   	command for "name"
   
    **WhateverNameYouWant**
    change this to a name you want, I use kokoro311 so I know its used for kokoro and python version = 3.12
   
    **python=3.12**
   	newest version of python is 3.14, 3.12 was the last version that offered real speed boost from 3.11, 75% for synchronized tasks, very important for media sites
   
   
