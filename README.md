<h1 align="center"> GSoC 2022 @Moja Global 
  
</h1>
 
<br/> 

| Project Name: (Building UI library for moja global)  <br/>
 <br/> 
| Details |    | 
|------------|---------| 
| Mentor       |    Harsh Mishra, Gopinath Balakrishnan     |          
| Student |    Palak Sharma     | 
| Github Repository  | tick    |        
| Npm Package      |         |            
| Documentation     |         |             
 
<br/>    

# Project Description 
<p> Moja global is a not-for-profit, collaborative project that brings together a community of experts to develop open-source software that allows users to accurately and affordably estimate greenhouse gas emissions and removals from the AFOLU sector. <br/>
  
This year in Google Summer of Code 2022 I have worked on building a faster, lightweight, user-friendly, mobile-friendly, and cross-browser-compatible UI library as a stand-alone dependency for moja global projects. I work on building a UI library having pre-written or ready-made code for various widely used components across all the repositories of moja global that future developers and users can use in their projects just by installing the package and running two or three import commands.
  <br/>    

  
The UI library developed under this project serves the following purpose
  
  - The UI library help in maintaining a UI consistent theme in moja global as an organization.
 - The UI library has reduced designing time for upcoming projects and it will also future help developers to focus more on the backend implementation part rather than on coding the frontend part.
- This UI library has created the projects more user-friendly and attractive.   
- Using UI Library components is easy as most of the code is written in the documentation itself. 
  
  <br/>    

  # My Contributions 
  The main aspects of my contributions are 
 

|     Contribution       | Tools and Technologies used | 
|------------|---------| 
  | Migration of current projects from Vue2 to Vue3   |    Vuejs     |       
| Designing  |   Figma  |   
| Implementation      |    Vuejs     |          
| Documentation     |      Storybook   |        
| Building       |     Rollup    |       
| Testing |     Axe    |       
| Launch   |    Yarn     |  
| Integration of UI library into existing projects  |    UI library     |       
  
  <br/>    
  
  ## Migration of existing projects from Vue2 to Vue3
  
  Initially, I worked on migrating the existing project from Vue version 2 to Vue version 3, to make them compatible to use the UI library which is based on Vue version 3 
  
  These are the Pull requests, I made for migration of the existing project 
   - https://github.com/moja-global/FLINT-UI/pull/311
   - https://github.com/moja-global/FLINT-UI/pull/305 
   - https://github.com/moja-global/FLINT-UI/pull/304
   - https://github.com/moja-global/FLINT-UI/pull/303
   - https://github.com/moja-global/FLINT-UI/pull/302
   - https://github.com/moja-global/FLINT-UI/pull/301
   - https://github.com/moja-global/FLINT-UI/pull/299 
  
  ## Designing 
  After Migration, I worked on designing the components of UI library according to the Moja Global brand guidelines. 
  The designs can be found here 
  
  ## Implementation & Documentation 
  I did Implementation and Documentation of the UI library simultaneously, I have added various components in the UI library with each being fully customizable, and accessible. 
  
  These are the Pull requests, I made for the Implementation and Documentation of the UI library
  
   - https://github.com/moja-global/ui-library/pull/13
   - https://github.com/moja-global/ui-library/pull/15
   - https://github.com/moja-global/ui-library/pull/19
   - https://github.com/moja-global/ui-library/pull/20
   - https://github.com/moja-global/ui-library/pull/24
   - https://github.com/moja-global/ui-library/pull/25
   - https://github.com/moja-global/ui-library/pull/26
   - https://github.com/moja-global/ui-library/pull/27
   - https://github.com/moja-global/ui-library/pull/28
   - https://github.com/moja-global/ui-library/pull/30
   - https://github.com/moja-global/ui-library/pull/33
   - https://github.com/moja-global/ui-library/pull/34
   - https://github.com/moja-global/ui-library/pull/45
  
  ## Building
  Building the UI library, is the main task of the project. I used vue rollup to build the UI library. 
  
   - https://github.com/moja-global/ui-library/pull/35
   - https://github.com/moja-global/ui-library/pull/42
  
  ## Testing 
  For testing the components of UI library, I have given two options to test in development mode as well as while making the pull request 
  
   - https://github.com/moja-global/ui-library/pull/46
   - https://github.com/moja-global/ui-library/pull/47
  
  ## Launch 
  We the help of my mentor, the launch of UI library has been automated. The launch happens as soon as the package version in package.json is changed. 
  
  ## Integration of UI library into existing projects 
  We tested the UI library by integrating it in the fresh new Vue 3 project as well as in existing mojaglobal's project. It worked as expected in both. 
  It is currently in use in FLINT UI
  
  # Summary 
  
  The overall experience of GSoC has been amazing and full of learnings. I learn many things like how to build a project from scratch, how to work with large codebase, etc. I would like to thank my mentors for always being there and helping me whenever needed. 
 
