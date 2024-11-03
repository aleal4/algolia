# Email Questions and Responses

## Question 1

Hello,

I'm new to search engines, and there are a lot of concepts I'm not educated on. To make my onboarding smoother, it'd help if you could provide me with some definitions of the following concepts: Records Indexing. I'm also struggling with understanding what types of metrics would be useful to include in the "Custom Ranking."

Cheers,  
George

---

## Reply 1

Hi George,

Absolutely! Here’s a more colorful explanation using analogies.

Definitions
**Records:** Think of records as individual books in a library. Each book contains specific information (like a story or data) that can be checked out and read. Just like each book has its own title and author, each record has its own unique data.

**Indexing:** Imagine indexing as creating a catalog for that library. Instead of searching through every book to find what you need, the catalog organizes the books by title, author, or genre. This way, you can quickly locate a book without sifting through the entire collection. Indexing does the same for data, making it easy to find relevant information quickly.

Examples of Custom Ranking Attributes: 
**Sales Rank:** Prioritizes items based on how well they sell.
**Stock Levels:** Ranks items based on availability.
**Ratings:** Uses customer ratings to influence visibility.
**Boolean Attributes:** Such as whether an item is on sale or offers free shipping.

I hope this make things clearer! Let me know if you have any more questions.

Augusto Leal | Solutions Engineer

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

Augusto Leal | Solutions Engineer  

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

Augusto Leal | Solutions Engineer  
