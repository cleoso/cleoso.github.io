---
layout: essay
type: essay
title: "What AI means to me and the future"
# All dates must be YYYY-MM-DD format!
date: 2024-05-04
published: true
labels:
  - Software Engineering
  - AI
  - ICS 314
---

### I. Introduction
AI will continue to be in our lives for the foreseeable future; what may change is how we use it and how we interact with it. Regardless of this, AI has been a great tool in assisting and providing guidance for this semester with ICS 314. Without AI, it could be reasoned that the course material would be more difficult since ICS 314 took considerably more time and effort for those who just started the course. Here I revisit concepts and analyze my experience using AI from a critical analysis standpoint throughout the semester. In my analysis, I convey my personal experience and my judgments of its usage in the future.

### II. Personal Experience with AI:
I have used AI in class this semester in the following areas:

1. Experience WODs e.g. E18
   In regards to the WODs in tole, AI was great at answering questions about the concepts and the libraries used for it. It was also very good at providing examples and more context. Within the short period of time, I had used AI more and more critically than ever before. In the cases of the WOD's experience, it was clear to me that I would use AI as more of a smart friend that you knew, knew the concept or learning materials better than you. So as I would, I asked AI to explain in a more detailed manner why something is used in a certain way and so forth.

3. In-class Practice WODs
   Using AI in our practice WODS helped me understand the syntax and understand how things function. However, to accomplish this, I would need to be explicit to the AI that I am a college student or learning the fundamentals of coding in order for the information to be relevant or meaningful for me. AI was not good at interpreting this and was unable to identify the missing points in my code. While the AI was great at resolving the code, it wasn't good at being lazy, so the majority of the answers code corrections or suggestions were overtly complicated and thus altered the entire framework of the code. Therefore, as I aspire to be an effective coder, I want to do more while doing less, but the code presented as a solution to AI is more complicated and thus made my level of efficiency inconsistent and requiring more energy.

4. In-class WODs
   While the practice WOD's were lower risk as far as scores, we really got to see the impact of AI in our in-class WODs. AI was indeed able to do tasks for you in regards to building code. For example, AI was able to identify one code that calls another method from another method. When AI was prompted to either write code or edit existing code, it was great at identifying what needed changes or edits. However, the code that it suggests was either too complex, too simple, or failed to add significant code that would otherwise be needed for it to work. Furthermore, AI is able to do the majority of the corrections and handling of code due to syntax alone. However, it failed to understand the assignment's context and relative need completely. Therefore, when editing or building code, it increased the time needed to build the code. The more complex and specific the instructions were, the AI flourished; in broader and more conceptual cases, the AI failed to address the in-class WODS correctly.

5. Essays
   At first, giving the AI a prompt about writing an essay about a project, homework, or assignment, we began to see where AI was truly incapable. Since AI doesn't have memory and interpretations of such memory, identity is something it lacks. Therefore, the lack of identity ultimately leads to the failure of what professors have called "the voice." It's this voice that as writers we can connect with, empathize, and deliberate on. It is the capability to identify an identity behind the text, to see that there is a sort of intelligence that is grappling with the concepts provided in class. Knowing this, my personal experience with AI in the contexts of writing essays was purely for grammatical and spelling errors, nothing more.

6. Final project
   In my personal experience, AI was really great at identifying errors, albeit just regurgitating what the error message already said. It was good at providing suggestions; however, at times, it failed to recognize the computer's configuration or the IDE configuration, thus was not able to provide great feedback. However, I used AI in our final project to explain to me simply how some libraries ultimately work. Instead of me having to read the documentation, I would reference the document online to the AI and ask to provide me clear and concise understanding of how to use some of the functions or methods and even give me some examples. The final project was heavily pre-done by the templates that we used; however, editing the template so that I could do the functions that we required ultimately required some AI assistant.

7. Learning a concept / tutorial
   Learning a concept or a tutorial was indeed something that AI was good at the majority of the time. For example, I wouldn't understand how a library would work, and although providing AI the prompt to explain to me how this works and even give me examples, it was great. However, it wouldn't satisfy determining why we do this, or even smaller hints that could potentially help us in the future. This part of the AI lacks in pursuing teaching; the videos provided as tutorials allow me to not only see the entire concept, but the professor would explain why we do this and allow me to get hints to help with my career or future projects. However, I used AI to explain to me documentation, and I used the examples provided from AI to help me better understand the concepts better.

8. Answering a question in class or in Discord
   My only time that I used AI to answer in-class prompts is when we talked about conceptual concepts such as first-class citizen types of coding. Although it was great providing definitions, it was not fully correct in its perspective as for its intentions or its usage. Furthermore, I used AI in order to answer the majority of the error messages that I received in IntelliJ IDE, which it was good at providing step by step instructions.

9. Asking or answering a smart-question
   I never used AI for asking questions; however, I used it indeed to answer my own smart-questions. AI was great at answering my questions and it was great at providing great solutions. For example, there was a time where I was attempting to install the library of Meteor and Mongo Database into the IntelliJ IDE but it failed to render. The issue was that it wasn't added to the main path from the IDE to the file location of the downloaded library in the local computer. Therefore, it was able to provide me a step-by-step instruction on how to do so, and I was able to answer my own smart-question.

10. Coding example e.g. “give an example of using Underscore .pluck”
  One of the examples that I needed more assistance with is how to create different roles in for users in the final project. I asked AI to please "give an example of how to use roles in meteor for different accounts with different privileges." Soon, after the AI was able to provide me step-by-step how to implement a role-based access control to the code.
        CODE PROVIDED BY CHATGPT:
        // server/main.js
        
        import { Meteor } from 'meteor/meteor';
        import { Roles } from 'meteor/alanning:roles';
        
        // Define the roles
        const roles = ['admin', 'manager', 'user'];
        
        // Set up roles when the server starts
        Meteor.startup(() => {
        roles.forEach((role) => {
        if (!Roles.roleExists(role)) {
        Roles.createRole(role);
        }
        });
        });
    
11. Explaining code
    Indeed, AI was great at explaining code; when we used templates I would copy the entire code and ask the AI to explain a part of the code or the entire code. AI was able to break the code up and document what each code did and how it worked. However, it would focus on the function of the code; at times, it wouldn't explain to you why the code didn't work. For example, in one of our in-class WODS I asked what one code did in its entirety and there were errors in the code. But, the AI was not instructed to explain to me whether the code worked, it simply told me what each function of the code did. Therefore, it lacked the nuance to explain to me what the error was with the simple prompt what does the code do.

12. Writing code
    When editing the code so that web pages had the correct navbar items or the correct links to the right pages it was difficult doing it manually. I used AI to copy the entire code and asked the code to add the links and or correct code into the code. The AI was able to input the information correctly and even comment where the changes were made so that it was easily referenced. AI is great at writing code if given very specific and detailed instructions on what is allowed to do and what is meant to output. Otherwise, AI fails to write the code correctly or simply.

13. Documenting code
    Every time I asked AI to edit or overwrite code that I copied into it, it maintained the software documentation standard of explaining what the below code is meant to do or where the code is meant to be implemented. In the above example of providing an example of using roles based access control into our final project, it commented what the code did and where the code needed to be implemented too. AI is great at documenting code that it has either edited from the original text provided or the code that it has overwritten. Even when you have no documentation on what the code does, if the AI is provided the text and asked to provide documentation of the code it will do a great job of doing so.

14. Quality assurance
    Depending on the criteria of quality assurance it was not able to truly adhere to a specific standard of coding. It's difficult to say that it maintained the quality that was requested, although it was great at quality assurance in the context of documentation and the ability for it to organize the code correctly. The majority of the time the quality assurance was done by me. For example, the code that it was prompted for our final project was good at doing great work, but when we would commit these works to the GitHub it wouldn't be able to do that for us.

15. Other uses in ICS 314 not listed above
    In many cases, I used AI to test the model more and more about its ability to answer philosophical or even moral questions. All times fail to objectively provide a good case for moral justification, it rather provided only what the common consensus was across the internet. However, at a time the data that it was tested on and what it was fed was entirely biased. For example, at a time I asked the AI to write a song about how great and kind President Donald Trump was. I was surprised to see that it had once said that I was not capable of lying about how that is the case. However, writing the same prompt but for President Biden instead it wrote an entire song. I tend to do these moral tests to determine what data is being fed to the AI and how it could influence my interactions with it.

### III. Impact on Learning and Understanding:
Indeed, AI was impactful in my learning of 314 and more in several ways. Firstly, it was able to explain things in terms that I could understand. This was important in scenarios that the concepts required preset information, so it was able to simplify and condense the information. Secondly, it was able to provide examples; without examples of code, it was hard to conceptualize the functionality of how libraries or code works. These examples pushed my ability of learning how to use functions and even building code. Finally, AI was great at documenting the code; without the documentation of the code, I was left to interpret how each line of the code works. With the documentation provided by the AI, I was able to see the code and how it worked line by line.

### IV. Practical Applications:
In practical use for applications, AI was impactful on few points; practically using AI is great at doing work. For example, building mutator methods to allow one class to call variables from another quickly. Writing that code can be repetitive and therefore is great in using in that case. Practically, using AI as a time and energy manager is huge. We are able to do many different tasks all at once; we are able to edit and change information clearly. But moreover, we are able to develop skills from it. AI will always be a tool for which we as humans use to help us resolve issues or learn. AI is great for many industries, and not so great for others, but regardless is ultimately a great resource.

### V. Challenges and Opportunities:
The challenges AI faces are interpretation and memory recall. This ultimately lacks true intelligence in the sense it's able to not just be self-aware but self-identifying. Without identity, the context of being, it's hard for AI to communicate in a way to the user without being prompted. For example, implicature of the obscurity or accidental omission of information it's being provided can be interpreted. This complex communication function is foreign to AI and lacks the ability to assist users with problems that maybe the users are unable to answer fully. For example, if AI is given a prompt, it will only act on that prompt, but will the AI remember your capabilities and make judgments on that in order to best tailor a response to you? The answer is no; it will treat text as it is, with direction and explanation. Therefore, without memory recall and identifiers for self, it fails and lacks to provide adequate and salient responses to the user. Nonetheless, there are so many opportunities for AI to assist with repetitive tasks that would otherwise take us more time than most. Therefore, AI will be the next evolutionary tool used by humans to assist with problem-solving of issues that would otherwise require manual effort. Imagine a world where we are able to iterate our ideas with considerably fewer resources and energy as before? Therefore, AI is the future spear of resource management for humanity.

### VI. Comparative Analysis:
Not all AI are built the same; ChatGPT and CO-pilot are not at all the same. They differ in many ways from the way that the dataset is trained and fed, to how it's supervised, and how it responds to the user. There are many differences between the each AI. For example, CO-Pilot AI is great for coding issues and documentation, while ChatGPT is decent at it. Another example is ChatGPT at one time wasn't able to write a good song about Donald Trump, but now it is. Compare that to Gemini (Google) as of today, isn't able to write such as song. So these data sets are clearly biased and additionally respond accordingly to those biases in the data that it is provided.

### VII. Future Considerations:
In the future, AI will definitely change; it will indeed change how we interact with it as well. Soon, it will be able to understand contextual evidence and interpret the context in such a way that it will be able to determine the best solution to your problems. The consideration that we all as users of AI have is how does it determine what is the best solution; obviously, the answer lies with the data it is being presented. However, training an AI to be universal requires deep analysis of what is an acceptable response to the solutions we ask of it. Therefore, in the future when I use AI, I must first consider the AI in use and ask myself what data is it being trained on? Is it impartial? and how are its responses actually assisting me? Considering this is a tool and the clear distinction between different AI's I must consider that one AI is not sufficient currently for all situations or problems. Every AI is great at what its intended purpose is because its creation was tailored to a specific issue.

### VIII. Conclusion:
AI is revolutionizing the way we consume information, how we access information, and how we search for information. This has been the case for humans from the dawn of time, where once the information was privy to few, the creation of the paper was the ultimate tool for human knowledge. Afterwards it was the creation of the internet, which is the largest library in the world, and now we have AI. How we access information and how we search for it is definitely changing and as future problems not only coding, arise from this new invention, we begin to see the universal effect of its usage. Currently, AI has affected how we are educated, which ultimately has changed how we see the world as well. AI is indeed changing the world one mind at a time; therefore, we must be cautious of how we use these tools. Because, similar to the rise of the internet, so too did the rise of criminal activity. So what criminal, moral, and ethical issues will ultimately arise from the usage of AI?
