# SNHU-CS255: System Analysis and Design
**Term:** September - October 2026

## Overview
This class was about designing systems, whether it be code, an organization, a workflow, or any other situation where data or tasks flow. It covered the various different ways a system can be described, whether it be its use case, its composition, its organization, the way those parts interact with one another, or describing the exact mechanisms it uses to achieve one of its use cases. It discussed a layered approach where the system could be clearly described as a whole, or could be described in minute detail when required.

## Essential Questions & Professional Reflection

### Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
DriverPass was an online portal-based education platform for driver's education. They wanted the system to handle a range of tasks, from housing education modules for students to take online to acting as a scheduling hub for students to schedule driving lessons with their instructor. The same software was to be used for clients as staff, so it needed different user types with different dashboards and access to different tasks. Driving instructors needed to be able to track their schedule, their students' progress, and provide feedback. As well as self-signup online, the secretary needed to be able to create accounts for other people if they called or walked into the office. IT and the CEO needed maintenance and reporting access. Separate dashboards were designed to facilitate each role in their required tasks.

### What did you do particularly well?
I really envisioned myself in each of these roles. I didn't just envision the exact pieces of the system that the client explicitly asked for, but also considered what designs and tools would make it easier for each user to use.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
This is a tricky one. Overall, I think I did a fairly good job, but I keep thinking of tiny little things that could have been better. I envisioned the overall system well, but I could have designed each of the individual pieces in further detail. It is very clear that when designing a whole system, it is important the designer and the client agree on a definition of done. The designer could always add more detail to exactly how each of these pieces is supposed to work, but there comes a point where reaching a certain degree of granularity is no different than actually coding the project yourself. Every single layer of detail could be zoomed in to describe the exact process in increasing detail, and it can be hard to decide exactly how much detail is or isn't needed in any particular layer of the design.

### How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?
A platform that is difficult to use is a platform no one will want to use. Usability, clarity, and functionality need to be built into the system at the architectural level, because if the system isn't designed around them, it can take much more effort to add them into the system later. If a system serves a need but doesn't do it well, it creates a simple opening for a competitor to create a similar product that users will like better.

### How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?
I think a layered and varied design is necessary. Before the inner workings of a system are designed, it is very important that the designer and the client have a clear and shared understanding of what the system needs to do and very roughly how it will go about doing that. Designing deeper systems before this is clear leads to repeated work. Next, I like to think about the design similar to Object Oriented Programming (OOP). In OOP, different pieces of a system need to understand what other pieces do, and what resources they will need to do it, but they don't need to understand exactly how it is done. A board or executive team needs to clearly understand the upper layers of the system design, but only someone like the Chief Operations Officer need to dig into the weeds of the deeper design charts and understand exactly how each piece works. I think of this rather similar to the principles of Polymorphism and Abstraction.

