Steps to run the Application

Extract the Batch-B2_B3_File_Sharing_App.zip file

Now open the extracted file (File_Sharing_App) in the VS Code or any IDE

Now open two terminals (Click CTRL + `  to open terminal in VS Code) in VS Code

Terminal 1:

First change the directory to Server

	cd server

Now just run the package.json to install all the required modules

	npm install


Terminal 2:

Change the directory to Client

	cd client

Run the package.json to install the node_modules

	npm install


Once the installation is finished start the server in both terminals.

	npm start

Now the server is started at port Number 8000 in server

Now the server is started at port Number 3000 in client

Upload any file into the server and a link will be displayed, copy that link in any browser and the file will be downloaded



