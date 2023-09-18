---
CSC 510 Software Engineering\
Project Title - ShopSync
---

# Project Overview

From the five projects that were assigned to us, we decided on SLASH,
which we later renamed as ShopSync.Finding the greatest prices might
take a lot of time in the world of online shopping, where a lot of
e-commerce companies sell a wide range of goods. Enter ShopSync, a
platform for publicly accessible web APIs created to simplify online
buying. Utilizing this adaptable application, we can easily compare
prices on various websites by scraping information from well-known
e-commerce sites including Amazon, Walmart, Target, BestBuy, Costco, and
eBay.

SHOPSYNC is all about efficiency. It can save a lot of time by quickly
scanning and compiling offers from multiple internet merchants. This
puts an end to the hassle of manually going through numerous websites in
search of the greatest deals and rates. It offers easily available
public APIs that can quickly filter, sort, and search the data that has
been scraped. Additionally, Slash creates JSON answers, offering
customization options to suit particular needs.

# Team Collaboration

We effectively handled our work by assigning specific projects among
team members. We first looked closely at the code and documentation for
each project. After acquiring a thorough grasp, we talked about our
options and chose the most promising concept. The teamwork within our
group played a crucial role in turning the assignment into a successful
and functional project.

# Technical Challenges

Throughout the duration of the project, we encountered a series of
technical challenges. These challenges were primarily encountered due to
the dynamic nature of the software environment, where the updated software
components posed both opportunities as well as obstacles. We struggled
with the complexities brought about by these updates, including version
mismatches and clashing versions. Additionally, a few code errors
emerged as a challenge. In this section, we will provide a detailed
account of each of these challenges, our strategies for resolution, and
the valuable insights we gained from navigating these technical hurdles.

Firstly, we attempted to run all of the projects that were assigned to
us. While some of them did not have the best user interface, the others
had complex challenges like connection to DB. We were unable to run one
of the projects since the cross-origin resource sharing (CORS) was not
enabled, which disallowed the front-end to send the request to the
back-end.

After evaluating all the available options and attempting to execute
each of them, we ultimately selected 'Slash' as our project. The errors
we faced during implementation of Slash included:

1.  ValueError and ImportError: The older FastAPI version had outdated
    code. The update of the same caused a clash in other dependencies.

2.  ModuleNotFoundError: We encountered an error when attempting to
    import functions from another Python class. We were able to resolve it by appending our project’s root directory to PYTHONPATH.

3.  Code Error: The code was accessing keys in a dictionary without
    checking it's existence. That caused an error in the code.

# Addressing Technical Challenges

To tackle the challenges we encountered, we can implement several
practices to maintain the application's usability and ease of future
modifications:

Regularly updating the code to prevent package and version
discrepancies, and adopting shorter release cycles. Thoroughly
documenting the code, incorporating pertinent updates regarding
libraries. Verifying the documentation for relevant packages and
dependencies.

# Best Practices

We will be following the following best practices for developing the
following application.

1.  Following the PEP8 Style for keeping homogeneity throughout the
    application. It is critical that we adhere to the PEP 8 style rules
    to ensure consistency throughout our application. PEP 8 is a
    thorough reference for organizing our Python code. Many elements,
    such as variables, functions, classes, and packages, must be named
    in Python development. Choosing meaningful and appropriate names now
    can result in significant time and energy savings afterward. These
    well-chosen names reveal the role of each variable, function, or
    class. Furthermore, they assist us in avoiding incorrect names that
    could potentially lead to difficult debugging scenarios. We will
    continue to use the PEP 8 formatting requirements in our code to
    preserve consistency and improve readability.

2.  Documenting the code properly Thoroughly documenting code is
    critical, especially in collaborative software development
    environments involving numerous teams or individuals. Team members
    must understand the codebase, including its functionality and how it
    integrates into the wider application. As a result, we are devoted
    to detailed code documentation in order to allow seamless
    collaboration and avoid any bottlenecks that may prohibit team
    members from contributing efficiently.

3.  Writing Object-Oriented Code Using object-oriented programming
    techniques improves not just code understanding but also efficiency.
    We enhance code reusability and shareability by encapsulating
    functionality within classes. Data abstraction assures data
    integrity and security, while polymorphism allows us to utilize a
    consistent interface for diverse objects, making it easier to write
    efficient code. Furthermore, inheritance allows several classes to
    inherit properties from a superclass, minimizing redundancy and
    improving application speed. Our adherence to these object-oriented
    concepts will add to our application's enhanced functionality.

# Conclusion

After evaluating all five assigned projects based on rubric and comparing their performance, we determined that "Slash" received the highest score. Despite encountering a few challenges during the project's execution, our teamwork and collaborative efforts allowed us to overcome these issues and successfully complete the project.The primary objective of this project is to simplify the process of finding the best online shopping deals. To ensure the project remains user-friendly, maintainable, and open to future improvements, we are committed to adhering to coding standards such as PEP 8, thorough code documentation, and good coding practices.
