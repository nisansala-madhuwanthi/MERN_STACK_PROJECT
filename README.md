<h1>Locally Installation Guide</h1>

<h2>Prerequisites:</h2>

<p>Ensure that you have Git, Node.js, and npm (Node Package Manager) or may be Yarn installed on your system. (some npm packagers will not be working so should install yarn as well)</p>
<h2>Clone the Repository:</h2>
<ul>
<li>Go to the GitHub link of BrowseMe: [GitHub Repository Link]</li>
<li>Click on the "Code" button and copy the HTTPS link provided.</li>
<li>Create a new folder on your local machine where you want to download the project files.</li>
<li>Rename the new folder as desired.</li>
<li>Open the terminal (command prompt for Windows) and navigate to the newly created folder.</li>
<li>Use the following command to clone the repository: git clone [paste-the-copied-HTTPS-link] </li>
<li>Press Enter to begin cloning the repository.</li>
<li>Once the cloning is complete, navigate inside the project folder.</li>
</ul>

<h2>Setup Backend, Frontend, and Socket:</h2>
<ul>
<li>Open Visual Studio Code (VS Code) and click on the "File" tab.</li>
<li>Select "Open Folder" and find the location of the BrowseMe project folder you just cloned.</li>
<li>Select the "browseMe-market" folder and open it in VS Code.</li>
<li>Open the terminal in VS Code and split it into three terminals for backend, frontend, and socket.</li>
<li>In each terminal, navigate to the respective folder using the following commands:</li>
<br>
<p>For backend terminal: <em>cd backend</em></p>
<p>For frontend terminal: <em>cd frontend</em></p>
<p>For socket terminal: <em>cd socket</em></p>
<li>In each terminal, type the following command to install the required dependencies: <em>npm install or yarn </em></li>
<li>Press Enter to install the dependencies for each part.</li>
</ul>


<h2>Start the Servers:</h2>
<ul>
<li>For the backend, type the following command in the backend terminal and press Enter: <em>npm run dev </em></li>
<li>For the frontend and socket, type the following command in the respective terminals and press Enter for each: <em>npm start </em></li>
<p>The backend server will run on Port 8000, the frontend on Port 3000, and the socket on Port 4000.</p>
</ul>

<h2>Configure .env File:</h2>
<ul>
<li>For security purposes, the .env file has been removed from the repository. </li>
<li>Add the necessary things inside the "backend" folder -> "config" folder -> ".env" file.</li>
<li>See the documentation</li>
</ul>




<i>@copyright by BrowserMe 2023</i>
