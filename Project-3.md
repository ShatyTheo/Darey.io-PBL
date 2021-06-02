#Simple To-Do application on MERN Web Stack:
Implementing a web solution based on MERN stack in AWS Cloud.

Step 1 - Backend configuration (Installing Node.js on ubuntu server)

![Project-3 image1](https://user-images.githubusercontent.com/63529760/120256686-aa027680-c25c-11eb-8932-f9efff586a37.PNG)

Application Code Setup : new directory for your To-Do project:

![Project-3 image2](https://user-images.githubusercontent.com/63529760/120257142-a3c0ca00-c25d-11eb-9767-5f4c3583de31.PNG)

Initializing your project to create a new file "package.json"

![Project-3 image3](https://user-images.githubusercontent.com/63529760/120257469-5002b080-c25e-11eb-866d-9daf0041da45.PNG)
![Project-3 image4](https://user-images.githubusercontent.com/63529760/120257546-70326f80-c25e-11eb-80d5-f1a72b2134fa.PNG)
![Project-3 image5](https://user-images.githubusercontent.com/63529760/120257853-fcdd2d80-c25e-11eb-9743-1984f60e0ae5.PNG)

Install ExpressJS:
![Project-3 image6](https://user-images.githubusercontent.com/63529760/120258210-99073480-c25f-11eb-9a13-f5175b0e515b.PNG)

Creating index.js file:
![Project-3 image7](https://user-images.githubusercontent.com/63529760/120258356-dd92d000-c25f-11eb-9d86-2f5feeab6c87.PNG)

Installing the dotenv module:
![Project-3 image8](https://user-images.githubusercontent.com/63529760/120258486-234f9880-c260-11eb-9aa5-1003e3645462.PNG)

Index.js file content:
![Project-3 image9](https://user-images.githubusercontent.com/63529760/120258677-7d505e00-c260-11eb-85f3-31c4367cf9d9.PNG)

Accessing Express in a browser:
![Project-3 image10](https://user-images.githubusercontent.com/63529760/120259044-3020bc00-c261-11eb-90ff-8c098fcf18fa.PNG)

Creating routes directory:
![Project-3 image11](https://user-images.githubusercontent.com/63529760/120259269-a32a3280-c261-11eb-8d17-e89628064911.PNG)

Creating api.js file:
![Project-3 image12](https://user-images.githubusercontent.com/63529760/120259457-fdc38e80-c261-11eb-986e-5882c4b1d38d.PNG)

Creating models by installing mongoose:
![Project-3 image13](https://user-images.githubusercontent.com/63529760/120259735-74608c00-c262-11eb-9a68-d11d9aaab40b.PNG)

Creating models folder and todo.js file:
![Project-3 image14](https://user-images.githubusercontent.com/63529760/120259867-bd184500-c262-11eb-8ef1-0e8a22a7ec12.PNG)

updating our routes from the file api.js in ‘routes’ directory to make use of the new model:
![Project-3 image15](https://user-images.githubusercontent.com/63529760/120404120-a41b9c80-c313-11eb-983b-65500d7a3f8d.PNG)

![Project-3 image16](https://user-images.githubusercontent.com/63529760/120403937-425b3280-c313-11eb-9a69-667dd6eaa0f7.PNG)

Creating MongoDB Database:
![Project-3 image20](https://user-images.githubusercontent.com/63529760/120405421-8439a800-c316-11eb-8035-1ab92397f77a.PNG)
![Project-3 image21](https://user-images.githubusercontent.com/63529760/120405463-9582b480-c316-11eb-96a9-cd5676d21691.PNG)

Creating .env file in todo directory:
![Project-3 image17](https://user-images.githubusercontent.com/63529760/120404602-b64a0a80-c314-11eb-97ce-fa29302c8e1b.PNG)
![Project-3 image18](https://user-images.githubusercontent.com/63529760/120404635-ca8e0780-c314-11eb-9a9a-e53702850316.PNG)
![Project-3 image19](https://user-images.githubusercontent.com/63529760/120404792-20fb4600-c315-11eb-9272-c6511b66371c.PNG)

Starting the server:
![Project-3 image22](https://user-images.githubusercontent.com/63529760/120405792-6587e100-c317-11eb-8404-8c2fd18b41aa.PNG)

Testing Backend Code without Frontend using RESTful API:
![Project-3 image23](https://user-images.githubusercontent.com/63529760/120406478-eeebe300-c318-11eb-9907-e74e3778988c.PNG)
![Project-3 image24](https://user-images.githubusercontent.com/63529760/120406495-fd39ff00-c318-11eb-988a-909e115051a3.PNG)

Step 2 - Frontend creation: A folder called client has been created in todo directory: 
![Project-3 image25](https://user-images.githubusercontent.com/63529760/120407124-7ede5c80-c31a-11eb-93a3-f660c6860dae.PNG)

Running a React App:

We’re going to install concurrently used to run more than one command simultaneously from the same terminal window, and install nodemon. It is used to run and monitor the server. If there is any change in the server code, nodemon will restart it automatically and load the new changes.

![Project-3 image26](https://user-images.githubusercontent.com/63529760/120407579-73d7fc00-c31b-11eb-887f-d34847ecb6da.PNG)
![Project-3 image27](https://user-images.githubusercontent.com/63529760/120407610-818d8180-c31b-11eb-8ebe-952ea20149b4.PNG)

Updating package.json in Todo's directory with the new script:
![Project-3 image28](https://user-images.githubusercontent.com/63529760/120407957-12645d00-c31c-11eb-81d3-ffc1fc9bb2ea.PNG)

Configure Proxy in package.json
![Project-3 image29](https://user-images.githubusercontent.com/63529760/120408283-ba7a2600-c31c-11eb-914e-aa235687ef7e.PNG)
![Project-3 image30](https://user-images.githubusercontent.com/63529760/120408500-29f01580-c31d-11eb-849e-afe1acf15596.PNG)
![Project-3 image31](https://user-images.githubusercontent.com/63529760/120408720-95d27e00-c31d-11eb-81ad-584f5ce84aee.PNG)

Creating your React Components:
![Project-3 image32](https://user-images.githubusercontent.com/63529760/120409737-979d4100-c31f-11eb-9c5d-db02cbb9943d.PNG)
![Project-3 image33](https://user-images.githubusercontent.com/63529760/120409775-aab01100-c31f-11eb-838f-6778a0ed04c1.PNG)
![Project-3 image34](https://user-images.githubusercontent.com/63529760/120409804-bb608700-c31f-11eb-94cc-857101b9d5e3.PNG)
![Project-3 image35](https://user-images.githubusercontent.com/63529760/120409835-cb786680-c31f-11eb-97f4-b2f8fc35e303.PNG)
![Project-3 image36](https://user-images.githubusercontent.com/63529760/120409861-d8955580-c31f-11eb-9c67-6fc91797939b.PNG)
![Project-3 image37](https://user-images.githubusercontent.com/63529760/120409926-fcf13200-c31f-11eb-94b5-542cb65bb953.PNG)
![Project-3 image38](https://user-images.githubusercontent.com/63529760/120409975-16927980-c320-11eb-80a2-74ec6a125670.PNG)
![Project-3 image39](https://user-images.githubusercontent.com/63529760/120410010-2b6f0d00-c320-11eb-9992-f7cb884d9183.PNG)











