## DOC_FOR_SETUP_HELIUM_APP

	Hardware and software configuration need for Helium Edge project:

    *	OS  -  Windows 8.1 and above or  Windows  10  (recommended )
    *	I3 or above processor (i5 recommended)
    *	8 GB (recommended)
    *	Visual Studio 2013 and above (vs-2017 recommended)

	Steps follow to set up Helium Edge project:

    STEP 1:  Install Visual Studio 
    STEP 2:  Install latest Node.js from https://nodejs.org/en/ 
    ![image](https://cloud.githubusercontent.com/assets/27442147/25019892/ed5f2738-20a9-11e7-96cb-7f6a1280b202.png)
    
    STEP3:  Open visual studio and sign-in with your visual studio credential.
    
   ![image](https://cloud.githubusercontent.com/assets/27442147/25019989/56e677d8-20aa-11e7-8bd0-13045a674e65.png)
    
    STEP 4: Connect to Team Foundation server (https://brandonstaley.visualstudio.com/Helium):
    
      ![image](https://cloud.githubusercontent.com/assets/27442147/25020321/7a47fd0e-20ab-11e7-8fa2-7ff587a5fe53.png)
    
    STEP 5: After map to TFS we can see below structure:
    
    ![image](https://cloud.githubusercontent.com/assets/27442147/25046641/3480295e-2150-11e7-9e6c-f9bffa6e4716.png)

   STEP 6: Create a local folder for copy of an application.
   
   ![image](https://cloud.githubusercontent.com/assets/27442147/25046680/763c0796-2150-11e7-83cb-f0b0bc517bcf.png)
   
   STEP 7: Open “command prompt” as an Administrator and go to application folder:
   
   ![image](https://cloud.githubusercontent.com/assets/27442147/25046711/a287001c-2150-11e7-8328-cda170a056f3.png)

   STEP 8: run below command 
    *	npm install
    *	npm install angular-cli@latest -g
    *	npm install gulp-cli@latest -g
    
  STEP 9: Go to Tools -> Extensions and updates need to check “Type script for visual studio” is installed or not. If not please click             on online (left side of vs) and install.
  
      ![image](https://cloud.githubusercontent.com/assets/27442147/25046783/07a94f40-2151-11e7-8ef5-0daf3bd089f3.png)
  
      ![image](https://cloud.githubusercontent.com/assets/27442147/25046823/28f8e106-2151-11e7-9d20-9fa754bca5fd.png)
  
  STEP 10: Check NPM Task Runner is installed or not? If not please install through online.
  
      ![image](https://cloud.githubusercontent.com/assets/27442147/25046872/6338127e-2151-11e7-8278-07706ca42a76.png)
      
  STEP 11:  For confirm NPM (node package manager)  is install or not from cmd:
         Go to application folder location and check node_modules folder should present.

         ![image](https://cloud.githubusercontent.com/assets/27442147/25046975/f1124a56-2151-11e7-9d90-f320cec3f0c3.png)
  
  STEP 12:  Go to this path and change D:\Development\Source\.vs\config 
	      And open applicationhost.config file and need to add ‘dist’ at end of  physicalpath

         ![image](https://cloud.githubusercontent.com/assets/27442147/25047025/2eab30b2-2152-11e7-8cc2-8a562fe66127.png)
         
  STEP 13: Need to set up environment path in visual studio. Go to tool -> options -> Project and solution 
          ->  Web Package Management and move to first position.
  
         ![image](https://cloud.githubusercontent.com/assets/27442147/25047091/98452794-2152-11e7-9da8-080200009ffd.png)
  
  STEP 14: Now Build the application and run………..
  

  
  
  
  
  
