# Email Questions and Responses

## Question 1

Hello,

I'm new to search engines, and there are a lot of concepts I'm not educated on. To make my onboarding smoother, it'd help if you could provide me with some definitions of the following concepts: Records Indexing. I'm also struggling with understanding what types of metrics would be useful to include in the "Custom Ranking."

Cheers,  
George

---

## Reply 1

Hi George,

Thank you for reaching out with your questions! I’m happy to help clarify these concepts for you.

A **record** is essentially an individual entry in your dataset—think of it like a single product in a catalog. On a technical level, records are similar to the individual rows in an Excel spreadsheet and typically contain various pieces of information. For example, a product record might include attributes such as name, price, rating, and description. These attributes are crucial because they represent the terms customers use to find products, while metrics like price and rating are often used for filtering and sorting search results.

**Indexing** refers to how we organize and manage all those records. An index acts like a roadmap for your data, allowing us to retrieve records quickly when users search for specific terms. When customers enter keywords that describe products, indexing helps match those keywords with the appropriate records efficiently. Don’t worry too much about the technical details—our dashboards simplify this process by allowing you to make key decisions about your data while Algolia handles the indexing in the background.

Regarding **Custom Ranking**, think of it as a way to prioritize search results when multiple entries match a user's query. You can specify which attribute should be used for ranking, helping to highlight your most popular or highest-rated products. For instance, if someone searches for "iPhone," you can set up Custom Ranking to display the highest-rated models first, enhancing the overall search experience for your customers.

Thanks again for your excellent questions! Below, I’ve included some links for further reading on these topics.

If you’d like more information or would prefer a walkthrough of these concepts in Algolia, feel free to reach out! I’d be happy to schedule a Zoom call.

Best regards,

Augusto Leal 
Solutions Engineer  

[Custom Ranking Guide](https://www.algolia.com/doc/guides/managing-results/must-do/custom-ranking/)  
[Preparing Your Data](https://www.algolia.com/doc/guides/sending-and-managing-data/prepare-your-data/)

---

## Question 2

Hello,

Sorry to give you feedback that I know you may not want to hear, but I really dislike the new dashboard design. Clearing and deleting indexes now require several clicks, which is inconvenient for me while iterating.

Regards,  
Matt

---

## Reply 2

Hi Matt,

I hope you're doing well! Thank you for sharing your feedback; it’s incredibly valuable for our ongoing improvements. I understand how frustrating it can be when changes affect your workflow, and I’ll definitely pass your thoughts along to our product team.

In the meantime, I’d like to suggest a couple of potential solutions. If you're working with a single index over an extended period, consider bookmarking it for quick access. This way, you'll only need two clicks to clear or delete that index.

![Indices Screenshot](indices.png)

Additionally, if you want your index to be regularly rebuilt with the latest dataset, take advantage of the built-in Connectors functionality in the dashboard. For example, I recently set up an index connected to a remote JSON file that updates every hour. Here’s a screenshot showing how to navigate this feature:

![New Connector Screenshot](newconnector.png)

If these options don’t meet your needs right now, I can help you write a script that utilizes the API to delete an index or clear its records at the push of a button.

[Delete Indices Documentation](https://www.algolia.com/doc/guides/sending-and-managing-data/manage-indices-and-apps/manage-indices/how-to/delete-indices/?client=javascript/)

Thank you again for your feedback; it’s crucial in helping us enhance our platform. If there's anything else I can assist you with regarding these solutions, please let me know!

Best regards,

Augusto Leal  
Solutions Engineer  

---

## Question 3

Hi,

I'm looking to integrate Algolia into my website. Will this require a lot of development work? What does the high-level process look like?

Regards,  
Leo

---

## Reply 3

Hi Leo,

Thanks for reaching out! The complexity of implementation can vary, but it can often be quite straightforward—sometimes just requiring a few clicks and importing some predefined libraries.

I recommend starting with this quick 1-minute video that outlines how simple implementation can be in just three steps:

[Quick Implementation Video](https://www.youtube.com/watch?v=yA4KISBv_88/)

Algolia offers integrations with over 40 popular web and mobile technologies:

[Algolia Integrations](https://www.algolia.com/developers/integrations/)

We also provide InstantSearch libraries that come with ready-made UI components for various frameworks including vanilla JavaScript, React, Vue, Angular, Android, and iOS.

If your integration is more complex than that, I'm here to help make the process as smooth as possible. Could you share what your current tech stack looks like? This way, I can tailor my suggestions specifically for your setup.

Alternatively, if you'd prefer real-time discussion, feel free to book some time on my calendar:

[Schedule a Meeting](http://calendly.com/insertmylinkhere/)

Looking forward to hearing from you!

Best regards,

Augusto Leal  
Solutions Engineer  
