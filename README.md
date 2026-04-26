Reflection

Maintainable, Readable, and Adaptable Code

When writing programs, I focus on keeping my code modular, readable, and easy to maintain. In this course, that mainly came from how I designed and used the CRUD Python module in Project One and then reused it in Project Two. Instead of writing database logic directly inside the dashboard code, I separated it into its own class. This improved readability by enforcing separation of concerns. The dashboard handled user interaction and visualization, while the CRUD module handled database communication.

One major advantage of this approach is reusability. I was able to plug the same CRUD module into the dashboard without rewriting database queries. It also made debugging easier because I could isolate issues to either the database layer or the UI layer. This design also improves scalability, since additional features or data sources can be added without significantly modifying existing code. In the future, I could reuse this same module structure for other projects that require database access, such as web applications or APIs. I could also expand it by adding update and delete functionality or adapting it to work with different databases.

Problem-Solving Approach as a Computer Scientist

When approaching this project, I broke the problem down into smaller parts. First, I made sure I understood the client requirements from Grazioso Salvare, especially how they wanted to filter and visualize rescue animals. Then I focused on building the database connection and verifying that MongoDB queries using PyMongo returned the correct filtered data before integrating them into the dashboard.

This approach was different from earlier assignments because it required integrating multiple components instead of working on a single script. I had to think more about how systems interact, not just how individual pieces work. I also relied more on testing at each step, especially when working with MongoDB queries and making sure the dashboard displayed accurate results.

In the future, I would continue using this step-by-step approach, along with better planning upfront. For example, I would sketch out the database schema and expected queries before coding. I would also use more test cases, including edge cases where no results are returned, to make the system more robust.

Role of Computer Scientists and Impact

Computer scientists design and build systems that help organizations manage data and make better decisions. In this project, the dashboard I created allows a company like Grazioso Salvare to quickly filter and analyze animal data for rescue operations. Instead of manually searching through records, they can use the dashboard to identify suitable animals based on specific criteria.

This type of work matters because it improves efficiency and accuracy. By organizing data and presenting it visually, companies can make faster and more informed decisions. This reduces manual effort, minimizes human error, and allows faster decision-making in time-sensitive rescue situations. In a real-world scenario, this could directly impact how quickly animals are matched for rescue or adoption. Overall, projects like this show how software solutions can solve practical problems and add real value to an organization.
