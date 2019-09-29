
# 9 Tips to Get or Keep Your GitHub Ready for Job Seeking (and Two More to Make it Unstoppable)

Github isn't just a repository for code — it’s another part of your online presence, and arguably the most specific tool a hiring manager has (without talking to you) to understand how you’ll stack up as a candidate. Based on _**numerous**_ feedback sessions with employers we **know** that your GitHub profile will be a critical step in their assessment of you as a candidate. 

**Note:** Sometimes when graduates leave the program, they stop receiving attribution for their Git commits (i.e. the link between their computer and their GitHub account becomes severed). This can happen for a variety of reasons. To ensure the commits you make on your computer are associated to your GitHub profile, follow the steps below:

> 1. Open your [email settings in Github](https://github.com/settings/emails).
> 2. In your terminal, run the command `git config user.email`.
> 3. Verify that the email in your terminal matches the email(s) listed in your GitHub profile.
>
>If you don't see an email when you run the command above, follow the "Your Identity" section in the [First-Time Git Setup Guide](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup#_your_identity).
>
>If you see an email when you run the command above but it's not listed in your GitHub profile, [add the email to your profile](https://github.com/settings/emails#email_label) so that you receive the proper attribution for your work.
>
>If you notice that your repository already has commits that aren't attributed to you, you can follow [the directions here](https://help.github.com/en/articles/changing-author-info) to update the attribution for each commit. In order to find the old email, you can run `git log` in the repository. _Since this action is "destructive", make sure you clone down a **separate copy** of your repo into a separate folder on your computer **before** you update the attributions. This way you'll have another copy of the original repo in case something goes wrong._

**In addition to ensuring that you are authoring all your repos on GitHub properly per the steps above, the following will make sure you stand out as a candidate...**

## Tips for a Strong GitHub Profile

### 1. Pin Projects to the Top of Your Profile

- Highlight your most impressive, large and/or recent projects (this can include Flatiron Schools projects, and solo projects) at the top of your GitHub page. The first thing an employer should see is what you’ve been working on most recently (your current skill set). 
- Having small projects is okay, but try to make them diverse. Having projects using different languages or technologies will show that you possess a variety of skills.
- You can do this through the ‘Customize your pins’ link. 
- These should be projects you have created - NOT completed labs!

### 2. Add Project Descriptions and Tags

- EVERY Flatiron School project (and future projects) should have a detailed description.
- Descriptions should include a few sentences about functionality, languages and/or major tools used. Be concise while explaining what the project is about. Include the project’s purpose and highlights.
- They should also include a link to a live site (at one point or another every final project should be hosted).  
- If your live site is buggy, make sure to video a demo of yourself using the project before the site comes down. Add that instead of a live link.
- Descriptions can be added/edited on the project repo.

### 3. Add a README for Every Project 

- All projects should have a README attached (gifs are highly recommended).
- READMEs can include wireframes or videos demonstrating project design and/or functionality.  
- This differs from a description as it should be longer, and about project functionality.
- For software engineering students: READMEs can also include links to live apps - if Front End and Back End are broken into separate repos, provide a link to the other relevant portion.
- If you wrote a blog post about your project, link it here.
- This feature can be added/edited on project repo.
- Check out this [guide to writing a kick-ass README](https://medium.com/@meakaakka/a-beginners-guide-to-writing-a-kickass-readme-7ac01da88ab3)
- Extra tip: While you can't embed a Youtube link (i.e. a project demo video) to a README in GitHub, you can include a thumbnail using the code at the very bottom of [this article](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links). Adding a youtube thumbnail is not required, but looks snappy. :)

### 4. Fill out ALL Profile Information

- Full Name
- Bio (if nothing else, Student of {Your Field of Study})
- URL (to something! blog, personal portfolio, etc. - preferably something with contact info)
- Email (personal choice)
- Company (FIS)
- Location  
- Recruiters use search tools and filter out profiles based on location. Having this information on your profile makes it easy for them to find you.
- Picture (professional: think LinkedIn)

### 5. Commit Often

- Does your GitHub account show that you are actively building/coding?
- Make consistent (daily) contributions to your Github profile. Think GREEN BOXES! Your daily activity will show potential employers your level of activity each day, week, month - and commits should be frequent! Employers look for this.
- One employer shared this: *A flurry of activity and then a decline to nothing is bad; a flurry of activity during the bootcamp and then sustained progress will distinguish you from 80% of bootcamp grads.* 

### 6. Contribute to Open Source Projects

- This shows that you can work well with a community, you know how to dive into large codebases/datasets and can adapt to different coding/programming standards. 
- Having pull requests/issues/reviews visible on your profile makes you stand out.

### 7. If You Fork Code, Actually Work on It

- Create meaningful contributions to other people’s code. If you want to note a fork to return to later, delete the fork, but star the repo it came from. 
- Your GitHub should communicate that you can build purposeful, meaningful apps/projects and features. 
- Companies are interested in what you are capable of creating, not that you completed a lesson; avoid arbitrarily pinning forked Learn.co lessons.

### 8. Focus on Project Structure and Organization

- In regards to architecture and design, make sure it is easy to figure out where to go in the project to locate the various functional areas and layers.
- Use relevant and well-known design patterns/file structures (don’t go out on a crazy limb).

### 9. Have Clean, Easy-to-Read Code on Your GitHub

- Functions should be responsible for one thing in general.
- Keep your code modular and DRY (‘Don’t Repeat Yourself’). Keep methods small and create a chunk you can reuse in different places as well as stack in different orders. Stay away from ‘copy and paste.’

## Bonus Tips

### Software Engineering

#### Are There Tests?

- Building out tests is impressive — especially at a junior level. 
- [Check out this article](https://www.toptal.com/qa/how-to-write-testable-code-and-why-it-matters) for tips on how to write testable code and why it  matters.

#### Are There Comments on Code?

- In a great code base, you’ll see a line about each code before writing the method, giving a  description of what it does.
On your next big project start adding in comments - this will prepare you for working on a common code base at your future  developer gig, and demonstrate to employers that you’re ready to collaborate effectively.

### Data Science

- While data projects are, by their nature, exploratory, with lots of sketching and exploratory data work, the final product - especially something that sits atop your resume as the first thing you are asking a hiring manager to look at - needs to be clear and clean.  
- Move intermediate/cutting room floor analysis to a separate workbook so it can be accessed at a later date.  
- Include many more markdown cells that describe the approach you are taking and bring the reader along in the analysis.  
- Compare model outputs in charts or tables to articulate why you selected the model that you did.  
- [Here is one writeup](https://towardsdatascience.com/custom-loss-functions-for-gradient-boosting-f79c1b40466d) (not an ipynb) that's an exemplar of leading with ideas.
