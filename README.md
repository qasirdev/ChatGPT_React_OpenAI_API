#1- Build a JavaScript AI App with React and the OpenAI API
This is the repository for the LinkedIn Learning course Build a JavaScript AI App with React and the OpenAI API. The full course is available from [LinkedIn Learning][lil-course-url].

![Build a JavaScript AI App with React and the OpenAI API][lil-thumbnail-url] 

In this course, learn how to integrate the OpenAI API into a JavaScript-based web app. Join instructor Morten Rand-Hendriksen as he takes a React-based weather app, adds  a heavy dose of AI, and creates an interactive experience that knows what location you want weather information from, explains the weather data in simple language, and even suggests what to wear. Through this project-based course, Morten teaches you about API integration, user-based authentication, storing user tokens in a ServiceWorker, task-based API configuration, and sending and receiving requests to the API.

## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

## Installing
1. To use these exercise files, you must have the following installed:
	- Node.js
2. Clone this repository into your local machine using the terminal (Mac), CMD (Windows), or a GUI tool like SourceTree.
3. In terminal, run `npm install` to install all dependencies.
4. In terminal, run `npm run dev` to start the Vite dev server.
5. In terminal, type `o` to open the site in your browser.
6. In terminal, type `q` to stop the Vite dev server.



### Instructor

Morten Rand-Hendriksen 
                            
Developer and Senior Staff Instructor

                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/morten-rand-hendriksen).

[lil-course-url]: https://www.linkedin.com/learning/build-a-javascript-ai-app-with-react-and-the-openai-api?dApp=59033956&leis=LAA
[lil-thumbnail-url]: https://media.licdn.com/dms/image/D560DAQGwwpM5Oem1Pw/learning-public-crop_288_512/0/1694808958256?e=2147483647&v=beta&t=8aOT86V8OE20qAcH8cwG-lc1LhmHB6fCRC0q4hmoVfk
_See the readme file in the main branch for updated instructions and information._

### 2- For AI assistant: 
[building-custom-agents-with-the-openai-assistant-api--asi--3366139](https://github.com/LinkedInLearning/building-custom-agents-with-the-openai-assistant-api--asi--3366139/tree/main)

```
Math tutor:
You are a personal math tutor. Answer questions briefly, in a sentence or less.

Dual language:
Answer every question in one paragraph, and provide both an english and a norwegian version of the answer. Make sure they contain the same information.

HVAC manual:
Provide short helpful step-by-step instructions and problem solving related to how to operate a remote control for an HVAC system. Use the provided files as reference with every response.
```
![ai-assitant-all](https://github.com/qasirdev/NEXTJS-TESTING-main-udemy/assets/19289683/12fea968-3369-460f-a6ef-0ffa5fb21013)
![ai-assitant-hvac](https://github.com/qasirdev/NEXTJS-TESTING-main-udemy/assets/19289683/456fcf41-af9d-4132-a06d-633ca0dededf)

### 3 - Custom instarunctions:
- https://github.com/LinkedInLearning/controlling-chatgpt-with-api-system-messages-3814093 - use Rest Client extension
- https://github.com/microsoft/prompts-for-edu/blob/main/Students/Prompts/Tutor.MD
![ai-custome-instrunctions](https://github.com/qasirdev/NEXTJS-TESTING-main-udemy/assets/19289683/05258789-90e7-4c77-a7fe-24ad9c7e1c6c)
