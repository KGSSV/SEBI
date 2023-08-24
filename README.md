# SEBI - Empowering Investors Hackathon

#### Team Name - The Turing Tribe
#### Problem Statement - With the rapid proliferation of digital platforms, there has been an alarming surge in deceptive investment claims propagated by self-proclaimed influencers. Such misinformation poses a significant threat, potentially causing unwary investors substantial financial losses. This challenge necessitates innovative solutions in the form of advanced models, cutting-edge tools, and user-centric products that meticulously scrutinize and ascertain the authenticity of influencers active on digital platforms. By harnessing the power of advanced technologies such as Generative AI and Machine Learning, these solutions strive not only to promptly identify and red-flag deceptive claims but also to erect a robust protective barrier around investors, thereby preempting potential financial hazards.

#### Team Leader Email - rajveer.mathur25@gmail.com

<img width="348" alt="TuringTribe" src="https://github.com/KGSSV/SEBI/blob/main/latest%20ttt.png">
<br>

## A Brief of the Prototype: 
The Prototype is disected into 3 parts
#### 1.Landing UI: Users are prompted to provide links to YouTube videos or YouTube shorts to initiate the process. In doing so, users gain access to the concurrently generated transcription also.
<img width="550" height="430" alt="End2End" src="https://github.com/KGSSV/SEBI/blob/main/MicrosoftTeams-image%20(11).png">

#### 2. The Analysis : Here the user gets the consolidated / processed knowledge of various metrics such as : Category , Confidence Score , List of Descriptives , Missing Context
 


## Tech Stack: 
#### AWS Lambda Functions (Serverless Backend)
#### HTML, CSS & JS (UI Playground)
#### Github Actions (End 2 End Automation)   

## Step-by-Step Code Execution Instructions:
#### UI Playground/ Sandbox
1. Pull Repository and NPM INSTALL in the client as well as server folder.
2. NPM RUN SERVER on both above directories as well.
3. The UI will open in browser with IP Address.
4. Generate your Fine Grain Token for the repository for which you want test cases.
5. In the UI put the Token in the Gitpat Token and username as Repo Owner.
6. Select parameters of repository, branch and module.
7. Next you can choose the test cases to be generated by AI driven technique or Manual Input.
8. A Submit Button will push this to your Repository after dealing with GPT prompt engineering.
9. Results can be seen of the assessment in the test case validation pipeline.
10. Create a .github/workflows workflow file where action pipeline can be defined
11. Fetch these Yml files from this repo and paste them in the above created directory of the desired testing repository.


#### End 2 End Automation
1. Create a .github/workflows workflow file where the action pipeline can be defined.
2. Fetch these Yml files from this repo and paste them in the above-created directory of the desired testing repository.
3. Download MobaXterm.
4. Go to Repository Settings and click on "runner" -> "action runner" -> create action runner and note down all the commands provided on the UI.
5. Set up an SSH Connection using MobaXterm with the hosted EC2 Instance/Ubuntu VM.
6. Run all 5 commands to host the action runner on the VM.
7. Now the environment is set up, and you can make changes to any .java logic file, which will push test cases to the testing directory.
8. Upon push, you will notice an action pipeline firing, which will validate the test cases.

9. For funcitonal testcases make changes to .html file (ui component)
10. this will fire a diffrent pipeline setuped which is reponsible for genrating functional test cases
11. once the test cases are generated a pipeline will trigger which will connect with mobaXterm to validate the functional testcases in headmode
  
## What I Learned:
During the development of the prototype, the most significant learning I had was the immense potential and power of AI-driven testing and automation in revolutionizing the software development process. As the prototype evolved and integrated various elements, I witnessed firsthand how the combination of AI-driven test case generation, seamless code management integration, and continuous monitoring could create a highly efficient and effective testing solution.

One of the key takeaways from the development process was the remarkable speed at which the prototype could execute tests and provide feedback. AI's ability to rapidly analyze code, generate relevant test cases, and prioritize critical areas for testing significantly reduced the time required for testing. This acceleration translated into faster development cycles and quicker time-to-market for software products.

Another critical insight was the robustness of the AI-generated test cases. The AI pointer showcased an impressive ability to identify corner cases, edge scenarios, and potential defects that might be overlooked during manual testing. This discovery emphasized the importance of incorporating AI's intelligence into the testing phase to ensure comprehensive coverage and enhance the overall quality of the software.

Moreover, witnessing the seamless integration with code management tools during the prototype development was enlightening. The ability to access code directly from repositories, perform testing on specific branches, and automate the validation pipeline simplified the entire testing process. It made me realize the true value of having testing and development processes seamlessly interconnected, leading to greater collaboration and streamlined workflows.

Throughout the development journey, I also gained valuable insights into the significance of continuous monitoring and feedback loops. With the prototype providing real-time insights into test results and detecting issues early on, developers could promptly address and resolve potential defects. This iterative feedback loop proved indispensable in maintaining high software quality and fostering a culture of continuous improvement.

In conclusion, developing the prototype underscored the transformational impact of AI-driven testing and automation in the software development life cycle. The biggest learning was how this integrated approach could significantly reduce manual effort, expedite development cycles, improve productivity, and ultimately deliver higher-quality software products. The experience solidified my belief in the immense potential of AI in reshaping the future of software development and testing.
