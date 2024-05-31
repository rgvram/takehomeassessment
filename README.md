# Tasks

1.  From this list, rank your 5 most favorite and 5 least favorite support tasks. Provide a
    brief explanation for each.
    Ans:  
     Favorite:
    a. Respond to 25+ support requests via email every day
    reason: I love solving puzzles and supports request are like puzzles(some small while other large), so doing 25+ support request per per day is some thing that I enjoy doing
    b. Dig through logs to troubleshoot a customer's broken project
    reason: I am good at digging through logs because I believe logs are gold mine of resources which are like timeline of a project or incidents
    c. Analyze hundreds of support tickets to spot trends the product team can use
    reason: I believe that data shows insights to many issues and by following data we can also creation solutions to mitigate those issue or reduce time taken to handle similar situation
    d. Help train and onboard new support teammates
    reason: I love teaching others what I learn because I learn fast and understand concepts when I teach
    e. Act as a dedicated CSE for a handful of key customers to ensure their success using Vercel
    reason: I love the challenge of working with a customer end-to-end and see the resulting of work impact real world projects.

            Less Favorite:
                a. Respond to queries on Twitter, Reddit, Hacker News and other 3rd party sites
                reason: When I am in a public channel and cannot ask developer to share there confidential logs the level of support I can provide is based on assumption which may or may not work. I do not like ambiguity, so I would rather have developer interact with me in private setting where I can completely understand the issues and provide clear solution.
                b. Manage a support team
                reason: I am happy to mentor or help team mates however I do not enjoy managing team and would rather spend that time take up projects
                c. Work with 3rd party partners to track down a tricky situation for a joint customer
                reason: I like working with 3rd party because it give a difference perspective to our products. However when working with 3rd part who may not have same KIP standers as us it becomes tricky to help joint customer in a timely manner.
                d. Identify, file (and, where possible, resolve) bugs in private and public Vercel/Next.js repos on GitHub
                reason: In my experience it take a big chuck of day to report bug and when there is no bug is not action in a timely manner it triggers OCD which means I keeping following up with engineering team.
                e. Work with the product team to develop a new feature based on feedback from customers
                reason: In my experience I have suggested many features and driven them to production, however not all features go live which is dis hearting. So even though I enjoy working with product team it is not my most favorite task.

2.  What do you want to learn or do more of at work?
    Ans: I am always eager to take on new challenges and learn additional skills that will help me grow in my career. At work, I would love to have the opportunity to work on innovative projects that push the boundaries of what is possible.
    Specifically, I am very interested in working on new product features and initiatives that solve real customer problems in novel ways.
    I enjoy the process of ideating, prototyping, and iterating on new concepts until we land on a solution that delights users.
    In addition, I would relish the chance to drive the implementation and rollout of these new features. This involves collaborating cross-functionally with engineering, design, and product management to bring the vision to life. It also entails working closely with customers to gather feedback and ensure the feature is meeting their needs.
    Ultimately, I am passionate about continuous learning and improvement, both for myself and the products I work on. I would welcome any opportunity to expand my skill set, take on more responsibility, and make a meaningful impact through my work. Tackling new challenges head-on is how I grow as a professional.

3.  Describe how you solved a challenge or technical issue that you faced in a previous role
    (preferably in a previous support role). How did you determine that your solution was
    successful?
    Ans: As a developer support associate our goal is to reduce the time take to resolve(TTR) developer queries. When I was diving deep into my case work for the year I observed that my throttling cases was taking up to 10 days to resolve. So I took up the task of gather all throttling related case for the team and dive deep. - I observed that team average is more than 10 days while less then 5% of throttling increase requests were approved which was creating bad developer experience. - So, I revisited the whole workflow from case creation to resolution for 100 case sample(from 680 case) to understand and identify the gapes in process. - By implementing throttling guide in Documentation and providing a better contact us form for throttling issue I was able to reduce case volume by 30%(quarter on quarter) - By working with Solution Architects and create a separate communication channels for throttling cases I was able to reduce time take to resolve(TTR) from 10+ days to 6 days.

        By improving the TTR and reducing case count it was evident that changes implemented by me has improved developer experience(reduced HDM NOs).

4.  When would you choose to use Edge Functions, Serverless Functions, or Edge
    Middleware with Vercel?
    Ans: Choosing between these 3 one should consider the specific requirements of the project and the benefits each option offers:
    Edge Functions: These are serverless functions that run at the edge of the network, closest to the user. They are ideal for caching, content filtering, and other tasks that require low latency and high performance. Edge Functions are particularly useful for applications that need to handle a high volume of requests and require fast response times.
    NOTE: Edge function has a
    Serverless Functions: These are cloud-based functions that run on demand and scale automatically. They are suitable for tasks that require more computational power and memory than Edge Functions can provide. Serverless Functions are ideal for complex computations, data processing, and other tasks that require more resources.
    Edge Middleware: This is a type of middleware that runs at the edge of the network, providing a layer of abstraction between the client and the server. Edge Middleware is useful for tasks such as caching, content compression, and SSL termination. It is particularly effective for applications that require a high level of customization and control over the flow of data.
    In simple words, you would choose Edge Functions for tasks that require low latency and high performance, Serverless Functions for tasks that require more computational power and memory than Edge Functions and Edge Middleware for tasks that require a high level of customization and control over data flow.

        Research:
        >> Vercel doc "Ask AI"
        https://vercel.com/docs/functions
        https://vercel.com/docs/functions/edge-middleware

5.  Imagine a customer writes in requesting help with a build issue on a framework or
    technology that you've not seen before. How would you begin troubleshooting this and
    what questions would you ask the customer to understand the situation better?
    Ans:
    Basic of Support etiquette: - Acknowledge the problem. - Paraphrase the question asked and letting them know you could not find said framework in the documentation as a way of showing them that 'I have checked and I could not find what you are talking about? please help with the resources you used?'
    Asking for more information: - Ask what framework they have used. - Ask for details of project if there are many projects in Developer's versal account. - The specific error message or log output they are seeing. - The exact steps they have taken to reproduce the issue.
    Ask about the environment to replicate: - Environment details like versions used

            Email can look like this:
            ___________________
            Hello from Vercel support team, My name is Ram.
            From your email I understand that when you are using [name of framework or technology] you are facing issues.
            When I checked our documenting and resources I could not find any details about [name of framework or technology] you are using as your referring to our official documentation for this build or some 3rd party resource. If you are using 3rd party resource please provide me the links.
            Please let me know which project from all your vercel projects this build issue is effecting?
            To troubleshoot further please provide below details:
                - specific error message
                - log output
                - The exact steps they have taken to reproduce the issue.
                - To replicate this issue please share Environment of your project.
            Please refer to link below to see framework that we officially support:
            https://vercel.com/docs/frameworks

6.  The customer from question 5 replies to your response with the below:

“I’m so frustrated. I’ve been trying to make this work for hours and I just can’t figure it
out. It must be a platform issue so just fix it for me instead of asking me questions.”
Please write a follow-up reply to the customer.

    Ans:
        Hello from Vercel support team, My name is Ram.
        Thank you for reaching out to Vercel support. I'm happy to help you troubleshoot your issue you're experiencing with your project.
        As you believe this to be a system issue I have check our incident reports and haven't found any issues, however your could be a fist incident.
        To better understand the situation, could you please provide more details about your project? Specifically, could you tell me:
            - specific error message
            - log output
            - The exact steps they have taken to reproduce the issue.
            - To replicate this issue please share Environment of your project.

        If possible could you please provide me a reproducible example of the issue.

        Once I have this information, I'll be happy to work with you to identify and resolve the issue.

7.  A customer writes in to the Helpdesk asking "How do I do a redirect from the /blog
    path to https://example.com?" Please write a reply to the customer. Feel free to add any
    information about your decision making process after the reply.

        Ans:
        Email:
        _________
            Hello from Vercel support team, My name is Ram.
            I understand that you wish to redirect your website traffic from /blog path to https://example.com
            You can achieve this by setting up a rewrite in your next.config.js file. Here's an example of how you can do this:
                module.exports = {
                    async rewrites() {
                        return [
                            {
                                source: '/blog',
                                destination: 'https://example.com/blog',
                            },
                            {
                                source: '/blog/:slug',
                                destination: 'https://example.com/blog/:slug', // Matched parameters can be used in the destination
                            },
                                ]
                    },
                }

            You can read more about rewrite in our documentation link: https://vercel.com/docs/edge-network/rewrites#rewrites-on-vercel

        Research:
        Used keywords routes and understood basics of rewrites to suggest this answer
        https://vercel.com/docs/edge-network/rewrites#rewrites-on-vercel

8.  A customer is creating a site and would like their project not to be indexed by search
    engines. Please write a reply to the customer. Feel free to add any information about
    your decision making process after the reply.
    Ans:
    Email:
    ******\_\_******
    Hello from Vercel support team, My name is Ram.
    I understand that you do not want your project to be indexed by search engines.
    Since a Preview Deployment creates a new version of your site under a different domain, a search engine would consider it as a new website when crawling it and negatively impact your website ranking.
    To prevent that, the X-Robots-Tag HTTP header is automatically set to noindex for all Preview Deployments so that search engines do not accidentally index the Preview URLs.
    To learn more about the X-Robots-Tag, refer to link [Google Search Reference.](https://developers.google.com/search/docs/crawling-indexing/robots-meta-tag#xrobotstag)

        Research:
         https://vercel.com/docs/deployments/preview-deployments#search-engine-indexing

9.  What do you think is one of the most common problems which customers ask Vercel for
    help with? How would you help customers to overcome common problems, short-term
    and long-term?  
     Ans: I believe most common problems that developers ask Vercel for help with is likely to be build errors or issues with deploying their projects. This can include errors that prevent a project from building/running locally or while deploying.

        Short-term Support ::
        Documentation and Guides: Vercel can offer more detailed documentation indexed support tool which guides developer troubleshooting build errors, including specific scenarios and solutions for common issues like a workflow.
        Community Support: We from support can engage with the Vercel community through GitHub Discussions, where they can ask questions, share knowledge, and get help from other developers while we moderate the Discussions.

        Long-term Support ::
        Best Practices: Vercel recommends best practices for building and deploying projects, such as building locally before deploying to Vercel, which can help prevent common issues.
        Enterprise Support Plans: For businesses with critical workloads or time-sensitive deployments, Vercel offers support plans and SLAs that provide dedicated support and specific turnaround times for responses. Like a premium support.

10. How could we improve or alter this familiarization exercise?
    Ans: I would ask candidate in 4th question of this exercise to go through vercel documentation and note down features or aspects of documentation that stood out to him/her to familiarize them with versal documentation page.
