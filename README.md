Meet GOATCOACH, 

  1.Project Overview 

  My AI Career Coach is designed to help college seniors and recent
graduates feel prepared for behavioral software
engineering interviews. 

The career pathway that this targets is Software Engineering 

GOOGLE NOTEBOOKLM

  2. The Problem I'm Solving
Many college seniors and recent graduates feel unprepared for software
engineering interviews. I'm facing this challenge myself right now, and
I saw the same struggle among classmates as graduation approached. I
also see it constantly on social media, where new grads share how
stressful and confusing interview prep can be.

  This tool helps because it gives candidates a place to practice behavioral interview questions, 
get feedback grounded in real sources, and build confidence before the interview, instead of trying to figure it all out alone.

3. How My AI Career Coach Works
I curated resources including:
- Qualtrics, "A Guide to the Software Engineer Job Hunt," a career guide
  written for college students and new grads
- Target job description: Junior Software Engineer at Bambee HR
  (Glendale, CA), an entry-level role focused on Python or TypeScript,
  data pipelines, and teamwork
- MIT Career Advising & Professional Development, “The STAR Method for Behavioral Interviews,” an interview       preparation resource

I used NotebookLM to analyze these resources and provide source-grounded
career guidance.


4. My AI Career Coach in Action

   EXAMPLE 1: Career Guidance
**My prompt:** Based on my sources, what are the top skills and
qualities the Bambee HR Junior Software Engineer role is looking for,
and how should I prepare for the interview?

**What the AI helped me understand:**
    NotebookLM explained what the Bambee HR Junior Software Engineer role
requires and showed which parts of my resume already match those
requirements. It also gave me a list of ways to prepare for the
interview, pointing to specific experiences from my resume that I can
talk about showing I have relevant experience.

  
  EXAMPLE 2: Mock Interview
**My prompt:** Okay now act as a hiring manager that is interviewing me for the Bambee HR Junior Software Engineer Role. Ask me a behavioral question at a time using the STAR method, wait for me to answer and then give me feedback

**What I learned:**
   I learned that while explaining my past experiences it is crucial to not be broad when explaining action taken, and what the results were. Also, when answering, using experiences that are on your resume is important so that it can showcase that you actually have relevant experiences. 

  
  EXAMPLE 3: Career Action Plan
**My prompt** Based on my sources and my resume, create a step-by-step action plan for the next 30, 60, and 90 days to become a strong candidate for the Bambee HR Junior Software Engineer role. Include specific skills to build, projects to work on, and interview practice. 

**My next steps:** NotebookLM compared my resume to the job requirements and built a plan around my gaps. First I’ll strengthen Python, SQL, and testing by adding pytest tests to one of my existing web projects, then learn AWS basics and build a small data pipeline project. In the final stretch I’ll add Docker and TypeScript basics, clean up my GitHub, and run full mock interviews.

5. Testing and Improving My Assistant

**Original prompt:** Based on my sources and my resume, create a step-by-step action plan for the next 30, 60, and 90 days to become a strong candidate for the Bambee HR Junior Software Engineer role. Include specific skills to build, projects to work on, and interview practice. 

**Improved prompt:** Based only on my sources and my resume, create a realistic 30, 60, and 90-day plan for becoming a strong candidate for the Bambee HR Junior Software Engineer role. Assume I can spend about 1 to 2 hours per day. Focus on the 3 biggest gaps between my resume and the job description. For each stage, give one measurable goal, 2 to 3 specific tasks, and one interview practice activity. Say which source supports each recommendation, and keep any numbers consistent.

**What changed and why** My original prompt was extremely broad and it assumed many things. For one my original prompt did not place any restrictions, so the response I got back was very ambitious and assumed I had unlimited time. I also changed it so that it would focus on my biggest gaps so that I won't waste time on parts I already know. Finally, to make sure I was learning I added measurable goals to make the plan realistic, easier to follow, and easier to check my progress.  


##6. Responsible AI
How did I check the AI's output for accuracy,
bias, or misleading information?

To check for output accuracy, bias, or misleading information I read and made sure that the responses made sense and did not output any hallucinations. One item in particular where my AI coach seemed to be inaccurate was during my first prompt when asking for a 30/60/90 day plan. While it gave me a seemingly great answer, the AI was too ambitious and gave me something that maybe would not be realistic for my schedule. I also made sure that the plan was consistent with skills I have put on my resume. 

What information should never be shared
with this assistant?

Personal information should never be shared, such as emails, phone numbers, addresses and maybe even work locations. I removed these from my resume to make sure that the coach does not have access to this. Besides, this information is not necessary for the coach to give me useful advice. 


## 7. My 30/60/90-Day Career Plan
30 days: Build a mock HR data ingestion module in Python with at least 15 pytest unit tests covering data validation and edge cases. Write 2 STAR stories using the MIT percentages.

60 days: Learn AWS S3 and Lambda and deploy a small serverless pipeline that processes uploaded data files. Practice explaining the architecture in a 30-minute whiteboard session.

90 days: Convert a React component or API route from a past project to TypeScript with no compiler errors. Polish my GitHub READMEs and complete a full 45-minute mock interview.

## 8. Reflection
1. What was the most useful thing my AI coach did?
     The most useful thing my AI coach did was use my resume and job listing, to make a realistic plan to be a better candidate for the job listing. 
3. What was one limitation or mistake I discovered?
    One mistake I discovered was that sometimes the AI may make assumptions if the prompts are not tight enough. In this case, my AI coach made a very unrealistic plan for someone with my schedule. 
5. How could this assistant help someone in a real job?
    This assistant can help someone get a real job by pointing out gaps in resumes. It can also help someone practice interview questions that are tailored from a job posting. This can help a person be prepared for an actual interview. Finally, this assistant can create a plan for someone who does not know where to start. 
7. What would I improve in a future version?
   One thing I can improve in the future is add multiple job listings that I am interested in. This way I can see other gaps in experience as well as become a better candidate for multiple job listings. I would also maybe expand this coach to cover technical interviews by adding a coding interview guide.

## 9. Skills Demonstrated
- Prompt engineering
- AI output evaluation
- Research and source curation
- Responsible AI practices
- GitHub documentation
- Career readiness

