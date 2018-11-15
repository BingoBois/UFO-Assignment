#### Hand-in

*   **List of questions, or link to the questionaire.**
    *   [https://docs.google.com/forms/d/10-jmVm4UdAqeX4Mi540RJrilu_AEbil5jigv6I3Dr6E/edit?ts=5bec1dee#responses](https://docs.google.com/forms/d/10-jmVm4UdAqeX4Mi540RJrilu_AEbil5jigv6I3Dr6E/edit?ts=5bec1dee#responses)

*    **An appendix with the actual answers** 


*   Question 1:


![Question1ImageScale](https://github.com/BingoBois/UFO-Assignment/blob/master/Q1Scale-APIDescription.png)




*   Question 2: What was the hardest part of the API description to understand 

    *   The hardest part is to get an overview. There's a lot of documentation. It's well formulated but not always clear of where to find what we need.
    *   I couldn´t find a general API documentention
    *   Which parameter the post method is exepecting to get

    

*   Question 3:

![Question3ImageScale](https://github.com/BingoBois/UFO-Assignment/blob/master/Q3Scale-GenerelInformation.png)


*   Question 4: What was the hardest part of the general information section to understand?_
    *   Configuring Proxy
    *   Nothing to comment
    
*   Question 5

![Question5ImageScale](https://github.com/BingoBois/UFO-Assignment/blob/master/Q5Scale-TechSection.png)
    

*   Question 6: What was the hardest part to understand about the technology section? 

    *   Test Environment
    *   The overall architecture
    
*   Question 7: Is there anything you would have done differently in regards to the project setup documentation? 

    *   Not really. Even though it's not that easy to setup everything, since I can't seem to find a simple way to start everything locally.
    *   I would make separated ReadMe for each project
    *   Maybe a content table would be great. 

*   Question 8: How would you rate this questionnaire on a scale from 1 to 5_

    
![Question8ImageScale](https://github.com/BingoBois/UFO-Assignment/blob/master/Q8Scale-RateQuestions.png)


*   Question 9: Additional Notes to the questionnaire

    0 svar


    Der er endnu ingen svar på dette spørgsmål.

*   **Your conclusions regarding the main issues pointed out in the questionnaire**

Despite a limited amount of answered surveys to work from, a lot of adjustments and conclusions can be drawn. \


*   **Question 1:**
    *   On a scale from 1 to 5, how easy was the API description to understand?
    *   1 person selected "3", while 2 selected "4"
    *   When asking for a user to give a rating, like on a 1 to 5 scale, it is important to specify what the high and low values represent, like the following example: "**On a scale of 1 to 5, where 1 is good and 5 is bad, rate your experience with X**". We obviously failed to provide such an instruction for our 3 questions where we asked for such ratings.
    *   Our reading of the scale is that the persons found the API description more harder to understand, than easy. This is probably due to the lack of an easy and simple overview, better layout, and more details regarding the API's, such as parameters. 
*   **Question 2:**
1.  The hardest part is to get an overview. There's a lot of documentation. It's well formulated but not always clear of where to find what we need._
2.  I couldn´t find a general API documentention_
3.  Which parameter the post method is exepecting to get_


For the first answer, we agree that while the documentation was huge and well formulated, we should have spent some time setting up and arranging the layout of the google doc more clearly. This could easily have been achieved by making an index list of all the topics in the document and more clearly define each chapter/section.

For the second answer, we are a bit baffled by the statement. When we were assigned a monitor group, we delivered them the following components:



    *   Links to the a (at the time) very thorough and up-to-date google doc containing all our documentation for the entire project.
        *   [https://docs.google.com/document/d/1js5Vx5Y_EBHAWZZGPYC5kW4LwCBrb_e1Qx2xlP_ZxnI/edit#heading=h.pqwzm878ggoe](https://docs.google.com/document/d/1js5Vx5Y_EBHAWZZGPYC5kW4LwCBrb_e1Qx2xlP_ZxnI/edit#heading=h.pqwzm878ggoe)
    *   Link to the project repo
    *   List of team members
    *   Instructions on how to post issues or questions.


![DocumentatitionHandOverDocumentation](https://github.com/BingoBois/UFO-Assignment/blob/master/groupdocudocu.png)


_The Facebook-message hand-in over the information regarding the project to the monitor group._

We will admit that we failed to cut-out the documentation document and place the relevant information in the relevant repos, and while we could dissect why the statement makes us feel like the user didn't look hard enough or didn't look in the right place, it ultimately falls back on us to make sure that all the information is easy to find and understand.

As for the third answer, while we did provide a exhausted list of all of the projects API's and a lot details concerning each individual API, we did fail to provide information regarding potential parameters in each individual API.

 



*   **Question 3:**
    *   _On a scale from 1 to 5, how easy was the general information section to understand?_
    *   One person selected "3", while two persons selected "5" 
    *   When asking for a user to give a rating, like on a 1 to 5 scale, it is important to specify what the high and low values represent, like the following example: "**_On a scale of 1 to 5, where 1 is good and 5 is bad, rate your experience with X_**". We obviously failed to provide such an instruction for our 3 questions where we asked for such ratings.
    *   Our reading of the scale is that the persons found the general information hard to to understand. 

        

*   **Question 4:**

1.  _Configuring Proxy_

We are not quite sure what the user is referring to here. There are probably a few more steps to run the project locally, since the team opted to develop the project using Typescript and a variable in the FrontEnd needs to point to a locally-hosted backend, rather then the one online.

The also opted to use a bunch of tools and technologies not discussed in class, such as Kubernetes, for hosting the project. 



*   **Question 5:**
    *   _On a scale from 1 to 5, how good of an overview did the technology section give you?_
    *   One vote on 1,3 and 5.
    *   When asking for a user to give a rating, like on a 1 to 5 scale, it is important to specify what the high and low values represent, like the following example: "**_On a scale of 1 to 5, where 1 is good and 5 is bad, rate your experience with X_**". We obviously failed to provide such an instruction for our 3 questions where we asked for such ratings.
    *   Our reading of the scale is, that the persons are very divided when it comes to determining if the documentation provided an easy overview.
*   **Question 6:**
1.  _Test Environment_
1.  _The overall architecture_

For the first answer, the team recognizes that the documentation has been insufficient to help the reader to setup the project for local testing.

As for the second answer, the team totally understands that the documentation relating to the overview of the project and its architecture, should have been a lot more stronger and thorough. The team was happy with the choice of splitting the project up into multiple repos for "frontend", "backend" and "DevOps", but the team failed to coherently bind the documentation together across the different repos.



*   **Question 7:**

 



1.  _Not really. Even though it's not that easy to setup everything, since I can't seem to find a simple way to start everything locally._
1.  _I would make separated ReadMe for each project_
1.  _Maybe a content table would be great._

For the first answer, the team agrees that even though we felt that we had written simple instructions for running the project, we failed to include more specific details, such as getting the project to run locally. The team also needed to write a more basic and simple overview of what tools were needed to run the project, to better prepare the user to setup the project locally and make them understand how the tools and programs intertwined with each other.

for the second answer, the team never completed the process of separating the google doc documentation into each individual and relevant repos, and that is totally the teams fault. 

For the third answer, the team recognizes that the documentation needed a better overview of its content, such as a index list in the beginning.  



*   **Question 8:**
    *   _How would you rate this questionnaire on a scale from 1 to 5_
    *   One vote on 1,3 and 5.
    *   When asking for a user to give a rating, like on a 1 to 5 scale, it is important to specify what the high and low values represent, like the following example: "**_On a scale of 1 to 5, where 1 is good and 5 is bad, rate your experience with X_**". We obviously failed to provide such an instruction for our 3 questions where we asked for such ratings.
    *   Our reading of the scale is, that the persons are very divided when it comes to determining if the questionnaire was easy or hard to understand.

  


    



*   **A list of which changes you made on the basis of those issues**
    *   Survey
        *   The "rating"-questions needs to be more defined!
    *   Documentation
        *   Up-to-date documentation
            *   The team failed to update the documentation as the deadline for the handover was approaching. This meant that a lot of new features, changes to existing features, API's etc. did not get updated as progress and development was made to the project, thus making parts of the documentation obsolete and outdated. This is clearly an area that we need to put on a higher priority in the future.
        *   Documentation available in relevant repos
            *   While the original idea for having one single document with all relevant information regarding the project was great, it failed to deliver on the individual repos. 
            *   The team needs to make sure that all the repos have their readme-files updated with the relevant documentation.
        *   Easier and better layout of the documentation
            *   The current google doc documentation is a bit messy.
            *   Needs to reorganize and use tools such as index, to quickly give the reader a overview of the document and its content
        *   Even more simple setup explanation
            *   Make sure that it's even more crystal clear how to setup and run the project locally for own testing purposes.
        *   Better Tool and Tech overview & details
            *   The documentation needs to better give the reader an better insight and explanation about the tools and technology used in the project.
        *   More details regarding the API's
            *   The team needs to add further details regarding the API's, such as Parameters.
            *   The team also needs to explain what API's the frontend uses from the backend.
        *   More explanation of the Frontend
            *   The information regarding the frontend needs to be expanded, especially in regards to methods, functions and libraries.
*   **A rough estimate of the time used to produce the original documentation, and a rough estimate of the amount of time used to solve this exercise**
    *   5-6 hours on the initial documentation.
    *   1-2 hours setting up the documentation in each repo
    *   1 hour on Survey
    *   4-5 hours reflecting on the survey
    *   Total: About 11-13 hours
    *   + 4-5 hours to update the existing documentation with the given feedback.
